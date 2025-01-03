# DynaGRAG：动态子图表示助力图检索增强生成，提升语言理解与生成能力

发布时间：2024年12月24日

`RAG

理由：该论文提出了一种新的图检索增强生成（GRAG）框架，旨在通过引入外部知识（特别是知识图谱）来提升语言理解和生成能力。这属于检索增强生成（RAG）的范畴，因为它结合了检索机制（从知识图谱中检索相关信息）和生成模型（LLMs）来增强语言模型的表现。` `知识图谱`

> DynaGRAG: Improving Language Understanding and Generation through Dynamic Subgraph Representation in Graph Retrieval-Augmented Generation

# 摘要

> # 摘要
图检索增强生成（GRAG 或 Graph RAG）架构通过引入外部知识来提升语言理解和生成能力。然而，如何有效捕捉并整合文本与结构化数据中的丰富语义信息仍是一大挑战。为此，我们提出了一种全新的 GRAG 框架，专注于提升知识图谱中的子图表示和多样性。该框架通过优化图密度、更精准地捕捉实体与关系信息，并动态筛选相关且多样化的子图，从而更全面地理解语义结构。具体实现包括去重处理、嵌入的两步均值池化、基于唯一节点的查询感知检索，以及动态相似性感知广度优先搜索（DSA-BFS）算法。此外，通过硬提示将图卷积网络（GCNs）与大型语言模型（LLMs）结合，进一步强化了节点与边的表示学习，同时保持了层次化的子图结构。多个基准数据集的实验结果验证了该 GRAG 框架的有效性，凸显了增强子图表示和多样性对语言理解与生成的重要性。

> Graph Retrieval-Augmented Generation (GRAG or Graph RAG) architectures aim to enhance language understanding and generation by leveraging external knowledge. However, effectively capturing and integrating the rich semantic information present in textual and structured data remains a challenge. To address this, a novel GRAG framework is proposed to focus on enhancing subgraph representation and diversity within the knowledge graph. By improving graph density, capturing entity and relation information more effectively, and dynamically prioritizing relevant and diverse subgraphs, the proposed approach enables a more comprehensive understanding of the underlying semantic structure. This is achieved through a combination of de-duplication processes, two-step mean pooling of embeddings, query-aware retrieval considering unique nodes, and a Dynamic Similarity-Aware BFS (DSA-BFS) traversal algorithm. Integrating Graph Convolutional Networks (GCNs) and Large Language Models (LLMs) through hard prompting further enhances the learning of rich node and edge representations while preserving the hierarchical subgraph structure. Experimental results on multiple benchmark datasets demonstrate the effectiveness of the proposed GRAG framework, showcasing the significance of enhanced subgraph representation and diversity for improved language understanding and generation.

[Arxiv](https://arxiv.org/abs/2412.18644)