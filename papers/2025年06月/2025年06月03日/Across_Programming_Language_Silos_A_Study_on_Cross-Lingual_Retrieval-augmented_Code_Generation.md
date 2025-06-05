# 跨语言检索增强代码生成研究：打破编程语言的壁垒

发布时间：2025年06月03日

`LLM应用` `代码生成` `多语言系统`

> Across Programming Language Silos: A Study on Cross-Lingual Retrieval-augmented Code Generation

# 摘要

> # 摘要  
目前的研究主要集中在单语言设置下的大型语言模型（LLMs）与检索增强代码生成（RACG）的结合，尚未探索跨语言的有效性和安全性。多语言RACG系统在跨编程语言（PLs）迁移代码库方面具有重要价值，然而在跨语言迁移过程中可能面临错误传播的风险，例如对抗性数据损坏，这给多语言RACG系统带来了挑战。我们构建了一个涵盖13种编程语言、近14,000个实例的数据集，以探索多语言RACG系统的实用性和鲁棒性。我们的研究揭示了四个关键发现：（1）有效性：多语言RACG显著提升了多语言代码LLMs的生成能力；（2）不平等性：在RACG中，Java的跨语言实用性优于Python；（3）鲁棒性：对抗性攻击对单语言RACG的性能有显著负面影响，但在跨语言场景下影响有所缓解；令人意外的是，扰动后的代码在跨语言场景下可能提升RACG性能；（4）专业化：领域特定的代码检索器在性能上显著优于通用文本检索器。这些发现为开发高效且安全的多语言代码助手奠定了基础。

> Current research on large language models (LLMs) with retrieval-augmented code generation (RACG) mainly focuses on single-language settings, leaving cross-lingual effectiveness and security unexplored. Multi-lingual RACG systems are valuable for migrating code-bases across programming languages (PLs), yet face risks from error (e.g. adversarial data corruption) propagation in cross-lingual transfer. We construct a dataset spanning 13 PLs with nearly 14k instances to explore utility and robustness of multi-lingual RACG systems. Our investigation reveals four key insights: (1) Effectiveness: multi-lingual RACG significantly enhances multi-lingual code LLMs generation; (2) Inequality: Java demonstrate superior cross-lingual utility over Python in RACG; (3) Robustness: Adversarial attacks degrade performance significantly in mono-lingual RACG but show mitigated impacts in cross-lingual scenarios; Counterintuitively, perturbed code may improve RACG in cross-lingual scenarios; (4) Specialization: Domain-specific code retrievers outperform significantly general text retrievers. These findings establish foundation for developing effective and secure multi-lingual code assistants.

[Arxiv](https://arxiv.org/abs/2506.03535)