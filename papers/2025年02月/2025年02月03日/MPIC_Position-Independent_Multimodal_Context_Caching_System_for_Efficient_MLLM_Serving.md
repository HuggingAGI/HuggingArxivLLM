# MPIC: 位置无关的多模态上下文缓存系统，助力高效多模态大语言模型服务

发布时间：2025年02月03日

`LLM应用

理由：这篇论文主要讨论的是如何通过改进缓存技术来加速多模态大型语言模型（MLLM）的推理过程。具体来说，它提出了一种位置无关的缓存方法（MPIC），以优化多模态信息管理，从而提高系统的响应时间和效率。虽然涉及系统级和算法级的优化，但其核心目标是为了提升LLM在实际应用中的性能，因此应归类为LLM应用。` `计算机系统` `缓存技术`

> MPIC: Position-Independent Multimodal Context Caching System for Efficient MLLM Serving

# 摘要

> 当前主流服务平台采用上下文缓存技术来加速多模态大型语言模型（MLLM）的推理。然而，这种方法仅重用了初始提示序列的键值（KV）缓存，即使前缀稍有不同，也会导致完整的KV缓存重新计算。这在交错文本和图像以及多模态检索增强生成的场景下尤为低效。本文提出了一种位置无关的缓存方法，作为多模态信息管理的更优解决方案。我们设计并实现了名为MPIC的缓存系统，以应对系统级和算法级的挑战。MPIC在接收多模态数据时将KV缓存存储在本地或远程磁盘上，并在推理过程中并行计算和加载KV缓存。为了减少精度损失，我们在系统中集成了重用和重新计算机制。实验结果显示，与现有上下文缓存系统相比，MPIC可将响应时间减少多达54%，同时保持几乎无精度损失。

> The context caching technique is employed to accelerate the Multimodal Large Language Model (MLLM) inference by prevailing serving platforms currently. However, this approach merely reuses the Key-Value (KV) cache of the initial sequence of prompt, resulting in full KV cache recomputation even if the prefix differs slightly. This becomes particularly inefficient in the context of interleaved text and images, as well as multimodal retrieval-augmented generation. This paper proposes position-independent caching as a more effective approach for multimodal information management. We have designed and implemented a caching system, named MPIC, to address both system-level and algorithm-level challenges. MPIC stores the KV cache on local or remote disks when receiving multimodal data, and calculates and loads the KV cache in parallel during inference. To mitigate accuracy degradation, we have incorporated integrated reuse and recompute mechanisms within the system. The experimental results demonstrate that MPIC can achieve up to 54% reduction in response time compared to existing context caching systems, while maintaining negligible or no accuracy loss.

[Arxiv](https://arxiv.org/abs/2502.01960)