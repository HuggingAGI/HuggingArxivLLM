# AlayaDB：为高效且有效的长上下文LLM推理构建数据基石

发布时间：2025年04月14日

`LLM应用` `大型语言模型` `推理系统`

> AlayaDB: The Data Foundation for Efficient and Effective Long-context LLM Inference

# 摘要

> AlayaDB 是 AlayaDB AI 推出的一款前沿向量数据库系统，专为大型语言模型 (LLMs) 的高效长上下文推理而原生设计。它通过分离 KV 缓存和注意力计算，将这些功能封装到一个新型向量数据库系统中，与传统 LLM 推理系统形成鲜明对比。对于模型即服务提供商 (MaaS)，AlayaDB 在满足不同服务级别目标 (SLOs) 的多样化工作负载时，相比现有替代方案（如 KV 缓存拆分、基于检索的稀疏注意力）更节省硬件资源并提供更优质的生成质量。AlayaDB 的核心在于将 LLM 推理中的注意力计算和缓存管理抽象为查询处理流程，并通过原生查询优化器实现性能提升。在本研究中，我们通过来自行业合作伙伴的三个实际案例，以及在 LLM 推理基准上的广泛实验结果，充分证明了 AlayaDB 的有效性。

> AlayaDB is a cutting-edge vector database system natively architected for efficient and effective long-context inference for Large Language Models (LLMs) at AlayaDB AI. Specifically, it decouples the KV cache and attention computation from the LLM inference systems, and encapsulates them into a novel vector database system. For the Model as a Service providers (MaaS), AlayaDB consumes fewer hardware resources and offers higher generation quality for various workloads with different kinds of Service Level Objectives (SLOs), when comparing with the existing alternative solutions (e.g., KV cache disaggregation, retrieval-based sparse attention). The crux of AlayaDB is that it abstracts the attention computation and cache management for LLM inference into a query processing procedure, and optimizes the performance via a native query optimizer. In this work, we demonstrate the effectiveness of AlayaDB via (i) three use cases from our industry partners, and (ii) extensive experimental results on LLM inference benchmarks.

[Arxiv](https://arxiv.org/abs/2504.10326)