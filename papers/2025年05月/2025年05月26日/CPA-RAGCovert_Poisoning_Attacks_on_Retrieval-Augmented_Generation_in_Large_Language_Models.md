# CPA-RAG: 大型语言模型中的检索增强生成中的隐蔽投毒攻击

发布时间：2025年05月26日

`RAG` `人工智能`

> CPA-RAG:Covert Poisoning Attacks on Retrieval-Augmented Generation in Large Language Models

# 摘要

> 检索增强生成（RAG）通过整合外部知识来提升大型语言模型（LLMs）的表现，但其开放性也引入了可被投毒攻击利用的漏洞。现有针对RAG系统的投毒方法存在一些局限性，例如对抗文本的泛化能力较差且缺乏流畅性。本文提出了一种黑盒对抗框架CPA-RAG，该框架能够生成与查询相关的文本，通过操纵检索过程来诱导目标答案的产生。所提出的方法结合了基于提示的文本生成、多LLM的跨指导优化以及基于检索器的评分机制，以构建高质量的对抗样本。我们在多个数据集和LLMs上进行了广泛的实验来评估其有效性。实验结果表明，当top-k检索设置为5时，该框架的攻击成功率超过90%，与白盒方法相当，并且在不同top-k值下始终保持约5个百分点的优势。此外，它在多种防御策略下比现有黑盒基线高出14.5个百分点。更重要的是，我们的方法成功地攻破了部署在阿里巴巴百链平台上的商用RAG系统，证明了其在实际应用中潜在的威胁。这些发现强调了构建更 robust 和安全的RAG框架以抵御投毒攻击的必要性。

> Retrieval-Augmented Generation (RAG) enhances large language models (LLMs) by incorporating external knowledge, but its openness introduces vulnerabilities that can be exploited by poisoning attacks. Existing poisoning methods for RAG systems have limitations, such as poor generalization and lack of fluency in adversarial texts. In this paper, we propose CPA-RAG, a black-box adversarial framework that generates query-relevant texts capable of manipulating the retrieval process to induce target answers. The proposed method integrates prompt-based text generation, cross-guided optimization through multiple LLMs, and retriever-based scoring to construct high-quality adversarial samples. We conduct extensive experiments across multiple datasets and LLMs to evaluate its effectiveness. Results show that the framework achieves over 90\% attack success when the top-k retrieval setting is 5, matching white-box performance, and maintains a consistent advantage of approximately 5 percentage points across different top-k values. It also outperforms existing black-box baselines by 14.5 percentage points under various defense strategies. Furthermore, our method successfully compromises a commercial RAG system deployed on Alibaba's BaiLian platform, demonstrating its practical threat in real-world applications. These findings underscore the need for more robust and secure RAG frameworks to defend against poisoning attacks.

[Arxiv](https://arxiv.org/abs/2505.19864)