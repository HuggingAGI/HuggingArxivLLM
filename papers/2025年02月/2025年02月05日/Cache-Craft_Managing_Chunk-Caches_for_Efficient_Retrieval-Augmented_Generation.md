# Cache-Craft：高效检索增强生成的块缓存管理方法

发布时间：2025年02月05日

`RAG` `系统优化`

> Cache-Craft: Managing Chunk-Caches for Efficient Retrieval-Augmented Generation

# 摘要

> 检索增强生成（RAG）常与大型语言模型（LLMs）结合使用，以融合领域知识或用户个性化信息。在RAG中，针对用户查询，检索器从知识库提取相关文本片段，并将其作为输入提示的一部分传递给LLM。通常，文本片段会在多个用户查询中被重复检索。然而，当前LLMs的注意力层在处理每个问题时都会对输入片段重复计算键值（KVs），因为现有方法无法在任意上下文中重用KV缓存。简单复用会导致输出质量下降，进而造成GPU上的冗余计算和延迟增加。为此，我们提出了Cache-Craft系统，用于管理和重用RAG系统中文本片段对应的预计算键值（块缓存）。Cache-Craft通过识别可重用缓存、优化少量重新计算以保持输出质量，并高效存储和淘汰硬件中的块缓存，从而最大化重用并隐藏开销。实验结果表明，Cache-Craft相比最先进的前缀缓存，冗余计算减少51%，相比完全重新计算减少75%。在真实工作负载中，Cache-Craft持续批处理可使LLaMA-3-8B和LLaMA-3-70B模型的吞吐量提升1.6倍，端到端延迟减少2倍，同时保持输出质量。

> Retrieval-Augmented Generation (RAG) is often used with Large Language Models (LLMs) to infuse domain knowledge or user-specific information. In RAG, given a user query, a retriever extracts chunks of relevant text from a knowledge base. These chunks are sent to an LLM as part of the input prompt. Typically, any given chunk is repeatedly retrieved across user questions. However, currently, for every question, attention-layers in LLMs fully compute the key values (KVs) repeatedly for the input chunks, as state-of-the-art methods cannot reuse KV-caches when chunks appear at arbitrary locations with arbitrary contexts. Naive reuse leads to output quality degradation. This leads to potentially redundant computations on expensive GPUs and increases latency. In this work, we propose Cache-Craft, a system for managing and reusing precomputed KVs corresponding to the text chunks (we call chunk-caches) in RAG-based systems. We present how to identify chunk-caches that are reusable, how to efficiently perform a small fraction of recomputation to fix the cache to maintain output quality, and how to efficiently store and evict chunk-caches in the hardware for maximizing reuse while masking any overheads. With real production workloads as well as synthetic datasets, we show that Cache-Craft reduces redundant computation by 51% over SOTA prefix-caching and 75% over full recomputation. Additionally, with continuous batching on a real production workload, we get a 1.6X speed up in throughput and a 2X reduction in end-to-end response latency over prefix-caching while maintaining quality, for both the LLaMA-3-8B and LLaMA-3-70B models.

[Arxiv](https://arxiv.org/abs/2502.15734)