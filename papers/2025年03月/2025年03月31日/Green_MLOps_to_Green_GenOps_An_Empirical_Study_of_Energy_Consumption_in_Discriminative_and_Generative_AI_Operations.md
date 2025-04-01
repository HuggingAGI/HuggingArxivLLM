# 绿色 MLOps 到绿色 GenOps：判别式与生成式 AI 运维中的能耗实证研究

发布时间：2025年03月31日

`LLM应用

摘要讨论了大型语言模型（LLMs）在实际应用中的能耗表现，分析了不同模型规模和服务请求下的能耗情况，并提供了优化能耗的实用指南。这属于LLM的实际应用研究，因此归类为LLM应用。` `MLOps` `可持续AI`

> Green MLOps to Green GenOps: An Empirical Study of Energy Consumption in Discriminative and Generative AI Operations

# 摘要

> 本研究对判别式与生成式AI模型在真实MLOps管道中的能耗进行了深入实证调查。针对判别式模型，我们研究了不同架构和训练推理阶段的超参数设置，识别出有效的节能实践。对于生成式AI，我们重点评估了大型语言模型（LLMs）在不同模型规模和服务请求下的能耗表现。我们的研究采用了软件层面的功耗测量方法，确保结果在不同配置、模型和数据集之间易于复现。通过分析多个模型和硬件环境，我们揭示了各项指标间的关联，识别出影响能耗的关键因素。研究结果表明，优化判别式模型的架构、超参数和硬件配置可以在不牺牲性能的前提下显著降低能耗。对于LLMs而言，能效取决于模型规模、推理复杂度和请求处理能力之间的平衡，因为当利用率较低时，更大模型并不一定意味着更高能耗。本分析为设计绿色可持续的机器学习操作提供了实用指南，强调在保持性能的同时减少能耗和碳足迹。本文可作为基准，用于准确估算不同AI模型类型的总能耗。

> This study presents an empirical investigation into the energy consumption of Discriminative and Generative AI models within real-world MLOps pipelines. For Discriminative models, we examine various architectures and hyperparameters during training and inference and identify energy-efficient practices. For Generative AI, Large Language Models (LLMs) are assessed, focusing primarily on energy consumption across different model sizes and varying service requests. Our study employs software-based power measurements, ensuring ease of replication across diverse configurations, models, and datasets. We analyse multiple models and hardware setups to uncover correlations among various metrics, identifying key contributors to energy consumption. The results indicate that for Discriminative models, optimising architectures, hyperparameters, and hardware can significantly reduce energy consumption without sacrificing performance. For LLMs, energy efficiency depends on balancing model size, reasoning complexity, and request-handling capacity, as larger models do not necessarily consume more energy when utilisation remains low. This analysis provides practical guidelines for designing green and sustainable ML operations, emphasising energy consumption and carbon footprint reductions while maintaining performance. This paper can serve as a benchmark for accurately estimating total energy use across different types of AI models.

[Arxiv](https://arxiv.org/abs/2503.23934)