# 语义压缩与图增强检索：超越最近邻，提升向量搜索效果

发布时间：2025年07月25日

`RAG

理由：这篇论文讨论了检索增强生成（RAG）中的检索方法，并提出了一种新的检索范式，旨在解决传统ANN搜索在RAG应用中的不足。论文中明确提到了RAG，并探讨了如何改进检索以满足其需求，因此属于RAG类别。` `信息检索` `人工智能`

> Beyond Nearest Neighbors: Semantic Compression and Graph-Augmented Retrieval for Enhanced Vector Search

# 摘要

> 向量数据库通常依赖近似最近邻 (ANN) 搜索来检索与查询最接近的 top-k 向量。然而，尽管有效，这种方法常导致语义冗余的结果，难以满足检索增强生成 (RAG)、多跳问答 (QA) 和记忆增强代理等应用对多样性和上下文丰富性的需求。为此，我们提出了一种全新的检索范式：语义压缩，旨在从围绕查询的广泛语义结构中精选出紧凑且具代表性的向量集合。我们通过子模优化和信息几何的原则对这一目标进行形式化，并证明其通过优先考虑覆盖范围和多样性，能够超越传统 top-k 检索。为了实现这一理念，我们引入了图增强向量检索，通过在向量空间上叠加语义图（如 kNN 或知识图谱链接）实现多跳、上下文感知的搜索。我们从理论上分析了高维空间中基于 proximity 的检索的局限性，并展示了图结构如何提升语义覆盖范围。我们的工作为以意义为中心的向量搜索系统奠定了基础，强调混合索引、多样性感知查询和结构化语义检索。我们的实现已公开，以推动未来在这一领域的研究。

> Vector databases typically rely on approximate nearest neighbor (ANN) search to retrieve the top-k closest vectors to a query in embedding space. While effective, this approach often yields semantically redundant results, missing the diversity and contextual richness required by applications such as retrieval-augmented generation (RAG), multi-hop QA, and memory-augmented agents. We introduce a new retrieval paradigm: semantic compression, which aims to select a compact, representative set of vectors that captures the broader semantic structure around a query. We formalize this objective using principles from submodular optimization and information geometry, and show that it generalizes traditional top-k retrieval by prioritizing coverage and diversity. To operationalize this idea, we propose graph-augmented vector retrieval, which overlays semantic graphs (e.g., kNN or knowledge-based links) atop vector spaces to enable multi-hop, context-aware search. We theoretically analyze the limitations of proximity-based retrieval under high-dimensional concentration and highlight how graph structures can improve semantic coverage. Our work outlines a foundation for meaning-centric vector search systems, emphasizing hybrid indexing, diversity-aware querying, and structured semantic retrieval. We make our implementation publicly available to foster future research in this area.

[Arxiv](https://arxiv.org/abs/2507.19715)