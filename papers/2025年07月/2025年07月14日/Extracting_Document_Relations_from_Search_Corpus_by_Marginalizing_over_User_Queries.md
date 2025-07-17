# # 提取文档关系：基于边际化用户查询从搜索语料库中提取文档关系

发布时间：2025年07月14日

`RAG` `信息处理` `信息检索`

> Extracting Document Relations from Search Corpus by Marginalizing over User Queries

# 摘要

> 大规模语料库中的文档关系理解是知识发现和信息组织的关键。但现有方法多依赖人工标注或预定义的关系分类。我们提出了一种全新框架EDR-MQ（通过用户查询边际化提取文档关系），该框架通过查询边际化发现文档间的关系。EDR-MQ的核心思想是：密切相关文档通常会在不同用户查询的结果中共同出现，这使我们能够通过对一系列查询进行边际化处理来估算文档对的联合概率。为了实现这一查询边际化方法，我们开发了“多重条件检索增强生成”（MC-RAG），该方法采用条件检索，后续的文档检索依赖于之前检索到的内容。通过观察不同查询中的共现模式，EDR-MQ无需标注训练数据或预定义分类体系，即可估算文档对的联合概率。实验结果表明，我们的查询边际化方法成功识别了有意义的文档关系，揭示了主题聚类、证据链和跨领域连接，这些都是传统基于相似性的方法所无法察觉的。我们的以查询驱动的框架为文档组织提供了一种实用的方法，能够适应不同的用户视角和信息需求。

> Understanding relationships between documents in large-scale corpora is essential for knowledge discovery and information organization. However, existing approaches rely heavily on manual annotation or predefined relationship taxonomies. We propose EDR-MQ (Extracting Document Relations by Marginalizing over User Queries), a novel framework that discovers document relationships through query marginalization. EDR-MQ is based on the insight that strongly related documents often co-occur in results across diverse user queries, enabling us to estimate joint probabilities between document pairs by marginalizing over a collection of queries. To enable this query marginalization approach, we develop Multiply Conditioned Retrieval-Augmented Generation (MC-RAG), which employs conditional retrieval where subsequent document retrievals depend on previously retrieved content. By observing co-occurrence patterns across diverse queries, EDR-MQ estimates joint probabilities between document pairs without requiring labeled training data or predefined taxonomies. Experimental results show that our query marginalization approach successfully identifies meaningful document relationships, revealing topical clusters, evidence chains, and cross-domain connections that are not apparent through traditional similarity-based methods. Our query-driven framework offers a practical approach to document organization that adapts to different user perspectives and information needs.

[Arxiv](https://arxiv.org/abs/2507.10726)