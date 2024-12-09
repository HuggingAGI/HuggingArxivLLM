# Ltri-LLM：采用免训练动态三角形注意力模式实现 LLMs 的流长上下文推理

发布时间：2024年12月05日

`LLM理论` `人工智能`

> Ltri-LLM: Streaming Long Context Inference for LLMs with Training-Free Dynamic Triangular Attention Pattern

# 摘要

> 当前大型语言模型（LLMs）里注意力机制的二次计算复杂度，让长上下文的推理成本高得吓人。为解决这一难题，各种方法都致力于保留上下文的关键部分，通过键值（KV）压缩或稀疏注意力（SA）来尽可能接近全注意力（FA），从而能以流的方式处理近乎无限长的文本。但这些方法很难达到跟FA一样的性能水平，在检索任务中尤其如此。在本文中，我们对注意力头模式的分析显示，LLMs的注意力分布具有很强的局部相关性，自然体现了输入上下文的分块机制。我们提出了Ltri-LLM框架，它把KVs分成跨度，存到离线索引里，然后为各种查询把相关的KVs检索到内存中。在热门的长文本基准测试中的实验结果表明，Ltri-LLM能达到接近FA的性能，同时还能保持高效的基于流的推理。

> The quadratic computational complexity of the attention mechanism in current Large Language Models (LLMs) renders inference with long contexts prohibitively expensive. To address this challenge, various approaches aim to retain critical portions of the context to optimally approximate Full Attention (FA) through Key-Value (KV) compression or Sparse Attention (SA), enabling the processing of virtually unlimited text lengths in a streaming manner. However, these methods struggle to achieve performance levels comparable to FA, particularly in retrieval tasks. In this paper, our analysis of attention head patterns reveals that LLMs' attention distributions show strong local correlations, naturally reflecting a chunking mechanism for input context. We propose Ltri-LLM framework, which divides KVs into spans, stores them in an offline index, and retrieves the relevant KVs into memory for various queries. Experimental results on popular long text benchmarks show that Ltri-LLM can achieve performance close to FA while maintaining efficient, streaming-based inference.

[Arxiv](https://arxiv.org/abs/2412.04757)