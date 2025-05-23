# NQKV：基于正态分布特性的 KV 缓存量化方案

发布时间：2025年05月22日

`LLM应用` `计算机科学`

> NQKV: A KV Cache Quantization Scheme Based on Normal Distribution Characteristics

# 摘要

> 大型语言模型（LLMs）在各类任务中表现非凡。然而，为了提升性能，LLMs 常常需要更大的批次规模或更长的上下文长度，这给 KV 缓存带来了巨大的内存压力，成为 LLM 部署的主要瓶颈。为了解决这一问题，量化提供了一种直接有效的解决方案。目前，激活值的量化仅限于 8 位，而更低位的量化往往会导致精度大幅下降。为了进一步节省空间，我们深入分析了 KV 缓存的元素分布，并设计了 NQKV 算法。由于 KV 缓存中每个块内的元素呈正态分布，NQKV 采用了块内分位数量化方法，以实现信息论意义上的最优量化误差。在几乎不降低模型输出质量的情况下，NQKV 让 OPT 模型能够支持 2 倍的批次规模或 4 倍的上下文长度进行推理，与未使用 KV 缓存相比，吞吐量提升了 9.3 倍。

> Large Language Models (LLMs) have demonstrated remarkable proficiency across a wide range of tasks. However, LLMs often require larger batch sizes to enhance throughput or longer context lengths to meet task demands, which significantly increases the memory resource consumption of the Key-Value (KV) cache during inference, becoming a major bottleneck in LLM deployment. To address this issue, quantization is a common and straightforward approach. Currently, quantization methods for activations are limited to 8-bit, and quantization to even lower bits can lead to substantial accuracy drops. To further save space by quantizing the KV cache to even lower bits, we analyzed the element distribution of the KV cache and designed the NQKV algorithm. Since the elements within each block of the KV cache follow a normal distribution, NQKV employs per-block quantile quantization to achieve information-theoretically optimal quantization error. Without significantly compromising model output quality, NQKV enables the OPT model to perform inference with an 2x larger batch size or a 4x longer context length, and it improves throughput by 9.3x compared to when the KV cache is not used.

[Arxiv](https://arxiv.org/abs/2505.16210)