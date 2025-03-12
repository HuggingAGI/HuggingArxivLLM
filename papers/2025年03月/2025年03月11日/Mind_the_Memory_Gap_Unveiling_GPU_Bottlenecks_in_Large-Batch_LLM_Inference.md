# # 关注内存差距：揭秘大批次LLM推理中的GPU性能瓶颈

发布时间：2025年03月11日

`LLM应用

理由：这篇论文探讨了如何优化大语言模型的推理过程，特别是通过批处理和内存管理来提高资源利用率。它属于应用层面的优化策略，而非理论或特定技术（如RAG）的研究。` `云计算` `高性能计算`

> Mind the Memory Gap: Unveiling GPU Bottlenecks in Large-Batch LLM Inference

# 摘要

> 大语言模型在各种任务中广泛应用，但其自回归生成特性在推理过程中常导致资源利用率低下。批处理虽能提高吞吐量，但性能提升会在某个规模后趋于平缓，尤其是小模型，现有文献通常将其归因于计算密集型模式的转变。通过深入的GPU级别分析，我们发现大规模批处理推理仍受内存限制，DRAM带宽饱和成为主要瓶颈，导致GPU计算能力未被充分利用。为此，我们提出了一种批处理配置顾问（BCA），通过优化内存分配降低GPU内存需求，对吞吐量影响极小。释放的内存和GPU计算能力可用于并行工作负载。我们采用模型复制提升服务吞吐量和GPU利用率。我们的研究挑战了关于大语言模型推理的传统假设，为改善资源利用率提供了新见解和实用策略，特别是针对小规模语言模型。

> Large language models have been widely adopted across different tasks, but their auto-regressive generation nature often leads to inefficient resource utilization during inference. While batching is commonly used to increase throughput, performance gains plateau beyond a certain batch size, especially with smaller models, a phenomenon that existing literature typically explains as a shift to the compute-bound regime. In this paper, through an in-depth GPU-level analysis, we reveal that large-batch inference remains memory-bound, with most GPU compute capabilities underutilized due to DRAM bandwidth saturation as the primary bottleneck. To address this, we propose a Batching Configuration Advisor (BCA) that optimizes memory allocation, reducing GPU memory requirements with minimal impact on throughput. The freed memory and underutilized GPU compute capabilities can then be leveraged by concurrent workloads. Specifically, we use model replication to improve serving throughput and GPU utilization. Our findings challenge conventional assumptions about LLM inference, offering new insights and practical strategies for improving resource utilization, particularly for smaller language models.

[Arxiv](https://arxiv.org/abs/2503.08311)