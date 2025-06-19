# eLLM：弹性内存管理框架，高效服务大语言模型

发布时间：2025年06月18日

`LLM应用

论文摘要：大型语言模型 (LLMs) 正在数据中心中得到广泛应用。为这些模型提供服务需要精细的内存管理，因为它们的内存使用涉及静态权重、动态激活和键值缓存。虽然静态权重是恒定且可预测的，但激活和 KV 缓存等动态组件在运行时会频繁变化，这对高效的内存管理提出了重大挑战。现代 LLM 服务系统通常在不同的抽象级别处理运行时内存和 KV 缓存：运行时内存管理依赖于静态张量抽象，而 KV 缓存则利用基于页表的虚拟化层，该层构建在张量抽象之上。这种虚拟化动态管理 KV 缓存以缓解内存碎片问题。然而，这种双层方法从根本上隔离了运行时内存和 KV 缓存管理，导致在动态工作负载下内存利用率低下，吞吐量可能下降近 20%。为了解决这些限制，我们提出了 eLLM，一种受操作系统经典内存气球机制启发的弹性内存管理框架。eLLM 的核心组件包括：(1) 虚拟张量抽象，它将张量的虚拟地址空间与物理 GPU 内存解耦，创建一个统一且灵活的内存池；(2) 弹性内存机制，通过运行时内存膨胀和收缩动态调整内存分配，并利用 CPU 内存作为可扩展缓冲区；(3) 轻量级调度策略，采用 SLO 意识策略来优化内存利用率，并在严格的 SLO 约束下有效平衡性能权衡。全面评估表明，eLLM 显著优于现有系统，解码吞吐量提高了 2.32 倍，并支持 128K-token 输入的 3 倍更大批次大小。` `数据中心` `云计算`

> eLLM: Elastic Memory Management Framework for Efficient LLM Serving

# 摘要

> 大型语言模型 (LLMs) 正在数据中心中得到广泛应用。为这些模型提供服务需要精细的内存管理，因为它们的内存使用涉及静态权重、动态激活和键值缓存。虽然静态权重是恒定且可预测的，但激活和 KV 缓存等动态组件在运行时会频繁变化，这对高效的内存管理提出了重大挑战。现代 LLM 服务系统通常在不同的抽象级别处理运行时内存和 KV 缓存：运行时内存管理依赖于静态张量抽象，而 KV 缓存则利用基于页表的虚拟化层，该层构建在张量抽象之上。这种虚拟化动态管理 KV 缓存以缓解内存碎片问题。然而，这种双层方法从根本上隔离了运行时内存和 KV 缓存管理，导致在动态工作负载下内存利用率低下，吞吐量可能下降近 20%。为了解决这些限制，我们提出了 eLLM，一种受操作系统经典内存气球机制启发的弹性内存管理框架。eLLM 的核心组件包括：(1) 虚拟张量抽象，它将张量的虚拟地址空间与物理 GPU 内存解耦，创建一个统一且灵活的内存池；(2) 弹性内存机制，通过运行时内存膨胀和收缩动态调整内存分配，并利用 CPU 内存作为可扩展缓冲区；(3) 轻量级调度策略，采用 SLO 意识策略来优化内存利用率，并在严格的 SLO 约束下有效平衡性能权衡。全面评估表明，eLLM 显著优于现有系统，解码吞吐量提高了 2.32 倍，并支持 128K-token 输入的 3 倍更大批次大小。

> Large Language Models are increasingly being deployed in datacenters. Serving these models requires careful memory management, as their memory usage includes static weights, dynamic activations, and key-value caches. While static weights are constant and predictable, dynamic components such as activations and KV caches change frequently during runtime, presenting significant challenges for efficient memory management. Modern LLM serving systems typically handle runtime memory and KV caches at distinct abstraction levels: runtime memory management relies on static tensor abstractions, whereas KV caches utilize a page table-based virtualization layer built on top of the tensor abstraction. This virtualization dynamically manages KV caches to mitigate memory fragmentation. However, this dual-level approach fundamentally isolates runtime memory and KV cache management, resulting in suboptimal memory utilization under dynamic workloads, which can lead to a nearly 20% drop in throughput.
  To address these limitations, we propose eLLM, an elastic memory management framework inspired by the classical memory ballooning mechanism in operating systems. The core components of eLLM include: (1) Virtual Tensor Abstraction, which decouples the virtual address space of tensors from the physical GPU memory, creating a unified and flexible memory pool; (2) an Elastic Memory Mechanism that dynamically adjusts memory allocation through runtime memory inflation and deflation, leveraging CPU memory as an extensible buffer; and (3) a Lightweight Scheduling Strategy employing SLO-aware policies to optimize memory utilization and effectively balance performance trade-offs under stringent SLO constraints. Comprehensive evaluations demonstrate that eLLM significantly outperforms state-of-the-art systems, 2.32x higher decoding throughput, and supporting 3x larger batch sizes for 128K-token inputs.

[Arxiv](https://arxiv.org/abs/2506.15155)