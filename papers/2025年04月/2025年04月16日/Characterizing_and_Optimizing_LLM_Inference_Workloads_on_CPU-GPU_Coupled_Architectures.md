# # 表征与优化LLM推理负载在CPU-GPU耦合架构中的表现

发布时间：2025年04月16日

`其他` `计算机体系结构` `人工智能`

> Characterizing and Optimizing LLM Inference Workloads on CPU-GPU Coupled Architectures

# 摘要

> 大型语言模型（LLM）的推理工作负载正日益主导数据中心的成本和资源利用率，理解其在 CPU-GPU 耦合架构上的特性对优化至关重要。本文深入分析了 LLM 推理行为在松耦合（PCIe A100/H100）和紧耦合（GH200）系统上的表现。通过细粒度的操作符到内核追踪分析，结合我们的新型 profiler SKIP 和 Total Kernel Launch and Queuing Time (TKLQT) 指标，我们揭示了性能动态。结果显示，紧耦合 GH200 在大批次规模下表现显著优于松耦合系统，实现了 Llama 3.2-1B 1.9x-2.7x 的更快预填延迟。然而，GH200 在比松耦合系统大 4 倍的批次规模之前仍受 CPU 限制。在这一扩展的 CPU 限制区域，Grace CPU 的性能特性是导致 GH200 在小批次规模下推理延迟较高的关键因素。TKLQT 准确识别了这一 CPU/GPU 限制的转换点。通过内核融合减少 GH200 低批次延迟瓶颈的潜力巨大。这种内核级别的详细表征为优化 CPU-GPU 耦合策略提供了关键见解。这项工作是初步尝试，我们计划探索其他需要不同 CPU-GPU 异构架构程度的重大 AI/DL 工作负载。

> Large language model (LLM)-based inference workloads increasingly dominate data center costs and resource utilization. Therefore, understanding the inference workload characteristics on evolving CPU-GPU coupled architectures is crucial for optimization. This paper presents an in-depth analysis of LLM inference behavior on loosely-coupled (PCIe A100/H100) and closely-coupled (GH200) systems. We analyze performance dynamics using fine-grained operator-to-kernel trace analysis, facilitated by our novel profiler SKIP and metrics like Total Kernel Launch and Queuing Time (TKLQT). Results show that closely-coupled (CC) GH200 significantly outperforms loosely-coupled (LC) systems at large batch sizes, achieving 1.9x-2.7x faster prefill latency for Llama 3.2-1B. However, our analysis also reveals that GH200 remains CPU-bound up to 4x larger batch sizes than LC systems. In this extended CPU-bound region, we identify the performance characteristics of the Grace CPU as a key factor contributing to higher inference latency at low batch sizes on GH200. We demonstrate that TKLQT accurately identifies this CPU/GPU-bound transition point. Based on this analysis, we further show that kernel fusion offers significant potential to mitigate GH200's low-batch latency bottleneck by reducing kernel launch overhead. This detailed kernel-level characterization provides critical insights for optimizing diverse CPU-GPU coupling strategies. This work is an initial effort, and we plan to explore other major AI/DL workloads that demand different degrees of CPU-GPU heterogeneous architectures.

[Arxiv](https://arxiv.org/abs/2504.11750)