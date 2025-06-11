# LEANN：一种低存储向量索引方法

发布时间：2025年06月09日

`其他` `推荐系统` `信息检索`

> LEANN: A Low-Storage Vector Index

# 摘要

> 基于嵌入的搜索在推荐和检索增强生成（RAG）等应用中得到了广泛应用。然而，最近越来越多的需求是支持在设备本地存储的个人数据上实现这些功能。然而，由于其高昂的存储开销，维护与基于嵌入的搜索相关联的数据结构往往难以实现。例如，对100GB的原始数据进行索引需要150到700GB的存储空间，使得本地部署变得不切实际。在保持搜索质量和延迟的同时降低这一开销成为了一个关键挑战。本文中，我们提出了LEANN，一种针对资源受限个人设备的存储高效近似最近邻（ANN）搜索索引。LEANN结合了紧凑的图结构和高效的实时重新计算策略，以实现快速且准确的检索，同时仅产生极小的存储开销。我们的评估表明，LEANN将索引大小压缩至原始原始数据的5%以下，相比标准索引实现了高达50倍的存储缩减，同时在真实世界的问题回答基准测试中，不到2秒内实现了90%的top-3召回率。

> Embedding-based search is widely used in applications such as recommendation and retrieval-augmented generation (RAG). Recently, there is a growing demand to support these capabilities over personal data stored locally on devices. However, maintaining the necessary data structure associated with the embedding-based search is often infeasible due to its high storage overhead. For example, indexing 100 GB of raw data requires 150 to 700 GB of storage, making local deployment impractical. Reducing this overhead while maintaining search quality and latency becomes a critical challenge. In this paper, we present LEANN, a storage-efficient approximate nearest neighbor (ANN) search index optimized for resource-constrained personal devices. LEANN combines a compact graph-based structure with an efficient on-the-fly recomputation strategy to enable fast and accurate retrieval with minimal storage overhead. Our evaluation shows that LEANN reduces index size to under 5% of the original raw data, achieving up to 50 times smaller storage than standard indexes, while maintaining 90% top-3 recall in under 2 seconds on real-world question answering benchmarks.

[Arxiv](https://arxiv.org/abs/2506.08276)