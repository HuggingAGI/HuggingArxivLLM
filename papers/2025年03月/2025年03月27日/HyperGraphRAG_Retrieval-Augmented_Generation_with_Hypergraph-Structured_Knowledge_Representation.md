# HyperGraphRAG：通过超图结构知识表示实现的检索增强生成

发布时间：2025年03月27日

`RAG` `信息检索` `问答系统`

> HyperGraphRAG: Retrieval-Augmented Generation with Hypergraph-Structured Knowledge Representation

# 摘要

> 与标准的RAG不同，GraphRAG通过构建图结构来利用实体间的关系。然而，传统方法受限于二元关系：一条边仅连接两个实体，无法很好地表示现实中的多实体n元关系。为此，我们提出了HyperGraphRAG，一种基于超图的新型RAG方法，通过超边表示n元事实，从而更准确地建模现实中的复杂关系。我们还设计了一个完整的处理流程，包括超图构建、检索策略和生成机制。实验结果显示，在多个领域中，HyperGraphRAG的表现优于传统方法。

> While standard Retrieval-Augmented Generation (RAG) based on chunks, GraphRAG structures knowledge as graphs to leverage the relations among entities. However, previous GraphRAG methods are limited by binary relations: one edge in the graph only connects two entities, which cannot well model the n-ary relations among more than two entities that widely exist in reality. To address this limitation, we propose HyperGraphRAG, a novel hypergraph-based RAG method that represents n-ary relational facts via hyperedges, modeling the complicated n-ary relations in the real world. To retrieve and generate over hypergraphs, we introduce a complete pipeline with a hypergraph construction method, a hypergraph retrieval strategy, and a hypergraph-guided generation mechanism. Experiments across medicine, agriculture, computer science, and law demonstrate that HyperGraphRAG outperforms standard RAG and GraphRAG in accuracy and generation quality.

[Arxiv](https://arxiv.org/abs/2503.21322)