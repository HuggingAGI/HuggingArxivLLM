# # RGL：一个图中心、模块化的高效图上检索增强生成框架

发布时间：2025年03月24日

`RAG` `图数据库` `RAG系统`

> RGL: A Graph-Centric, Modular Framework for Efficient Retrieval-Augmented Generation on Graphs

# 摘要

> 图学习的最新进展推动了一系列创新型检索增强生成（RAG）系统的诞生，这些系统能够充分利用图数据中的固有关系结构。然而，现有方法大多受限于 rigid 的固定设置和高昂的工程成本，这严重影响了它们的适应性和扩展性。此外，RAG 研究领域长期忽视了图数据库领域在大规模图中高效检索 interesting 子结构方面的研究成果。为了解决这些问题，我们推出了 RAG-on-Graphs 图库（RGL），这是一个模块化的框架，能够将完整的 RAG 管道——从高效的图索引、动态节点检索，到子图构建、分词处理，再到最终的生成——无缝整合到一个统一的系统中。RGL 通过支持多种图格式，并为关键组件提供优化实现，成功解决了诸多核心挑战，与传统方法相比，实现了最高达 143 倍的速度提升。此外，RGL 提供了灵活的实用工具，例如动态节点过滤功能，能够在减少 token 消耗的同时，快速提取相关子图。通过广泛的评估测试，我们证实 RGL 不仅显著加速了原型开发过程，还全方位提升了基于图的 RAG 系统的性能表现和应用场景覆盖范围。

> Recent advances in graph learning have paved the way for innovative retrieval-augmented generation (RAG) systems that leverage the inherent relational structures in graph data. However, many existing approaches suffer from rigid, fixed settings and significant engineering overhead, limiting their adaptability and scalability. Additionally, the RAG community has largely overlooked the decades of research in the graph database community regarding the efficient retrieval of interesting substructures on large-scale graphs. In this work, we introduce the RAG-on-Graphs Library (RGL), a modular framework that seamlessly integrates the complete RAG pipeline-from efficient graph indexing and dynamic node retrieval to subgraph construction, tokenization, and final generation-into a unified system. RGL addresses key challenges by supporting a variety of graph formats and integrating optimized implementations for essential components, achieving speedups of up to 143x compared to conventional methods. Moreover, its flexible utilities, such as dynamic node filtering, allow for rapid extraction of pertinent subgraphs while reducing token consumption. Our extensive evaluations demonstrate that RGL not only accelerates the prototyping process but also enhances the performance and applicability of graph-based RAG systems across a range of tasks.

[Arxiv](https://arxiv.org/abs/2503.19314)