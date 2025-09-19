# 面向推荐系统的LLM特征提取器：关键因素何在？——提示词、模型与适配的系统性分析

发布时间：2025年09月18日

`LLM应用` `零售与电商`

> What Matters in LLM-Based Feature Extractor for Recommender? A Systematic Analysis of Prompts, Models, and Adaptation

# 摘要

> 利用大型语言模型（LLMs）生成语义特征已成为增强序列推荐系统（SRS）的有效范式，其典型流程包括物品文本处理、LLM特征提取及下游模型适配三个阶段。然而，现有方法在提示方式、架构设计与适配策略上差异显著，导致难以公平比较设计方案，也无法明确性能提升的核心驱动因素。为此，我们提出模块化分析框架RecXplore，将LLM特征提取流程拆解为数据处理、语义特征提取、特征适配和序列建模四大模块。该框架不依赖新技术，而是通过整合现有方法，实现对各模块的独立系统性探究。实验结果显示，在四个公共数据集上，仅组合现有技术中的最优设计（无需穷举搜索），即可在NDCG@5和HR@5上分别取得18.7%与12.7%的相对提升，显著优于强基线模型。这些发现证实，模块化基准测试能有效识别优质设计模式，为LLM增强推荐领域的标准化研究提供有力支持。

> Using Large Language Models (LLMs) to generate semantic features has been demonstrated as a powerful paradigm for enhancing Sequential Recommender Systems (SRS). This typically involves three stages: processing item text, extracting features with LLMs, and adapting them for downstream models. However, existing methods vary widely in prompting, architecture, and adaptation strategies, making it difficult to fairly compare design choices and identify what truly drives performance. In this work, we propose RecXplore, a modular analytical framework that decomposes the LLM-as-feature-extractor pipeline into four modules: data processing, semantic feature extraction, feature adaptation, and sequential modeling. Instead of proposing new techniques, RecXplore revisits and organizes established methods, enabling systematic exploration of each module in isolation. Experiments on four public datasets show that simply combining the best designs from existing techniques without exhaustive search yields up to 18.7% relative improvement in NDCG@5 and 12.7% in HR@5 over strong baselines. These results underscore the utility of modular benchmarking for identifying effective design patterns and promoting standardized research in LLM-enhanced recommendation.

[Arxiv](https://arxiv.org/abs/2509.14979)