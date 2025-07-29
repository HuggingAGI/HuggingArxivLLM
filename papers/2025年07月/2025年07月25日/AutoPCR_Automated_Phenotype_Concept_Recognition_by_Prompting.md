# AutoPCR: 基于提示的表型概念识别自动化

发布时间：2025年07月25日

`LLM应用

理由：这篇论文探讨了如何将大型语言模型（LLM）应用于生物医学文本挖掘中的表型概念识别任务，展示了其实际应用和性能提升。` `生物医学` `知识图谱`

> AutoPCR: Automated Phenotype Concept Recognition by Prompting

# 摘要

> 表型概念识别（CR）是生物医学文本挖掘中的重要任务，支持临床诊断和知识图谱构建等应用。然而，现有方法通常需要针对特定本体进行训练，且难以在多种文本类型和不断演变的生物医学术语间实现泛化。我们提出了AutoPCR，这是一种基于提示的表型CR方法，无需特定本体的训练。AutoPCR通过三个阶段进行概念识别：实体提取阶段采用基于规则和神经标签策略的混合方法，候选检索阶段使用SapBERT，实体链接阶段则通过提示大型语言模型完成。在四个基准数据集上的实验表明，AutoPCR在提及级别和文档级别评估中均表现出最佳的平均性能和最稳健的性能，超越了先前的最先进方法。进一步的消融和迁移研究验证了其归纳能力和对新本体的泛化能力。

> Phenotype concept recognition (CR) is a fundamental task in biomedical text mining, enabling applications such as clinical diagnostics and knowledge graph construction. However, existing methods often require ontology-specific training and struggle to generalize across diverse text types and evolving biomedical terminology. We present AutoPCR, a prompt-based phenotype CR method that does not require ontology-specific training. AutoPCR performs CR in three stages: entity extraction using a hybrid of rule-based and neural tagging strategies, candidate retrieval via SapBERT, and entity linking through prompting a large language model. Experiments on four benchmark datasets show that AutoPCR achieves the best average and most robust performance across both mention-level and document-level evaluations, surpassing prior state-of-the-art methods. Further ablation and transfer studies demonstrate its inductive capability and generalizability to new ontologies.

[Arxiv](https://arxiv.org/abs/2507.19315)