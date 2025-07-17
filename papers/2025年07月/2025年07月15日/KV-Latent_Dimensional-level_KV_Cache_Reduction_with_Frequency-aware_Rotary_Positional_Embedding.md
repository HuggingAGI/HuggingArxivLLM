# KV-Latent：维度级KV缓存缩减的频率感知旋转位置嵌入方法

发布时间：2025年07月15日

`LLM理论` `人工智能`

> KV-Latent: Dimensional-level KV Cache Reduction with Frequency-aware Rotary Positional Embedding

# 摘要

> 基于 Transformer 解码器的大语言模型 (LLMs) 已成为对话生成 AI 的首选方案。尽管解码器架构整体上更为优越，但在推理过程中逐渐增加的键值（KV）缓存已成为主要效率瓶颈，其问题体现在内存占用和数据传输带宽限制两个方面。为了解决这些挑战，我们提出了一种名为 KV-Latent 的新范式。通过将键值向量维度降采样到潜在空间中，我们能够显著减少 KV 缓存占用，并提升推理速度，仅需少量额外训练，训练量不到预训练的 1%。此外，我们通过修改频率采样机制，增强了旋转位置嵌入在低维向量上的稳定性，避免了高频引入的噪声，同时保留了位置衰减特性。我们的实验涵盖了带有分组查询注意力机制和无此机制的模型，均取得了令人满意的成果。最后，我们进行了对比实验，研究了分别降低键和值组件对模型性能的影响。我们的方法为构建更高效的语言模型系统提供了可能性，并在 KV 缓存节省和高效 LLM 方面开辟了新的前景。我们的代码可在 https://github.com/ShiLuohe/KV-Latent 获取。

> Large language models (LLMs) based on Transformer Decoders have become the preferred choice for conversational generative AI. Despite the overall superiority of the Decoder architecture, the gradually increasing Key-Value (KV) cache during inference has emerged as a primary efficiency bottleneck, both in aspects of memory consumption and data transfer bandwidth limitations. To address these challenges, we propose a paradigm called KV-Latent. By down-sampling the Key-Value vector dimensions into a latent space, we can significantly reduce the KV Cache footprint and improve inference speed, only with a small amount of extra training, less than 1\% of pre-training takes. Besides, we enhanced the stability of Rotary Positional Embedding applied on lower-dimensional vectors by modifying its frequency sampling mechanism, avoiding noise introduced by higher frequencies while retaining position attenuation. Our experiments, including both models with Grouped Query Attention and those without, have yielded satisfactory results. Finally, we conducted comparative experiments to study the impact of separately reducing Key and Value components on model's performance. Our approach allows for the construction of more efficient language model systems, and opens the new possibility on KV Cache saving and efficient LLMs. Our code is available at https://github.com/ShiLuohe/KV-Latent.

[Arxiv](https://arxiv.org/abs/2507.11273)