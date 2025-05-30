# # 探索电子健康记录基础模型的扩展定律

发布时间：2025年05月28日

`LLM应用`

> Exploring Scaling Laws for EHR Foundation Models

# 摘要

> 缩放定律深刻影响了大型语言模型的发展，通过系统性增加模型规模、数据集体量和计算资源，实现了性能的可预测提升。然而，这一理论在电子健康记录（EHRs）中的应用仍未得到充分探索。EHRs作为丰富、序列化且全球广泛存在的数据源，其结构与自然语言存在显著差异。本研究首次对EHR基础模型的缩放定律展开实证调查。通过在MIMIC-IV数据库的患者时间轴数据上，采用不同模型规模和计算预算训练Transformer架构，我们识别出一致的缩放模式，包括抛物线型IsoFLOPs曲线以及计算资源、模型参数、数据规模与临床效用之间的幂律关系。这些发现表明，EHR模型展现出与大型语言模型类似的缩放行为，为资源高效的训练策略提供了预测性见解。我们的研究结果为开发强大的EHR基础模型奠定了基础，这些模型有望革新临床预测任务并推动个性化医疗的发展。

> The emergence of scaling laws has profoundly shaped the development of large language models (LLMs), enabling predictable performance gains through systematic increases in model size, dataset volume, and compute. Yet, these principles remain largely unexplored in the context of electronic health records (EHRs) -- a rich, sequential, and globally abundant data source that differs structurally from natural language. In this work, we present the first empirical investigation of scaling laws for EHR foundation models. By training transformer architectures on patient timeline data from the MIMIC-IV database across varying model sizes and compute budgets, we identify consistent scaling patterns, including parabolic IsoFLOPs curves and power-law relationships between compute, model parameters, data size, and clinical utility. These findings demonstrate that EHR models exhibit scaling behavior analogous to LLMs, offering predictive insights into resource-efficient training strategies. Our results lay the groundwork for developing powerful EHR foundation models capable of transforming clinical prediction tasks and advancing personalized healthcare.

[Arxiv](https://arxiv.org/abs/2505.22964)