# 提升LLM系统语义缓存性能的集成嵌入方法

发布时间：2025年07月08日

`LLM应用` `计算机科学`

> An Ensemble Embedding Approach for Improving Semantic Caching Performance in LLM-based Systems

# 摘要

> 语义缓存通过识别语义相似的查询，存储一次响应，并为后续等效请求提供服务，从而提升大型语言模型（LLM）系统的效率。然而，现有的语义缓存框架依赖单一嵌入模型来表示查询，这限制了它们捕捉现实世界查询分布中多样化语义关系的能力。本文提出了一种集成嵌入方法，通过训练元编码器结合多个嵌入模型，以提升LLM缓存系统中的语义相似性检测能力。我们使用Quora问题配对数据集（QQP）对方法进行了评估，测量了缓存命中率、缓存未命中率、节省的标记数和响应时间。我们的集成方法在语义等效查询上实现了92%的缓存命中率，同时在正确拒绝非等效查询为缓存未命中方面达到了85%的准确率。这些结果表明，集成嵌入方法在区分语义相似和不相似查询方面显著优于单一模型方法，从而在LLM系统中实现了更有效的缓存性能和更低的计算开销。

> Semantic caching enhances the efficiency of large language model (LLM) systems by identifying semantically similar queries, storing responses once, and serving them for subsequent equivalent requests. However, existing semantic caching frameworks rely on single embedding models for query representation, which limits their ability to capture the diverse semantic relationships present in real-world query distributions. This paper presents an ensemble embedding approach that combines multiple embedding models through a trained meta-encoder to improve semantic similarity detection in LLM caching systems. We evaluate our method using the Quora Question Pairs (QQP) dataset, measuring cache hit ratios, cache miss ratios, token savings, and response times. Our ensemble approach achieves a 92\% cache hit ratio for semantically equivalent queries while maintaining an 85\% accuracy in correctly rejecting non-equivalent queries as cache misses. These results demonstrate that ensemble embedding methods significantly outperform single-model approaches in distinguishing between semantically similar and dissimilar queries, leading to more effective caching performance and reduced computational overhead in LLM-based systems.

[Arxiv](https://arxiv.org/abs/2507.07061)