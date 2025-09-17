# 探究HPC平台上分布式向量数据库的性能：基于Qdrant的研究

发布时间：2025年09月15日

`RAG` `基础理论`

> Exploring Distributed Vector Databases Performance on HPC Platforms: A Study with Qdrant

# 摘要

> 向量数据库近年来迅速走红，实现了对文本、图像、视频等数据的高效相似性搜索。如今已成为现代AI工作流的核心组件，通过检索增强生成技术将模型输出锚定在外部文献中，为大型语言模型提供有力支持。尽管至关重要，但在驱动大规模科学研究的高性能计算（HPC）系统中，向量数据库的性能特征仍鲜为人知。本研究在阿贡领导计算设施的Polaris超级计算机上，对分布式向量数据库性能展开实证分析：基于BV-BRC构建真实生物文本工作负载，利用Qwen3-Embedding-4B模型从peS2o语料库生成嵌入向量，并选取Qdrant作为研究对象，在最多32个工作节点下测试了插入、索引构建及查询延迟等指标。结合实践经验教训，本研究首次探索了HPC平台上向量数据库的性能特征，为后续研究与优化提供了重要参考。

> Vector databases have rapidly grown in popularity, enabling efficient similarity search over data such as text, images, and video. They now play a central role in modern AI workflows, aiding large language models by grounding model outputs in external literature through retrieval-augmented generation. Despite their importance, little is known about the performance characteristics of vector databases in high-performance computing (HPC) systems that drive large-scale science. This work presents an empirical study of distributed vector database performance on the Polaris supercomputer in the Argonne Leadership Computing Facility. We construct a realistic biological-text workload from BV-BRC and generate embeddings from the peS2o corpus using Qwen3-Embedding-4B. We select Qdrant to evaluate insertion, index construction, and query latency with up to 32 workers. Informed by practical lessons from our experience, this work takes a first step toward characterizing vector database performance on HPC platforms to guide future research and optimization.

[Arxiv](https://arxiv.org/abs/2509.12384)