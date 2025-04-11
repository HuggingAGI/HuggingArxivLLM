# 基于聚类驱动的专家剪枝方法，用于混合专家型大型语言模型

发布时间：2025年04月10日

`LLM理论` `模型压缩`

> Cluster-Driven Expert Pruning for Mixture-of-Experts Large Language Models

# 摘要

> 专家混合（MoE）架构作为一种有前景的范式，通过任务特定专家的稀疏激活，为大型语言模型（LLMs）的扩展提供了有效途径。尽管在推理阶段具备计算效率优势，但MoE模型（例如GPT-4）庞大的整体参数规模为实际部署带来了关键挑战。当前的剪枝方法往往无法解决MoE系统中两个固有特性：1）层内专家同质性，即同一MoE层内的专家存在功能性冗余；2）层间相似性模式，即深层中专家的同质性逐渐增加。为应对这些问题，我们提出了基于聚类的专家剪枝方法（C-Prune），这是一种针对MoE LLMs自适应任务特定压缩的新型两阶段框架。C-Prune通过分层专家聚类进行操作，首先在每个MoE层内利用参数相似性指标将功能相似的专家分组，然后通过全局聚类剪枝，采用统一的重要性评分机制消除跨层的冗余聚类，从而考虑跨层同质性。我们通过在多个MoE模型和基准上的广泛实验验证了C-Prune。结果表明，C-Prune能够有效减小模型规模，同时超越现有的MoE剪枝方法。

> Mixture-of-Experts (MoE) architectures have emerged as a promising paradigm for scaling large language models (LLMs) with sparse activation of task-specific experts. Despite their computational efficiency during inference, the massive overall parameter footprint of MoE models (e.g., GPT-4) introduces critical challenges for practical deployment. Current pruning approaches often fail to address two inherent characteristics of MoE systems: 1).intra-layer expert homogeneity where experts within the same MoE layer exhibit functional redundancy, and 2). inter-layer similarity patterns where deeper layers tend to contain progressively more homogeneous experts. To tackle these issues, we propose Cluster-driven Expert Pruning (C-Prune), a novel two-stage framework for adaptive task-specific compression of MoE LLMs. C-Prune operates through layer-wise expert clustering, which groups functionally similar experts within each MoE layer using parameter similarity metrics, followed by global cluster pruning, which eliminates redundant clusters across all layers through a unified importance scoring mechanism that accounts for cross-layer homogeneity. We validate C-Prune through extensive experiments on multiple MoE models and benchmarks. The results demonstrate that C-Prune effectively reduces model size while outperforming existing MoE pruning methods.

[Arxiv](https://arxiv.org/abs/2504.07807)