# KET-RAG：一种成本高效的图式RAG多粒度索引框架

发布时间：2025年02月13日

`RAG` `问答系统` `知识图谱`

> KET-RAG: A Cost-Efficient Multi-Granular Indexing Framework for Graph-RAG

# 摘要

> Graph-RAG 通过构建知识图谱提升 LLM 问答系统检索效果，尤其适用于需要多跳推理的生物医学、法律和政治科学领域。现有 Graph-RAG 系统基于文本块相关性构建 KNN 图，但无法捕捉实体关系，导致质量不佳。近期解决方案利用 LLM 提取实体和关系构建三元组知识图谱，但索引成本高昂。

为此，我们提出 KET-RAG 多粒度索引框架。它首先识别关键文本块并构建知识图谱骨架，然后构建文本-关键词二分图作为轻量替代。检索时，它结合骨架的局部搜索和二分图的模拟搜索提升质量。在两个真实数据集上，KET-RAG 在索引成本、检索效果和生成质量上均优于其他方案。与微软 Graph-RAG 相比，它检索质量相当或更优，索引成本降低超一个数量级，生成质量提升最高 32.4%，索引成本降低约 20%。

> Graph-RAG constructs a knowledge graph from text chunks to improve retrieval in Large Language Model (LLM)-based question answering. It is particularly useful in domains such as biomedicine, law, and political science, where retrieval often requires multi-hop reasoning over proprietary documents. Some existing Graph-RAG systems construct KNN graphs based on text chunk relevance, but this coarse-grained approach fails to capture entity relationships within texts, leading to sub-par retrieval and generation quality. To address this, recent solutions leverage LLMs to extract entities and relationships from text chunks, constructing triplet-based knowledge graphs. However, this approach incurs significant indexing costs, especially for large document collections.
  To ensure a good result accuracy while reducing the indexing cost, we propose KET-RAG, a multi-granular indexing framework. KET-RAG first identifies a small set of key text chunks and leverages an LLM to construct a knowledge graph skeleton. It then builds a text-keyword bipartite graph from all text chunks, serving as a lightweight alternative to a full knowledge graph. During retrieval, KET-RAG searches both structures: it follows the local search strategy of existing Graph-RAG systems on the skeleton while mimicking this search on the bipartite graph to improve retrieval quality. We evaluate eight solutions on two real-world datasets, demonstrating that KET-RAG outperforms all competitors in indexing cost, retrieval effectiveness, and generation quality. Notably, it achieves comparable or superior retrieval quality to Microsoft's Graph-RAG while reducing indexing costs by over an order of magnitude. Additionally, it improves the generation quality by up to 32.4% while lowering indexing costs by around 20%.

[Arxiv](https://arxiv.org/abs/2502.09304)