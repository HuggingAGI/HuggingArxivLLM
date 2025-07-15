# 百亿规模ANNS中的存储-计算瓶颈突破：GPU驱动的异步I/O框架

发布时间：2025年07月14日

`其他

理由：这篇论文主要讨论了近似最近邻搜索（ANNS）的优化，特别是针对基于磁盘的系统的性能提升。虽然它提到了RAG技术，但其核心贡献在于硬件和算法优化，而非RAG本身或LLM的应用或理论。因此，归类为“其他”。` `信息检索` `推荐系统`

> Breaking the Storage-Compute Bottleneck in Billion-Scale ANNS: A GPU-Driven Asynchronous I/O Framework

# 摘要

> 随着信息检索、推荐系统以及检索增强生成（RAG）技术的进步，近似最近邻搜索（ANNS）因其卓越的性能和准确性而获得了广泛应用。尽管出现了多种基于磁盘的ANNS系统来处理指数级增长的向量数据集，但它们由于以下两个内在限制而性能不佳：1）无法将SSD访问与距离计算过程重叠；2）由于次优的I/O栈导致的延长I/O延迟。

为了解决这些挑战，我们提出了FlashANNS，这是一个通过I/O计算重叠实现的GPU加速的基于图的ANNS系统。我们的核心见解在于通过三项关键创新同步协调I/O和计算：

1）依赖松弛的异步流水线：FlashANNS解耦I/O-计算依赖，使GPU距离计算与SSD数据传输完全重叠。

2）warp级并发SSD访问：FlashANNS实现了一个带有warp级并发控制的无锁I/O栈，以减少延迟引发的时间开销。

3）计算-I/O平衡的图度选择：FlashANNS通过轻量级计算到I/O比率采样选择图度，确保在不同I/O带宽配置下计算负载与存储访问延迟的最优平衡。

我们实现了FlashANNS，并将其与最先进的基于磁盘的ANNS系统（SPANN、DiskANN）以及一个GPU加速的基于磁盘的ANNS系统（FusionANNS）进行了比较。实验结果表明，在$\geq$95\%的@10召回率下，与现有的SOTA方法相比，我们的方法在单SSD配置下实现了2.3-5.9$	imes$的吞吐量提升，并且在多SSD配置下进一步实现了2.7-12.2$	imes$的吞吐量改进。

> With the advancement of information retrieval, recommendation systems, and Retrieval-Augmented Generation (RAG), Approximate Nearest Neighbor Search (ANNS) gains widespread applications due to its higher performance and accuracy. While several disk-based ANNS systems have emerged to handle exponentially growing vector datasets, they suffer from suboptimal performance due to two inherent limitations: 1) failing to overlap SSD accesses with distance computation processes and 2) extended I/O latency caused by suboptimal I/O Stack. To address these challenges, we present FlashANNS, a GPU-accelerated out-of-core graph-based ANNS system through I/O-compute overlapping. Our core insight lies in the synchronized orchestration of I/O and computation through three key innovations: 1) Dependency-Relaxed asynchronous pipeline: FlashANNS decouples I/O-computation dependencies to fully overlap between GPU distance calculations and SSD data transfers. 2) Warp-Level concurrent SSD access: FlashANNS implements a lock-free I/O stack with warp-level concurrency control, to reduce the latency-induced time overhead. 3) Computation-I/O balanced graph degree Selection: FlashANNS selects graph degrees via lightweight compute-to-I/O ratio sampling, ensuring optimal balance between computational load and storage access latency across different I/O bandwidth configurations. We implement FlashANNS and compare it with state-of-the-art out-of-core ANNS systems (SPANN, DiskANN) and a GPU-accelerated out-of-core ANNS system (FusionANNS). Experimental results demonstrate that at $\geq$95\% recall@10 accuracy, our method achieves 2.3-5.9$\times$ higher throughput compared to existing SOTA methods with a single SSD, and further attains 2.7-12.2$\times$ throughput improvement in multi-SSD configurations.

[Arxiv](https://arxiv.org/abs/2507.10070)