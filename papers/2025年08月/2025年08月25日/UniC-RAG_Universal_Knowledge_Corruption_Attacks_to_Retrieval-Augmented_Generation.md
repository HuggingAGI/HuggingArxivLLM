# UniC-RAG：面向检索增强生成的通用知识污染攻击

发布时间：2025年08月25日

`RAG` `基础理论`

> UniC-RAG: Universal Knowledge Corruption Attacks to Retrieval-Augmented Generation

# 摘要

> 检索增强生成（RAG）系统已在金融、医疗、网络安全等众多领域的实际场景中广泛应用。但研究发现，这类系统存在知识污染攻击漏洞：攻击者可向其知识库植入对抗性文本，诱导大语言模型（LLM）生成特定输出。当前研究多局限于攻击特定查询或主题（及关键词）相近的查询，而本文提出的通用知识污染攻击方法UniC-RAG则突破了这一限制。该方法通过联合优化少量对抗性文本，能同时攻击海量不同主题、不同领域的用户查询，帮助攻击者实现多样化恶意目标，如诱导用户访问恶意网站、触发有害命令执行或发起拒绝服务攻击。我们将UniC-RAG构建为优化问题，并设计了包含基于平衡相似度聚类的高效解决方案，显著提升了攻击效能。实验验证表明，UniC-RAG攻击效果卓越，性能远超基线：仅需向百万级文本知识库注入100条对抗性文本，即可同时攻击2000条用户查询，成功率超90%。此外，现有防御措施在UniC-RAG面前形同虚设，这也凸显了RAG系统亟需全新防御机制的紧迫性。

> Retrieval-augmented generation (RAG) systems are widely deployed in real-world applications in diverse domains such as finance, healthcare, and cybersecurity. However, many studies showed that they are vulnerable to knowledge corruption attacks, where an attacker can inject adversarial texts into the knowledge database of a RAG system to induce the LLM to generate attacker-desired outputs. Existing studies mainly focus on attacking specific queries or queries with similar topics (or keywords). In this work, we propose UniC-RAG, a universal knowledge corruption attack against RAG systems. Unlike prior work, UniC-RAG jointly optimizes a small number of adversarial texts that can simultaneously attack a large number of user queries with diverse topics and domains, enabling an attacker to achieve various malicious objectives, such as directing users to malicious websites, triggering harmful command execution, or launching denial-of-service attacks. We formulate UniC-RAG as an optimization problem and further design an effective solution to solve it, including a balanced similarity-based clustering method to enhance the attack's effectiveness. Our extensive evaluations demonstrate that UniC-RAG is highly effective and significantly outperforms baselines. For instance, UniC-RAG could achieve over 90% attack success rate by injecting 100 adversarial texts into a knowledge database with millions of texts to simultaneously attack a large set of user queries (e.g., 2,000). Additionally, we evaluate existing defenses and show that they are insufficient to defend against UniC-RAG, highlighting the need for new defense mechanisms in RAG systems.

[Arxiv](https://arxiv.org/abs/2508.18652)