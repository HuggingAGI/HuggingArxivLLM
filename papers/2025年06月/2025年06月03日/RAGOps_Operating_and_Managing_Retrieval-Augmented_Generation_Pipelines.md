# RAGOps：检索增强生成流水线的操作与管控

发布时间：2025年06月03日

`RAG` `企业环境` `数据管理`

> RAGOps: Operating and Managing Retrieval-Augmented Generation Pipelines

# 摘要

> 最近的研究显示，在企业环境中，60%的基于LLM的复合系统采用了检索增强生成（RAG）技术。通过从外部数据源中检索相关信息，RAG显著提升了LLM（或其他生成AI）输出的相关性和准确性。LLMOps专注于在生产环境中管理LLM复合系统的生命周期和操作，通过持续优化和反馈机制提升系统性能。RAGOps则在此基础上进一步强化了数据管理能力，以应对外部数据源的动态变化。这需要自动化的方法来评估和测试数据操作，从而优化检索相关性和生成质量。本文旨在（1）基于4+1模型视图，系统性地描述RAG应用的通用架构；（2）全面梳理RAG系统的生命周期，整合LLM和数据管理的协同机制；（3）深入探讨RAGOps在RAG生命周期各阶段的关键设计考量和质量权衡；（4）总结RAGOps领域面临的核心研究挑战；（5）通过两个实际案例，展示RAG应用及其对应的RAGOps实践。

> Recent studies show that 60% of LLM-based compound systems in enterprise environments leverage some form of retrieval-augmented generation (RAG), which enhances the relevance and accuracy of LLM (or other genAI) outputs by retrieving relevant information from external data sources. LLMOps involves the practices and techniques for managing the lifecycle and operations of LLM compound systems in production environments. It supports enhancing LLM systems through continuous operations and feedback evaluation. RAGOps extends LLMOps by incorporating a strong focus on data management to address the continuous changes in external data sources. This necessitates automated methods for evaluating and testing data operations, enhancing retrieval relevance and generation quality. In this paper, we (1) characterize the generic architecture of RAG applications based on the 4+1 model view for describing software architectures, (2) outline the lifecycle of RAG systems, which integrates the management lifecycles of both the LLM and the data, (3) define the key design considerations of RAGOps across different stages of the RAG lifecycle and quality trade-off analyses, (4) highlight the overarching research challenges around RAGOps, and (5) present two use cases of RAG applications and the corresponding RAGOps considerations.

[Arxiv](https://arxiv.org/abs/2506.03401)