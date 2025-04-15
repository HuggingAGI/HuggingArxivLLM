# 自适应向量索引划分方案，实现低延迟 RAG 管道

发布时间：2025年04月11日

`RAG` `问答系统` `数据库`

> An Adaptive Vector Index Partitioning Scheme for Low-Latency RAG Pipeline

# 摘要

> 检索增强生成（RAG）系统通过结合大型语言模型（LLMs）与向量数据库，显著提升了响应质量，支持语言模型推理的外部知识检索。尽管RAG使较小规模的LLMs能够高效回答问题，但现有的向量搜索优化和LLM推理服务优化大多独立开发，导致它们结合后常常出现次优的端到端性能。……本文介绍VectorLiteRAG，这是一种专为RAG系统设计的优化向量索引划分机制。通过在CPU和GPU系统上联合优化向量搜索和LLM推理服务，VectorLiteRAG显著提升了系统的响应能力。

一个关键挑战在于确定哪些索引以及多少向量索引应驻留在GPU上，并调整LLM批处理大小以平衡管道，从而降低首次令牌生成时间（TTFT）并满足用户定义的服务级别目标（SLO）。为解决这一问题，我们发现向量数据库中集群访问呈现访问偏差的特性——即一部分集群被查询的频率远高于其他集群。VectorLiteRAG通过优化的内存分配策略，动态地将与频繁访问集群对应的最小数量的向量索引分配到GPU HBM上，确保与LLM推理服务的管道平衡，从而实现高响应能力。这一自适应划分方案由一个统计模型指导，该模型提供内存分配和工作负载分布的信息。

我们的评估表明，VectorLiteRAG将向量搜索的响应能力提高了2倍，并通过智能平衡向量搜索和LLM执行之间的内存资源，显著降低了RAG系统的端到端TTFT。

> Retrieval Augmented Generation (RAG) systems enhance response quality by integrating Large Language Models (LLMs) with vector databases, enabling external knowledge retrieval to support language model reasoning. While RAG enables efficient question answering with smaller LLMs, existing optimizations for vector search and LLM serving have largely been developed in isolation. As a result, their integration often leads to suboptimal end-to-end performance. ... This paper introduces VectorLiteRAG, an optimized vector index partitioning mechanism designed for RAG systems that enhances the responsiveness of the system by jointly optimizing vector search and LLM serving across CPU and GPU system. A key challenge is to determine which indices and how much of the vector index should reside on the GPU and adjusting LLM batch sizes to balance the pipeline for lower Time-To-First-Token (TTFT) and meeting user-defined Service-Level Objectives (SLOs). To address this, we leverage the insight that cluster access in vector databases exhibits access skew, where a subset of clusters are queried significantly more frequently than others. VectorLiteRAG exploits this property through an optimized memory distribution strategy, dynamically allocating the minimum number of vector indices corresponding to frequently accessed clusters onto the GPU HBM to ensure a balanced pipeline with the LLM for high responsiveness. This adaptive partitioning scheme is guided by a statistical model that informs memory allocation and workload distribution. Our evaluation demonstrates that VectorLiteRAG improves vector search responsiveness by 2x, significantly reduces end-to-end TTFT in RAG systems by intelligently balancing memory resources between vector search and LLM execution.

[Arxiv](https://arxiv.org/abs/2504.08930)