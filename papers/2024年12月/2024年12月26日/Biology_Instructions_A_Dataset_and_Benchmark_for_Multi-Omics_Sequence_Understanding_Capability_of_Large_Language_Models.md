# 生物学指令：大型语言模型多组学序列理解能力的数据集与基准

发布时间：2024年12月26日

`LLM应用

**理由**：这篇论文主要讨论了如何利用大型语言模型（LLMs）来处理多组学生物学任务，并开发了一个专门的数据集和基线模型（ChatMultiOmics）。这属于将LLMs应用于特定领域（生物学）的任务，因此归类为LLM应用。` `生物信息学` `多组学`

> Biology Instructions: A Dataset and Benchmark for Multi-Omics Sequence Understanding Capability of Large Language Models

# 摘要

> 大型语言模型在通用领域展现了强大的能力，推动了革命性的变革。然而，如何利用这些模型的海量知识来理解多组学生物学仍是一个待开发的领域。为填补这一空白，我们推出了Biology-Instructions，这是首个大规模多组学生物序列指令调优数据集，涵盖DNA、RNA、蛋白质和多分子，旨在连接大型语言模型（LLMs）与复杂生物序列任务。该数据集通过整合多样化的生物序列预测任务与高级推理能力，同时保持对话流畅性，显著提升了LLMs的多功能性。我们还发现，即使是最先进的LLMs，在没有专门预训练和指令调优的情况下，在处理生物序列相关的多组学任务时仍存在明显的性能瓶颈。为此，我们开发了ChatMultiOmics基线模型，采用创新的三阶段训练流程，展示了利用Biology-Instructions理解生物学的强大能力。Biology-Instructions和ChatMultiOmics作为公开资源，为LLMs与多组学序列分析的深度融合提供了重要支持。

> Large language models have already demonstrated their formidable capabilities in general domains, ushering in a revolutionary transformation. However, exploring and exploiting the extensive knowledge of these models to comprehend multi-omics biology remains underexplored. To fill this research gap, we first introduce Biology-Instructions, the first large-scale multi-omics biological sequences-related instruction-tuning dataset including DNA, RNA, proteins, and multi-molecules, designed to bridge the gap between large language models (LLMs) and complex biological sequences-related tasks. This dataset can enhance the versatility of LLMs by integrating diverse biological sequenced-based prediction tasks with advanced reasoning capabilities, while maintaining conversational fluency. Additionally, we reveal significant performance limitations in even state-of-the-art LLMs on biological sequence-related multi-omics tasks without specialized pre-training and instruction-tuning. We further develop a strong baseline called ChatMultiOmics with a novel three-stage training pipeline, demonstrating the powerful ability to understand biology by using Biology-Instructions. Biology-Instructions and ChatMultiOmics are publicly available and crucial resources for enabling more effective integration of LLMs with multi-omics sequence analysis.

[Arxiv](https://arxiv.org/abs/2412.19191)