# UniC-RAG：对检索增强生成的通用知识污染攻击

发布时间：2025年08月25日

`RAG` `基础理论`

> UniC-RAG: Universal Knowledge Corruption Attacks to Retrieval-Augmented Generation

# 摘要

> 检索增强生成（RAG）系统已在金融、医疗、网络安全等众多领域的实际应用中广泛落地。然而，多项研究表明RAG系统易受知识污染攻击——攻击者通过向其知识库注入对抗性文本，就能诱导大型语言模型（LLM）生成特定的恶意输出。现有研究多聚焦于攻击特定查询或主题（关键词）相似的查询。为此，我们提出了UniC-RAG——一种针对RAG系统的通用知识污染攻击方法。与传统方法不同，UniC-RAG通过联合优化少量对抗性文本，就能同时攻击大量主题与领域各异的用户查询，从而让攻击者达成多种恶意目的，比如诱导用户访问恶意网站、触发有害命令执行，或是发起拒绝服务攻击。我们将UniC-RAG建模为优化问题，并设计了高效求解方案，其中包括基于相似度的平衡聚类方法，以提升攻击效能。充分实验验证显示，UniC-RAG极具效能，且显著优于现有基线。例如，仅向百万级文本的知识库注入100条对抗性文本，UniC-RAG在同时攻击大量用户查询（如2000条）时，攻击成功率即可超过90%。此外，我们测试了现有防御手段，发现其难以抵御UniC-RAG，这凸显了RAG系统亟需新型防御机制。

> Retrieval-augmented generation (RAG) systems are widely deployed in real-world applications in diverse domains such as finance, healthcare, and cybersecurity. However, many studies showed that they are vulnerable to knowledge corruption attacks, where an attacker can inject adversarial texts into the knowledge database of a RAG system to induce the LLM to generate attacker-desired outputs. Existing studies mainly focus on attacking specific queries or queries with similar topics (or keywords). In this work, we propose UniC-RAG, a universal knowledge corruption attack against RAG systems. Unlike prior work, UniC-RAG jointly optimizes a small number of adversarial texts that can simultaneously attack a large number of user queries with diverse topics and domains, enabling an attacker to achieve various malicious objectives, such as directing users to malicious websites, triggering harmful command execution, or launching denial-of-service attacks. We formulate UniC-RAG as an optimization problem and further design an effective solution to solve it, including a balanced similarity-based clustering method to enhance the attack's effectiveness. Our extensive evaluations demonstrate that UniC-RAG is highly effective and significantly outperforms baselines. For instance, UniC-RAG could achieve over 90% attack success rate by injecting 100 adversarial texts into a knowledge database with millions of texts to simultaneously attack a large set of user queries (e.g., 2,000). Additionally, we evaluate existing defenses and show that they are insufficient to defend against UniC-RAG, highlighting the need for new defense mechanisms in RAG systems.

[Arxiv](https://arxiv.org/abs/2508.18652)