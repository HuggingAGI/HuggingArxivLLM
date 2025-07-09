# # 高效从非结构化文本构建与检索知识图谱，赋能大规模 RAG 系统

发布时间：2025年07月03日

`RAG` `遗留代码迁移`

> Efficient Knowledge Graph Construction and Retrieval from Unstructured Text for Large-Scale RAG Systems

# 摘要

> 我们提出了一种可扩展且经济高效的框架，用于在企业环境中部署基于图的检索增强生成（GraphRAG）。尽管GraphRAG在多跳推理和结构化检索方面展现出潜力，但其采用受到使用大型语言模型（LLMs）构建知识图谱的高昂计算成本以及基于图检索的延迟的限制。为了解决这些问题，我们引入了两个核心创新：(1) 一种基于依赖的知识图构建管道，利用工业级NLP库从非结构化文本中提取实体和关系，完全消除对LLMs的依赖；(2) 一种轻量级图检索策略，结合混合查询节点识别与高效的单跳遍历，实现高召回率、低延迟的子图提取。我们在两个专注于遗留代码迁移的SAP数据集上评估了我们的框架，并展示了强劲的实证性能。我们的系统在基于LLM-as-Judge和RAGAS指标的评估中，分别比传统的基于LLM的RAG基线提升了15%和4.35%。此外，我们的基于依赖的构建方法达到了LLM生成知识图谱性能的94%（61.87% vs. 65.83%），同时显著降低了成本并提升了可扩展性。这些结果验证了在不产生过高资源需求的情况下，在现实世界的大规模企业应用中部署GraphRAG系统的可行性，为实用、可解释且领域可适配的检索增强推理铺平了道路。

> We propose a scalable and cost-efficient framework for deploying Graph-based Retrieval Augmented Generation (GraphRAG) in enterprise environments. While GraphRAG has shown promise for multi-hop reasoning and structured retrieval, its adoption has been limited by the high computational cost of constructing knowledge graphs using large language models (LLMs) and the latency of graph-based retrieval. To address these challenges, we introduce two core innovations: (1) a dependency-based knowledge graph construction pipeline that leverages industrial-grade NLP libraries to extract entities and relations from unstructured text completely eliminating reliance on LLMs; and (2) a lightweight graph retrieval strategy that combines hybrid query node identification with efficient one-hop traversal for high-recall, low-latency subgraph extraction. We evaluate our framework on two SAP datasets focused on legacy code migration and demonstrate strong empirical performance. Our system achieves up to 15% and 4.35% improvements over traditional RAG baselines based on LLM-as-Judge and RAGAS metrics, respectively. Moreover, our dependency-based construction approach attains 94% of the performance of LLM-generated knowledge graphs (61.87% vs. 65.83%) while significantly reducing cost and improving scalability. These results validate the feasibility of deploying GraphRAG systems in real-world, large-scale enterprise applications without incurring prohibitive resource requirements paving the way for practical, explainable, and domain-adaptable retrieval-augmented reasoning.

[Arxiv](https://arxiv.org/abs/2507.03226)