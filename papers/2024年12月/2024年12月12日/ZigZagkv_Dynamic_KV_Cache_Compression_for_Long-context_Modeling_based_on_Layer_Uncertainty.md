# ZigZagkv：基于层不确定性实现长上下文建模的动态 KV 缓存压缩

发布时间：2024年12月12日

`LLM应用` `计算机` `人工智能`

> ZigZagkv: Dynamic KV Cache Compression for Long-context Modeling based on Layer Uncertainty

# 摘要

> 大型语言模型（LLMs）已成研究热点。为加速 LLMs 的推理，在内存中存储计算缓存已成标准技术。然而，随着推理长度增加，不断增大的 KV 缓存可能导致内存不足。现有诸多方法通过 KV 缓存压缩来解决这一问题，主要是在所有层保留关键令牌以减少信息损失，且大多为每层分配统一的预算大小用于保留。但我们发现，从注意力和隐藏状态输出的角度来看，不同层和模型保留关键信息所需的最小预算大小各异。基于此，本文提出一种简单有效的 KV 缓存压缩方法，利用层不确定性为每层分配预算大小。实验结果表明，与全 KV 推理相比，该方法能将 KV 缓存的内存使用量降至仅约 20％，同时实现近乎无损的性能。

> Large Language models (LLMs) have become a research hotspot. To accelerate the inference of LLMs, storing computed caches in memory has become the standard technique. However, as the inference length increases, growing KV caches might lead to out-of-memory issues. Many existing methods address this issue through KV cache compression, primarily by preserving key tokens throughout all layers to reduce information loss. Most of them allocate a uniform budget size for each layer to retain. However, we observe that the minimum budget sizes needed to retain essential information vary across layers and models based on the perspectives of attention and hidden state output. Building on this observation, this paper proposes a simple yet effective KV cache compression method that leverages layer uncertainty to allocate budget size for each layer. Experimental results show that the proposed method can reduce memory usage of the KV caches to only $\sim$20\% when compared to Full KV inference while achieving nearly lossless performance.

[Arxiv](https://arxiv.org/abs/2412.09036)