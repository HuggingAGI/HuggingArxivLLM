# 即插即用的1.x位KV缓存量化技术，专为视频大型语言模型设计

发布时间：2025年03月20日

`LLM应用` `视频处理` `计算机视觉`

> Plug-and-Play 1.x-Bit KV Cache Quantization for Video Large Language Models

# 摘要

> 视频大型语言模型（VideoLLMs）在处理长视频输入并实现复杂推理与分析方面表现优异。然而，由于视频帧中的数千个视觉令牌，KV缓存会显著增加内存需求，成为推理速度和内存使用的关键瓶颈。KV缓存量化是解决这一问题的常用方法。本文发现，VideoLLMs的2-bit KV量化几乎不会损害模型性能，但 KV缓存量化在更低位数的极限尚未被探索。为填补这一空白，我们引入了 VidKV，这是一种即插即用的 KV缓存量化方法，可将 KV缓存压缩至低于2-bit。具体而言，（1）对于键，我们提出了一种通道维度的混合精度量化策略，其中对异常通道进行2-bit量化，对正常通道则结合1-bit量化与FFT进行处理；（2）对于值，我们实现了1.58-bit量化，同时选择性过滤语义突出的视觉令牌以实现精准保存，从而在精度与模型性能之间取得更好的平衡。重要的是，我们的研究表明，VideoLLMs的价值缓存应以通道为单位进行量化，而非如先前针对LLMs的KV缓存量化工作中所提出的逐令牌量化。实证结果表明，VidKV在六项基准测试中使用LLaVA-OV-7B和Qwen2.5-VL-7B进行的广泛实验显示，与FP16版本相比，VidKV能够将 KV缓存有效压缩至1.5-bit和1.58-bit精度，几乎无性能下降。


> Video large language models (VideoLLMs) have demonstrated the capability to process longer video inputs and enable complex reasoning and analysis. However, due to the thousands of visual tokens from the video frames, key-value (KV) cache can significantly increase memory requirements, becoming a bottleneck for inference speed and memory usage. KV cache quantization is a widely used approach to address this problem. In this paper, we find that 2-bit KV quantization of VideoLLMs can hardly hurt the model performance, while the limit of KV cache quantization in even lower bits has not been investigated. To bridge this gap, we introduce VidKV, a plug-and-play KV cache quantization method to compress the KV cache to lower than 2 bits. Specifically, (1) for key, we propose a mixed-precision quantization strategy in the channel dimension, where we perform 2-bit quantization for anomalous channels and 1-bit quantization combined with FFT for normal channels; (2) for value, we implement 1.58-bit quantization while selectively filtering semantically salient visual tokens for targeted preservation, for a better trade-off between precision and model performance. Importantly, our findings suggest that the value cache of VideoLLMs should be quantized in a per-channel fashion instead of the per-token fashion proposed by prior KV cache quantization works for LLMs. Empirically, extensive results with LLaVA-OV-7B and Qwen2.5-VL-7B on six benchmarks show that VidKV effectively compresses the KV cache to 1.5-bit and 1.58-bit precision with almost no performance drop compared to the FP16 counterparts.

[Arxiv](https://arxiv.org/abs/2503.16257)