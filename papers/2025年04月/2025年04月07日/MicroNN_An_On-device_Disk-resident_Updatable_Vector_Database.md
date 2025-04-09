# MicroNN：设备端磁盘驻留的可更新向量数据库

发布时间：2025年04月07日

`其他` `信息检索` `嵌入式系统`

> MicroNN: An On-device Disk-resident Updatable Vector Database

# 摘要

> 最近邻搜索在密集向量集合中的应用广泛，涵盖信息检索、检索增强生成（RAG）和内容排序等多个领域。尽管在大型向量集合上的高效搜索已有诸多成熟方法和开源工具，但现有系统大多针对内存充足的大型服务器、静态不可更新的向量集合，以及与其他搜索条件隔离的最近邻搜索场景。我们推出Micro Nearest Neighbour（MicroNN），一个专为资源受限环境设计的嵌入式最近邻向量搜索引擎，支持可扩展的相似性搜索。MicroNN专注于解决现实场景中的设备端向量搜索问题，特别是那些包含动态更新和结合最近邻搜索与结构化属性过滤器的混合查询场景。在这些场景中，内存资源极为有限，需要高效的磁盘索引结构和算法，同时支持持续的数据插入和删除操作。MicroNN作为一个轻量级嵌入式库，能够在极低资源消耗下高效处理大型向量集合。它已在实际生产环境中得到应用，支持设备端多种向量搜索场景。在公开的百万级向量基准测试中，MicroNN仅需不到7毫秒即可检索出前100个最近邻，同时仅占用约10 MB内存，且召回率高达90%。


> Nearest neighbour search over dense vector collections has important applications in information retrieval, retrieval augmented generation (RAG), and content ranking. Performing efficient search over large vector collections is a well studied problem with many existing approaches and open source implementations. However, most state-of-the-art systems are generally targeted towards scenarios using large servers with an abundance of memory, static vector collections that are not updatable, and nearest neighbour search in isolation of other search criteria. We present Micro Nearest Neighbour (MicroNN), an embedded nearest-neighbour vector search engine designed for scalable similarity search in low-resource environments. MicroNN addresses the problem of on-device vector search for real-world workloads containing updates and hybrid search queries that combine nearest neighbour search with structured attribute filters. In this scenario, memory is highly constrained and disk-efficient index structures and algorithms are required, as well as support for continuous inserts and deletes. MicroNN is an embeddable library that can scale to large vector collections with minimal resources. MicroNN is used in production and powers a wide range of vector search use-cases on-device. MicroNN takes less than 7 ms to retrieve the top-100 nearest neighbours with 90% recall on publicly available million-scale vector benchmark while using ~10 MB of memory.

[Arxiv](https://arxiv.org/abs/2504.05573)