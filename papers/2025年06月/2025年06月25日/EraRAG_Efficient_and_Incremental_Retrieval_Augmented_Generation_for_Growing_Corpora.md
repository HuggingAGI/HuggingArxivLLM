# EraRAG：面向不断增长语料库的高效增量式检索增强生成

发布时间：2025年06月25日

`RAG` `信息检索`

> EraRAG: Efficient and Incremental Retrieval Augmented Generation for Growing Corpora

# 摘要

> # 摘要
基于图的检索增强生成（Graph-RAG）通过在外部语料库上结构化检索来增强大型语言模型（LLMs）。然而，现有的方法通常假设语料库是静态的，这限制了它们在动态环境中的可扩展性。为了解决这一问题，我们提出了EraRAG——一个支持高效动态更新的多层Graph-RAG框架。通过基于超平面的局部敏感哈希（LSH），我们将原始语料库组织为分层图结构，实现了新数据的高效插入，同时保持了高准确性和低延迟。实验表明，EraRAG在更新效率和准确性上显著优于现有方法。这项工作为处理动态语料库的RAG系统提供了实用解决方案。我们的代码和数据可在GitHub获取。


> Graph-based Retrieval-Augmented Generation (Graph-RAG) enhances large language models (LLMs) by structuring retrieval over an external corpus. However, existing approaches typically assume a static corpus, requiring expensive full-graph reconstruction whenever new documents arrive, limiting their scalability in dynamic, evolving environments. To address these limitations, we introduce EraRAG, a novel multi-layered Graph-RAG framework that supports efficient and scalable dynamic updates. Our method leverages hyperplane-based Locality-Sensitive Hashing (LSH) to partition and organize the original corpus into hierarchical graph structures, enabling efficient and localized insertions of new data without disrupting the existing topology. The design eliminates the need for retraining or costly recomputation while preserving high retrieval accuracy and low latency. Experiments on large-scale benchmarks demonstrate that EraRag achieves up to an order of magnitude reduction in update time and token consumption compared to existing Graph-RAG systems, while providing superior accuracy performance. This work offers a practical path forward for RAG systems that must operate over continually growing corpora, bridging the gap between retrieval efficiency and adaptability. Our code and data are available at https://github.com/EverM0re/EraRAG-Official.

[Arxiv](https://arxiv.org/abs/2506.20963)