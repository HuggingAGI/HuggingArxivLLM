# ClusterKV：于语义空间中对 LLM 的 KV 缓存进行处理，以达成可召回压缩

发布时间：2024年12月04日

`LLM应用` `语言模型`

> ClusterKV: Manipulating LLM KV Cache in Semantic Space for Recallable Compression

# 摘要

> 大型语言模型（LLMs）已在众多应用中广泛运用，其上下文长度迅速增长，以应对长文档问答和复杂逻辑推理等任务。然而，长上下文给推理效率带来严峻挑战，像键值（KV）缓存的高内存开销以及因大量内存访问导致的延迟增加。近期工作提出压缩 KV 缓存来近似计算，可这些方法要么永久清除令牌，后续推理不再召回，要么按文本位置划分的页面粒度召回先前令牌。这两类做法都会降低模型的准确性和输出质量。为达成高效且精准的可召回 KV 缓存压缩，我们推出了 ClusterKV，它能以语义簇的粒度召回令牌。我们设计并落实了用于聚类、选择、索引和缓存的高效算法与系统。实验结果显示，ClusterKV 在上下文长度为 32k 的各类任务中准确性损失微乎其微，仅用 1k 至 2k 的 KV 缓存预算，延迟方面提速高达 2 倍，解码吞吐量提升 2.5 倍。和最先进的可召回 KV 压缩方法相比，ClusterKV 展现出更高的模型准确性和输出质量，同时保持或超越了推理效率。

> Large Language Models (LLMs) have been widely deployed in a variety of applications, and the context length is rapidly increasing to handle tasks such as long-document QA and complex logical reasoning. However, long context poses significant challenges for inference efficiency, including high memory costs of key-value (KV) cache and increased latency due to extensive memory accesses. Recent works have proposed compressing KV cache to approximate computation, but these methods either evict tokens permanently, never recalling them for later inference, or recall previous tokens at the granularity of pages divided by textual positions. Both approaches degrade the model accuracy and output quality. To achieve efficient and accurate recallable KV cache compression, we introduce ClusterKV, which recalls tokens at the granularity of semantic clusters. We design and implement efficient algorithms and systems for clustering, selection, indexing and caching. Experiment results show that ClusterKV attains negligible accuracy loss across various tasks with 32k context lengths, using only a 1k to 2k KV cache budget, and achieves up to a 2$\times$ speedup in latency and a 2.5$\times$ improvement in decoding throughput. Compared to SoTA recallable KV compression methods, ClusterKV demonstrates higher model accuracy and output quality, while maintaining or exceeding inference efficiency.

[Arxiv](https://arxiv.org/abs/2412.03213)