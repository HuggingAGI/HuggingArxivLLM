# DGRAG: 分布式图基检索增强生成，应用于边缘-云系统

发布时间：2025年05月26日

`RAG` `边缘计算` `分布式系统`

> DGRAG: Distributed Graph-based Retrieval-Augmented Generation in Edge-Cloud Systems

# 摘要

> 检索增强生成（RAG）作为一种极具潜力的方法，通过整合外部知识来提升语言模型的能力。然而，现实世界的数据往往分散在多个设备上，传统RAG方法需要集中存储这些数据，这不仅带来隐私担忧，还导致高昂的计算成本和延迟问题。为了解决这些问题，我们提出了一种基于分布式知识图谱的RAG方法——DGRAG，应用于边-云系统中。每个边缘设备维护本地知识库，仅与云端共享知识摘要。DGRAG包含两个主要阶段：首先，在分布式知识构建阶段，DGRAG利用知识图谱组织本地知识，生成子图摘要并存储在云端的摘要数据库中；其次，在协作检索与生成阶段，DGRAG在本地进行知识检索和答案生成，门控机制判断查询是否超出本地能力范围。对于超出本地范围的查询，云端根据摘要从最相关的边缘设备检索知识并生成更精确的答案。实验结果表明，DGRAG在问答任务质量方面显著优于基线方法。

> Retrieval-Augmented Generation (RAG) has emerged as a promising approach to enhance the capabilities of language models by integrating external knowledge. Due to the diversity of data sources and the constraints of memory and computing resources, real-world data is often scattered in multiple devices. Conventional RAGs that store massive amounts of scattered data centrally face increasing privacy concerns and high computational costs. Additionally, RAG in a central node raises latency issues when searching over a large-scale knowledge base. To address these challenges, we propose a distributed Knowledge Graph-based RAG approach, referred to as DGRAG, in an edge-cloud system, where each edge device maintains a local knowledge base without the need to share it with the cloud, instead sharing only summaries of its knowledge. Specifically, DGRAG has two main phases. In the Distributed Knowledge Construction phase, DGRAG organizes local knowledge using knowledge graphs, generating subgraph summaries and storing them in a summary database in the cloud as information sharing. In the Collaborative Retrieval and Generation phase, DGRAG first performs knowledge retrieval and answer generation locally, and a gate mechanism determines whether the query is beyond the scope of local knowledge or processing capabilities. For queries that exceed the local knowledge scope, the cloud retrieves knowledge from the most relevant edges based on the summaries and generates a more precise answer. Experimental results demonstrate the effectiveness of the proposed DGRAG approach in significantly improving the quality of question-answering tasks over baseline approaches.

[Arxiv](https://arxiv.org/abs/2505.19847)