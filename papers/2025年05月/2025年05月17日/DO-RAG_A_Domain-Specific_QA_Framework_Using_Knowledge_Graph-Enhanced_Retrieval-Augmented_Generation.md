# # DO-RAG：一个特定领域问答框架，利用知识图谱增强的检索增强生成

发布时间：2025年05月17日

`RAG` `数据库`

> DO-RAG: A Domain-Specific QA Framework Using Knowledge Graph-Enhanced Retrieval-Augmented Generation

# 摘要

> 领域特定问答系统不仅需要生成流利，更需要基于结构化专家知识的高事实准确性。现有的RAG框架在整合异构数据和保持推理一致性方面仍存在挑战。为此，我们提出了DO-RAG，一个可扩展且可定制的混合问答框架，它将多级知识图谱构建与语义向量检索相结合。

我们的系统采用新颖的智能体链式思维架构，从非结构化多模态文档中提取结构化关系，构建动态知识图谱以提高检索精度。在查询时，DO-RAG融合图谱和向量检索结果生成上下文感知的回答，并通过基于事实的优化来缓解幻觉问题。

在数据库和电气领域的实验评估显示，DO-RAG实现了近乎完美的召回率和超过94%的回答相关性，相比基线框架提升了高达33.38%的性能。通过结合可追溯性、适应性和性能效率，DO-RAG为大规模多领域的高精度问答提供了一个可靠的基础。


> Domain-specific QA systems require not just generative fluency but high factual accuracy grounded in structured expert knowledge. While recent Retrieval-Augmented Generation (RAG) frameworks improve context recall, they struggle with integrating heterogeneous data and maintaining reasoning consistency. To address these challenges, we propose DO-RAG, a scalable and customizable hybrid QA framework that integrates multi-level knowledge graph construction with semantic vector retrieval. Our system employs a novel agentic chain-of-thought architecture to extract structured relationships from unstructured, multimodal documents, constructing dynamic knowledge graphs that enhance retrieval precision. At query time, DO-RAG fuses graph and vector retrieval results to generate context-aware responses, followed by hallucination mitigation via grounded refinement. Experimental evaluations in the database and electrical domains show near-perfect recall and over 94% answer relevancy, with DO-RAG outperforming baseline frameworks by up to 33.38%. By combining traceability, adaptability, and performance efficiency, DO-RAG offers a reliable foundation for multi-domain, high-precision QA at scale.

[Arxiv](https://arxiv.org/abs/2505.17058)