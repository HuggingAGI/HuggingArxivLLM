# Quake：为向量搜索设计的自适应索引方案

发布时间：2025年06月06日

`其他` `推荐系统` `信息检索`

> Quake: Adaptive Indexing for Vector Search

# 摘要

> 向量搜索是一项从高维向量数据库中找到查询向量最接近的k个近邻的任务，这项技术支撑着许多机器学习应用，包括增强生成、推荐系统和信息检索。然而，现有的近似最近邻（ANN）方法在动态且数据分布变化的工作负载下表现不佳。我们引入了Quake，这是一个自适应索引系统，能够在这些环境中保持低延迟和高召回率。Quake采用了一种多级分区方案，能够根据更新和不断变化的访问模式进行调整，并通过一个基于分区大小和访问频率来预测查询延迟的成本模型进行指导。此外，Quake还通过一种新颖的召回率估计模型动态设置查询执行参数，以满足召回率目标。Quake还利用了NUMA感知的查询内并行，在搜索过程中提高了内存带宽的利用率。为了评估Quake，我们准备了一个基于维基百科的向量搜索工作负载，并开发了一个工作负载生成器，用于创建具有可配置访问模式的向量搜索工作负载。我们的评估表明，在动态工作负载下，与最先进的索引如SVS、DiskANN、HNSW和SCANN相比，Quake在查询延迟上实现了1.5到38倍的提升，在更新延迟上实现了4.5到126倍的提升。


> Vector search, the task of finding the k-nearest neighbors of a query vector against a database of high-dimensional vectors, underpins many machine learning applications, including retrieval-augmented generation, recommendation systems, and information retrieval. However, existing approximate nearest neighbor (ANN) methods perform poorly under dynamic and skewed workloads where data distributions evolve. We introduce Quake, an adaptive indexing system that maintains low latency and high recall in such environments. Quake employs a multi-level partitioning scheme that adjusts to updates and changing access patterns, guided by a cost model that predicts query latency based on partition sizes and access frequencies. Quake also dynamically sets query execution parameters to meet recall targets using a novel recall estimation model. Furthermore, Quake utilizes NUMA-aware intra-query parallelism for improved memory bandwidth utilization during search. To evaluate Quake, we prepare a Wikipedia vector search workload and develop a workload generator to create vector search workloads with configurable access patterns. Our evaluation shows that on dynamic workloads, Quake achieves query latency reductions of 1.5-38x and update latency reductions of 4.5-126x compared to state-of-the-art indexes such as SVS, DiskANN, HNSW, and SCANN.

[Arxiv](https://arxiv.org/abs/2506.03437)