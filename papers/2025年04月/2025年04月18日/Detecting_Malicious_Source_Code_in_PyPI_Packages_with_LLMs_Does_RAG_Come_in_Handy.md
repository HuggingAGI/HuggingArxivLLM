# 利用大语言模型识别PyPI包中的恶意代码：RAG能否发挥重要作用？

发布时间：2025年04月18日

`LLM应用` `网络安全` `开源软件`

> Detecting Malicious Source Code in PyPI Packages with LLMs: Does RAG Come in Handy?

# 摘要

> 开源生态系统（如PyPI）中的恶意软件包正日益增长安全风险。与传统漏洞不同，这些软件包是故意设计用来欺骗用户的，由于攻击手段不断演变以及缺乏结构化的数据集，使得检测变得十分困难。本研究中，我们通过实证评估了大型语言模型（LLMs）、增强检索生成（RAG）和少量样本学习在检测恶意源代码方面的有效性。我们对LLMs进行了微调，并整合了YARA规则、GitHub安全公告和恶意代码片段，旨在提高分类的准确性。然而，我们发现了一个出人意料的结果：尽管RAG预计能提升预测性能，但在实际评估中表现平平，准确率一般。相反，少量样本学习则更为有效，它显著提升了恶意代码的检测能力，达到了97%的准确率和95%的平衡准确率，超越了传统的RAG方法。因此，未来的工作应致力于扩展结构化的知识库、优化检索模型，并探索混合式人工智能驱动的网络安全解决方案。

> Malicious software packages in open-source ecosystems, such as PyPI, pose growing security risks. Unlike traditional vulnerabilities, these packages are intentionally designed to deceive users, making detection challenging due to evolving attack methods and the lack of structured datasets. In this work, we empirically evaluate the effectiveness of Large Language Models (LLMs), Retrieval-Augmented Generation (RAG), and few-shot learning for detecting malicious source code. We fine-tune LLMs on curated datasets and integrate YARA rules, GitHub Security Advisories, and malicious code snippets with the aim of enhancing classification accuracy. We came across a counterintuitive outcome: While RAG is expected to boost up the prediction performance, it fails in the performed evaluation, obtaining a mediocre accuracy. In contrast, few-shot learning is more effective as it significantly improves the detection of malicious code, achieving 97% accuracy and 95% balanced accuracy, outperforming traditional RAG approaches. Thus, future work should expand structured knowledge bases, refine retrieval models, and explore hybrid AI-driven cybersecurity solutions.

[Arxiv](https://arxiv.org/abs/2504.13769)