# LSM-VEC：基于磁盘存储的大型动态向量检索系统

发布时间：2025年05月22日

`其他

理由：这篇论文主要讨论了向量搜索技术的改进，特别是针对近似最近邻查询的动态向量索引LSM-VEC的设计与实现。虽然提到了RAG作为应用之一，但论文的核心贡献在于向量索引技术的创新，属于底层技术优化，不属于RAG、LLM应用或理论的范畴，因此归类为“其他”。` `AI应用` `向量搜索`

> LSM-VEC: A Large-Scale Disk-Based System for Dynamic Vector Search

# 摘要

> 向量搜索是现代AI应用的核心技术，支持在检索增强生成（RAG）、推荐系统和多模态搜索等任务中进行高维嵌入的近似最近邻（ANN）查询。然而，传统ANN索引（如HNSW）在处理大规模数据时，受限于内存容量，难以满足需求。基于磁盘的索引如DiskANN，虽降低了内存占用，但受限于离线图构建，导致向量更新效率低下且成本高昂。最新的基于聚类的方法SPFresh，虽然提升了可扩展性，但因粗粒度划分，导致召回率下降。此外，SPFresh采用原地更新机制，限制了其在动态负载下处理高吞吐量插入与删除的能力。
    本文提出了一种创新的基于磁盘的动态向量索引——LSM-VEC，它巧妙地将层次化图索引与LSM-tree存储相结合。通过将 proximity graph 分布在多个 LSM-tree 层中，LSM-VEC 实现了高效的 out-of-place 向量更新。其采用基于采样的概率搜索策略和自适应邻点选择机制，显著提升了搜索效率。同时，通过连接感知的图重排序技术，进一步降低了I/O需求，而无需进行全局重构。在十亿规模数据集上的实验结果表明，LSM-VEC 在性能上全面超越现有基于磁盘的 ANN 系统。它不仅实现了更高的召回率和更低的查询及更新延迟，还将内存占用减少了66.2%以上，展现出在处理动态更新的大型实际向量搜索场景中的卓越能力。

> Vector search underpins modern AI applications by supporting approximate nearest neighbor (ANN) queries over high-dimensional embeddings in tasks like retrieval-augmented generation (RAG), recommendation systems, and multimodal search. Traditional ANN search indices (e.g., HNSW) are limited by memory constraints at large data scale. Disk-based indices such as DiskANN reduce memory overhead but rely on offline graph construction, resulting in costly and inefficient vector updates. The state-of-the-art clustering-based approach SPFresh offers better scalability but suffers from reduced recall due to coarse partitioning. Moreover, SPFresh employs in-place updates to maintain its index structure, limiting its efficiency in handling high-throughput insertions and deletions under dynamic workloads.
  This paper presents LSM-VEC, a disk-based dynamic vector index that integrates hierarchical graph indexing with LSM-tree storage. By distributing the proximity graph across multiple LSM-tree levels, LSM-VEC supports out-of-place vector updates. It enhances search efficiency via a sampling-based probabilistic search strategy with adaptive neighbor selection, and connectivity-aware graph reordering further reduces I/O without requiring global reconstruction. Experiments on billion-scale datasets demonstrate that LSM-VEC consistently outperforms existing disk-based ANN systems. It achieves higher recall, lower query and update latency, and reduces memory footprint by over 66.2%, making it well-suited for real-world large-scale vector search with dynamic updates.

[Arxiv](https://arxiv.org/abs/2505.17152)