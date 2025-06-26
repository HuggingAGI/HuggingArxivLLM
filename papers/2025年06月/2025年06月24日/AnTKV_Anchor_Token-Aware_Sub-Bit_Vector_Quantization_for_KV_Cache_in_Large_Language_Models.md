# AnTKV: 大语言模型键值缓存的锚定标记感知子比特向量量化方法

发布时间：2025年06月24日

`LLM应用` `机器学习`

> AnTKV: Anchor Token-Aware Sub-Bit Vector Quantization for KV Cache in Large Language Models

# 摘要

> 量化作为一种有效且轻量级的解决方案，已逐渐成为减少大型语言模型（LLMs）中键值缓存（KV cache）内存占用的重要方法。不过，如何将超低比特键值缓存量化对性能的负面影响降到最低，仍然是一个巨大的挑战。我们发现，不同令牌的键值缓存量化对注意力输出质量的影响各不相同。为了系统性地研究这一现象，我们在注意力机制中进行了前向误差传播分析，并提出了一个名为Anchor Score（AnS）的指标，用于量化每个令牌键值缓存对量化引起的误差的敏感度。我们的分析揭示了不同令牌在AnS上的显著差异，这表明保留一小部分高AnS令牌的全精度（FP16）可以极大缓解激进量化场景下的精度损失。基于这一发现，我们引入了AnTKV，一个基于Anchor Token感知向量量化的新型框架，用于压缩键值缓存。此外，为了支持高效部署，我们设计并开发了一个与FlashAttention完全兼容的triton内核，从而实现了快速在线Anchor Token选择。AnTKV使LLaMA-3-8B能够在单个80GB A100 GPU上处理长达840K令牌的上下文长度，同时与FP16基线相比，解码吞吐量提高了3.5倍。我们的实验结果表明，在4-bit设置下，AnTKV可以与KIVI、SKVQ、KVQuant和CQ等先前工作相媲美或超越它们。更重要的是，在Mistral-7B上，AnTKV在超低比特量化下实现了显著更低的困惑度，1-bit时为6.32，0.375-bit时为8.87，而FP16基线为4.73。

> Quantization has emerged as an effective and lightweight solution to reduce the memory footprint of the KV cache in Large Language Models (LLMs). Nevertheless, minimizing the performance degradation caused by ultra-low-bit KV cache quantization remains a significant challenge. We observe that quantizing the KV cache of different tokens has varying impacts on the quality of attention outputs. To systematically investigate this phenomenon, we perform forward error propagation analysis on attention and propose the Anchor Score (AnS) that quantifies the sensitivity of each token's KV cache to quantization-induced error. Our analysis reveals significant disparities in AnS across tokens, suggesting that preserving a small subset with full precision (FP16) of high-AnS tokens can greatly mitigate accuracy loss in aggressive quantization scenarios. Based on this insight, we introduce AnTKV, a novel framework that leverages Anchor Token-aware Vector Quantization to compress the KV cache. Furthermore, to support efficient deployment, we design and develop a triton kernel that is fully compatible with FlashAttention, enabling fast online Anchor Token selection. AnTKV enables LLaMA-3-8B to handle context lengths up to 840K tokens on a single 80GB A100 GPU, while achieving up to 3.5x higher decoding throughput compared to the FP16 baseline. Our experiment results demonstrate that AnTKV matches or outperforms prior works such as KIVI, SKVQ, KVQuant, and CQ under 4-bit settings. More importantly, AnTKV achieves significantly lower perplexity under ultra-low-bit quantization on Mistral-7B, with only 6.32 at 1-bit and 8.87 at 0.375-bit, compared to the FP16 baseline of 4.73.

[Arxiv](https://arxiv.org/abs/2506.19505)