# Zorse：异构 GPU 集群上 LLM 训练效率的优化之道

发布时间：2025年07月14日

`LLM应用` `人工智能` `高性能计算`

> Zorse: Optimizing LLM Training Efficiency on Heterogeneous GPU Clusters

# 摘要

> 大语言模型（LLMs）的训练需要大量GPU计算资源，但GPU资源的有限性和高成本让许多组织难以构建同质化集群。通过汇集不同代的GPU构建异构集群，可以更高效地利用所有可用资源，实现更高的整体计算能力。然而，异构集群训练面临诸多挑战，包括跨GPU的负载均衡、内存使用优化以及在多样化网络互连上的高效通信训练。本文认为，要在异构集群上实现高效训练，需要：（1）以通信和内存高效的方式整合流水线并行和数据并行；（2）一种更灵活的流水线和数据并行配置，包括灵活划分GPU到非对称流水线并行阶段，以及在同一数据并行组中纳入异构GPU的能力。我们提出了Zorse，这是首个统一所有这些能力的系统，并集成了一个自动配置训练策略的规划器。我们的评估表明，在异构训练场景中，Zorse显著超越了现有最先进的系统。

> Large language models (LLMs) require vast amounts of GPU compute to train, but limited availability and high costs of GPUs make homogeneous clusters impractical for many organizations. Instead, assembling heterogeneous clusters by pooling together GPUs of different generations allows them to achieve higher aggregate compute and make use of all available GPUs. However, training on heterogeneous clusters presents several challenges, including load balancing across GPUs, optimizing memory usage to accommodate varying memory capacities, and ensuring communication-efficient training over diverse network interconnects potentially spanning multiple datacenters. In this paper, we make the case that efficient training on heterogeneous clusters requires (1) the integration of pipeline parallelism and data parallelism in a manner that is both communication- and memory-efficient, and (2) a more adaptable configuration of pipeline and data parallelism, which includes the capability to flexibly partition GPUs into asymmetric pipeline parallel stages and to incorporate heterogeneous GPUs within the same data parallelism group. We propose Zorse, the first system to unify all these capabilities while incorporating a planner that automatically configures training strategies for a given workload. Our evaluation shows that Zorse significantly outperforms state-of-the-art systems in heterogeneous training scenarios.

[Arxiv](https://arxiv.org/abs/2507.10392)