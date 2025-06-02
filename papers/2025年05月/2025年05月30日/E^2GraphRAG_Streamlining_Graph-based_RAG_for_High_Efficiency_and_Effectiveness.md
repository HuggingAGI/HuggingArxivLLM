# E²GraphRAG：精简图结构 RAG，实现高效且有效的性能

发布时间：2025年05月30日

`RAG` `问答系统` `知识图谱`

> E^2GraphRAG: Streamlining Graph-based RAG for High Efficiency and Effectiveness

# 摘要

> 基于图的 RAG 方法（如 GraphRAG）通过构建层次化实体图，展现出对知识库的良好全局理解能力。然而，这些方法通常效率低下，且依赖于人工预定义的查询模式，这限制了它们的实际应用。本文提出了一种简化的图基 RAG 框架 E²GraphRAG，旨在同时提升效率和效果。在索引阶段，E²GraphRAG 利用大型语言模型构建摘要树，并基于文档片段使用 SpaCy 构建实体图。随后，我们构建实体与片段之间的双向索引，以捕捉它们的多对多关系，从而在局部和全局检索中实现快速查找。在检索阶段，我们设计了一种自适应检索策略，利用图结构在局部和全局模式之间进行检索和选择。实验表明，与 GraphRAG 相比，E²GraphRAG 的索引速度提高了 10 倍，检索速度比 LightRAG 快 100 倍，同时保持了具有竞争力的问答性能。

> Graph-based RAG methods like GraphRAG have shown promising global understanding of the knowledge base by constructing hierarchical entity graphs. However, they often suffer from inefficiency and rely on manually pre-defined query modes, limiting practical use. In this paper, we propose E^2GraphRAG, a streamlined graph-based RAG framework that improves both Efficiency and Effectiveness. During the indexing stage, E^2GraphRAG constructs a summary tree with large language models and an entity graph with SpaCy based on document chunks. We then construct bidirectional indexes between entities and chunks to capture their many-to-many relationships, enabling fast lookup during both local and global retrieval. For the retrieval stage, we design an adaptive retrieval strategy that leverages the graph structure to retrieve and select between local and global modes. Experiments show that E^2GraphRAG achieves up to 10 times faster indexing than GraphRAG and 100 times speedup over LightRAG in retrieval while maintaining competitive QA performance.

[Arxiv](https://arxiv.org/abs/2505.24226)