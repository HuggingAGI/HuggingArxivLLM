# SentenceKV：通过句级语义键值缓存实现的高效LLM推理

发布时间：2025年04月01日

`LLM应用` `人工智能`

> SentenceKV: Efficient LLM Inference via Sentence-Level Semantic KV Caching

# 摘要

> 大型语言模型在处理长上下文时面临显著的计算和内存挑战。在推理过程中，高效管理存储自回归生成中间激活的键值（KV）缓存对于降低内存开销和提高计算效率至关重要。传统基于词元的高效KV缓存方法忽视了语义信息，将词元独立处理而未考虑其语义关系。同时，现有的语义保留KV缓存管理方法通常面临内存占用过大和首次令牌生成时间过长的问题。为了解决这些限制，我们提出了SentenceKV，这是一种新颖的基于句子级别的语义KV缓存方法，旨在在保持语义连贯性的同时提升推理效率。

在预填充阶段，SentenceKV基于句子级别的语义相似性对词元进行分组，将句子表示压缩为简洁的语义向量并直接存储在GPU上，同时将单个KV对卸载到CPU。在解码阶段，SentenceKV通过选择性检索语义相关的句子级别KV条目生成词元，利用预填充阶段语义向量与解码阶段查询之间的语义相似性。这确保了高效且上下文准确的预测，最大限度减少了将冗余或无关数据加载到GPU内存中，同时显著降低了内存开销，即使对于极长上下文也能保持稳定的推理延迟。

在PG-19、LongBench和Needle-In-A-Haystack等基准上的广泛评估表明，SentenceKV在效率和内存使用方面显著优于现有最先进方法，同时不牺牲模型准确性。

> Large language models face significant computational and memory challenges when processing long contexts. During inference, efficient management of the key-value (KV) cache, which stores intermediate activations for autoregressive generation, is critical to reducing memory overhead and improving computational efficiency. Traditional token-level efficient KV caching methods overlook semantic information, treating tokens independently without considering their semantic relationships. Meanwhile, existing semantic-preserving KV cache management approaches often suffer from substantial memory usage and high time-to-first-token. To address these limitations, we propose SentenceKV, a novel sentence-level semantic KV caching approach designed to enhance inference efficiency while preserving semantic coherence. During prefilling, SentenceKV groups tokens based on sentence-level semantic similarity, compressing sentence representations into concise semantic vectors stored directly on the GPU, while individual KV pairs are offloaded to CPU. During decoding, SentenceKV generates tokens by selectively retrieving semantically relevant sentence-level KV entries, leveraging the semantic similarity between the prefilling-stage semantic vectors and decoding-stage queries. This ensures efficient and contextually accurate predictions, minimizing the loading of redundant or irrelevant data into GPU memory and significantly reducing memory overhead while maintaining stable inference latency, even for extremely long contexts. Extensive evaluations on benchmarks including PG-19, LongBench, and Needle-In-A-Haystack demonstrate that SentenceKV significantly outperforms state-of-the-art methods in both efficiency and memory usage, without compromising model accuracy.

[Arxiv](https://arxiv.org/abs/2504.00970)