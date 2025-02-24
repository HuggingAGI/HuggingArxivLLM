# 从16位到1位：面向内存高效的多模态大语言模型的视觉KV缓存量化

发布时间：2025年02月15日

`其他` `多模态模型` `计算效率`

> From 16-Bit to 1-Bit: Visual KV Cache Quantization for Memory-Efficient Multimodal Large Language Models

# 摘要

> 多模态大型语言模型 (MLLMs) 在各类应用中表现优异，但部署时的计算开销仍是主要挑战。尽管键值 (KV) 缓存通过内存换计算提升了推理效率，但存储大量 KV 缓存导致的内存占用增加却降低了吞吐量，并限制了在 GPU 内存有限设备上的长期运行。现有方法主要通过丢弃不重要的 token 来减小 KV 缓存规模，以缓解内存限制，但可能造成信息丢失。我们提出了一种简单而有效的视觉量化策略，在保留所有视觉 token 的同时大幅降低内存消耗。为实现极端量化比率（1-bit 量化），我们提出了分组特定量化和基于分位数的量化方法，这些方法受到 KV 缓存固有模式的启发。我们的方法具有即插即用的特点，可无缝集成到各类 MLLMs 中，在不修改架构的情况下提升内存效率。大量实验表明，我们的方法在保持计算效率的同时有效降低了内存开销，并保留了多模态性能。

> Multimodal Large Language Models (MLLMs) have achieved remarkable success across various applications, yet their computational overhead during deployment remains a critical challenge. While Key-Value (KV) caching improves inference efficiency by trading memory for computation, the growing memory footprint from storing extensive KV caches reduces throughput and limits long-term execution on devices with constrained GPU memory. Existing approaches primarily focus on dropping unimportant tokens to reduce the KV cache size, mitigating memory constraints at the cost of potential information loss. In contrast, we propose a simple yet effective visual quantization strategy that preserves all visual tokens while significantly reducing memory consumption. To achieve an extreme quantization ratio, i.e., 1-bit quantization, we propose group-specific quantization and quantile-based quantization approaches, motivated by the inherent patterns of the KV cache. Our method is plug-and-play, enabling seamless integration into various MLLMs to improve memory efficiency without architectural modifications. Extensive experiments demonstrate that our approach effectively reduces memory overhead while maintaining computational efficiency and preserving multimodal performance.

[Arxiv](https://arxiv.org/abs/2502.14882)