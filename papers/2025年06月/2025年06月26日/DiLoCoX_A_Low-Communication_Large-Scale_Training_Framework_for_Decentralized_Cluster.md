# DiLoCoX：面向去中心化集群的低通信开销大规模训练框架

发布时间：2025年06月26日

`其他` `人工智能` `分布式系统`

> DiLoCoX: A Low-Communication Large-Scale Training Framework for Decentralized Cluster

# 摘要

> 大型语言模型 (LLMs) 的分布式训练需要高度依赖快速互联的集中式集群，而我们是否能在慢速网络环境下释放去中心化集群的潜力？在本文中，我们提出了一种低通信开销的大规模去中心化集群训练框架 DiLoCoX。该框架创新性地将流水线并行、双优化器策略、通信与本地训练的一步延迟重叠以及自适应梯度压缩方案相结合。通过理论分析，我们证明了这一组合在提升模型预训练效率方面的优势。实证结果显示，DiLoCoX能够在1Gbps网络环境下预训练1070亿参数规模的基础模型，与传统的AllReduce方法相比，实现了357倍的加速，同时对模型收敛性的负面影响微乎其微。这一突破标志着去中心化训练首次成功应用于超过1000亿参数规模的模型训练。

> The distributed training of foundation models, particularly large language models (LLMs), demands a high level of communication. Consequently, it is highly dependent on a centralized cluster with fast and reliable interconnects. Can we conduct training on slow networks and thereby unleash the power of decentralized clusters when dealing with models exceeding 100 billion parameters? In this paper, we propose DiLoCoX, a low-communication large-scale decentralized cluster training framework. It combines Pipeline Parallelism with Dual Optimizer Policy, One-Step-Delay Overlap of Communication and Local Training, and an Adaptive Gradient Compression Scheme. This combination significantly improves the scale of parameters and the speed of model pre-training. We justify the benefits of one-step-delay overlap of communication and local training, as well as the adaptive gradient compression scheme, through a theoretical analysis of convergence. Empirically, we demonstrate that DiLoCoX is capable of pre-training a 107B foundation model over a 1Gbps network. Compared to vanilla AllReduce, DiLoCoX can achieve a 357x speedup in distributed training while maintaining negligible degradation in model convergence. To the best of our knowledge, this is the first decentralized training framework successfully applied to models with over 100 billion parameters.

[Arxiv](https://arxiv.org/abs/2506.21263)