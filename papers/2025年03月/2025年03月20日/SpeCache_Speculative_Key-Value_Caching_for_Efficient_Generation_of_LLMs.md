# SpeCache：基于推测性键值缓存的LLM高效生成方法

发布时间：2025年03月20日

`LLM应用` `计算机体系结构`

> SpeCache: Speculative Key-Value Caching for Efficient Generation of LLMs

# 摘要

> 基于Transformer的大型语言模型（LLMs）在长文本任务中表现优异，但随着序列长度增加，有限的GPU显存（VRAM）难以应对线性增长的KV缓存需求，成为应用瓶颈。现有KV缓存压缩方法通过缓存驱逐、合并或量化来减小缓存大小，但压缩会导致不可逆的信息遗忘，影响解码准确性。本文提出SpeCache，利用大容量且易扩展的CPU内存卸载完整KV缓存，并基于VRAM中低精度KV缓存副本的重要性评分，在每步解码过程中动态回取KV对。为避免CPU-GPU通信引起的推理延迟，SpeCache推测下一个token可能关注的KV对，允许我们在下一步解码前预取它们，实现预取与计算并行化。在LongBench和Needle-in-a-Haystack基准测试中，实验验证SpeCache在不重新训练的情况下有效减少VRAM使用，同时避免长序列信息遗忘，即使KV缓存压缩比高达10倍。


> Transformer-based large language models (LLMs) have already achieved remarkable results on long-text tasks, but the limited GPU memory (VRAM) resources struggle to accommodate the linearly growing demand for key-value (KV) cache as the sequence length increases, which has become a bottleneck for the application of LLMs on long sequences. Existing KV cache compression methods include eviction, merging, or quantization of the KV cache to reduce its size. However, compression results in irreversible information forgetting, potentially affecting the accuracy of subsequent decoding. In this paper, we propose SpeCache, which takes full advantage of the large and easily expandable CPU memory to offload the complete KV cache, and dynamically fetches KV pairs back in each decoding step based on their importance measured by low-bit KV cache copy in VRAM. To avoid inference latency caused by CPU-GPU communication, SpeCache speculatively predicts the KV pairs that the next token might attend to, allowing us to prefetch them before the next decoding step which enables parallelization of prefetching and computation. Experiments on LongBench and Needle-in-a-Haystack benchmarks verify that SpeCache effectively reduces VRAM usage while avoiding information forgetting for long sequences without re-training, even with a 10x high KV cache compression ratio.

[Arxiv](https://arxiv.org/abs/2503.16163)