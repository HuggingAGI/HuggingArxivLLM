# 标题：语言模型的上下文完整性清洗

发布时间：2025年01月31日

`LLM理论

理由：这篇论文主要讨论了情境完整性（CI）理论在评估大型语言模型（LLMs）隐私影响中的应用，并分析了现有研究是否偏离了CI的核心原则。论文内容涉及LLMs的理论框架和隐私评估方法，属于对LLMs的理论探讨，因此归类为“LLM理论”。` `隐私保护` `人工智能`

> Position: Contextual Integrity Washing for Language Models

# 摘要

> 机器学习社区逐渐认识到情境完整性（CI）是评估大型语言模型（LLMs）隐私影响的有力框架。CI理论强调在隐私规范下共享信息，能够整合社会、法律、政治和技术等多维度因素，为LLMs隐私评估提供全面支持。然而，当前对CI的应用存在“CI洗白”现象，即未遵循理论核心原则，可能导致错误结论和隐私设计缺陷。本文系统梳理了CI的四大基本原则，分析了现有研究是否偏离这些原则，并指出LLMs实验中的潜在问题，如提示敏感性和位置偏差。

> Machine learning community is discovering Contextual Integrity (CI) as a useful framework to assess the privacy implications of large language models (LLMs). This is an encouraging development. The CI theory emphasizes sharing information in accordance with privacy norms and can bridge the social, legal, political, and technical aspects essential for evaluating privacy in LLMs. However, this is also a good point to reflect on use of CI for LLMs. This position paper argues that existing literature adopts CI for LLMs without embracing the theory's fundamental tenets, essentially amounting to a form of "CI-washing." CI-washing could lead to incorrect conclusions and flawed privacy-preserving designs. We clarify the four fundamental tenets of CI theory, systematize prior work on whether they deviate from these tenets, and highlight overlooked issues in experimental hygiene for LLMs (e.g., prompt sensitivity, positional bias).

[Arxiv](https://arxiv.org/abs/2501.19173)