# SINDI：一种针对稀疏向量近似最大内积搜索的高效索引

发布时间：2025年09月10日

`RAG` `金融科技`

> SINDI: an Efficient Index for Approximate Maximum Inner Product Search on Sparse Vectors

# 摘要

> 稀疏向量最大内积搜索（MIPS）是检索增强生成（RAG）多路径检索的核心技术。近年来，基于倒排索引和图的算法在兼顾实用效率的同时，已实现较高的搜索精度。但在生产环境中，其性能常受冗余距离计算和频繁随机内存访问的制约。此外，稀疏向量的压缩存储格式还会阻碍SIMD加速技术的应用。为此，本文提出稀疏倒排非冗余距离索引（SINDI），该索引集成了三项关键优化：（i）高效内积计算：SINDI借助SIMD加速，省去冗余标识符查找步骤，支持批量内积计算；（ii）内存友好设计：SINDI将对原始向量的随机内存访问改为对倒排列表的顺序访问，大幅降低内存受限延迟；（iii）向量剪枝：SINDI仅保留向量中幅值较大的非零项，在保证精度的前提下提升查询吞吐量。我们在多个真实数据集上对SINDI进行了评估，实验结果显示，SINDI在不同规模、语言和模型的数据集上均表现出最先进的性能。在MsMarco数据集上，当Recall@50超过99%时，SINDI的单线程每秒查询数（QPS）较SEISMIC和PyANNs提升了4.2至26.4倍。值得一提的是，SINDI已集成至蚂蚁集团开源向量搜索库VSAG中。

> Sparse vector Maximum Inner Product Search (MIPS) is crucial in multi-path retrieval for Retrieval-Augmented Generation (RAG). Recent inverted index-based and graph-based algorithms have achieved high search accuracy with practical efficiency. However, their performance in production environments is often limited by redundant distance computations and frequent random memory accesses. Furthermore, the compressed storage format of sparse vectors hinders the use of SIMD acceleration. In this paper, we propose the sparse inverted non-redundant distance index (SINDI), which incorporates three key optimizations: (i) Efficient Inner Product Computation: SINDI leverages SIMD acceleration and eliminates redundant identifier lookups, enabling batched inner product computation; (ii) Memory-Friendly Design: SINDI replaces random memory accesses to original vectors with sequential accesses to inverted lists, substantially reducing memory-bound latency. (iii) Vector Pruning: SINDI retains only the high-magnitude non-zero entries of vectors, improving query throughput while maintaining accuracy. We evaluate SINDI on multiple real-world datasets. Experimental results show that SINDI achieves state-of-the-art performance across datasets of varying scales, languages, and models. On the MsMarco dataset, when Recall@50 exceeds 99%, SINDI delivers single-thread query-per-second (QPS) improvements ranging from 4.2 to 26.4 times compared with SEISMIC and PyANNs. Notably, SINDI has been integrated into Ant Group's open-source vector search library, VSAG.

[Arxiv](https://arxiv.org/abs/2509.08395)