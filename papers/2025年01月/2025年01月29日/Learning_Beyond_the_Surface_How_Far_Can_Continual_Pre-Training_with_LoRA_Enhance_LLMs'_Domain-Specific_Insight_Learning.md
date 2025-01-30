# 深入学习的边界：LoRA持续预训练如何提升LLMs的领域洞察力？

发布时间：2025年01月29日

`LLM理论

理由：这篇论文主要探讨了持续预训练对大型语言模型（LLMs）在特定领域数据中提取深层见解能力的影响，特别是通过修改文档来提升模型的学习能力。这涉及到LLMs的理论研究，尤其是如何通过训练方法和数据调整来改进模型的表现。因此，将其分类为LLM理论是合适的。`

> Learning Beyond the Surface: How Far Can Continual Pre-Training with LoRA Enhance LLMs' Domain-Specific Insight Learning?

# 摘要

> 大型语言模型（LLMs）在各类任务中表现卓越，但其从特定领域数据中提取并内化深层见解的能力仍有待挖掘。本研究探讨了持续预训练如何提升LLMs在陈述性、统计性和概率性见解上的学习能力。我们聚焦医学和金融两大领域，利用LoRA在现有数据集上训练LLMs。为评估每种见解类型，我们建立了基准，衡量持续预训练如何帮助模型超越表层知识。同时，我们研究了文档修改对捕捉见解的影响。结果显示，尽管对原始文档的持续预训练效果有限，但通过修改文档仅保留关键信息，显著提升了LLMs的见解学习能力。

> Large Language Models (LLMs) have demonstrated remarkable performance on various tasks, yet their ability to extract and internalize deeper insights from domain-specific datasets remains underexplored. In this study, we investigate how continual pre-training can enhance LLMs' capacity for insight learning across three distinct forms: declarative, statistical, and probabilistic insights. Focusing on two critical domains: medicine and finance, we employ LoRA to train LLMs on two existing datasets. To evaluate each insight type, we create benchmarks to measure how well continual pre-training helps models go beyond surface-level knowledge. We also assess the impact of document modification on capturing insights. The results show that, while continual pre-training on original documents has a marginal effect, modifying documents to retain only essential information significantly enhances the insight-learning capabilities of LLMs.

[Arxiv](https://arxiv.org/abs/2501.17840)