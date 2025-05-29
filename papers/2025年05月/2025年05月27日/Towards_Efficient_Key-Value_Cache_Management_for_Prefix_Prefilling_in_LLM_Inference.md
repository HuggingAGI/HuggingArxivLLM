# 探索 LLM 推理中前缀填充的高效键值缓存管理方法

发布时间：2025年05月27日

`LLM应用` `AI推理` `分布式存储`

> Towards Efficient Key-Value Cache Management for Prefix Prefilling in LLM Inference

# 摘要

> 随着大型语言模型（LLMs）扩展上下文窗口的广泛应用，高效的键值缓存（KVC）管理成为优化推理性能的关键。检索增强生成（RAG）和智能体等推理任务具有高缓存复用性，因此高效的缓存管理对于减少冗余和提升速度至关重要。我们通过分析公开追踪数据中的实际KVC访问模式，评估了Redis等商用键值存储和基于RDMA的先进系统（如CHIME [1]和Sherman [2]）在KVC元数据管理中的表现。研究表明，现有存储方案未能针对KVC预加载进行优化，凸显了为LLM工作负载设计高效分布式缓存系统的重要性，该系统需具备优化的元数据管理功能。我们的研究为设计更优的KVC管理系统，实现可扩展、低延迟的推理提供了重要见解。

> The increasing adoption of large language models (LLMs) with extended context windows necessitates efficient Key-Value Cache (KVC) management to optimize inference performance. Inference workloads like Retrieval-Augmented Generation (RAG) and agents exhibit high cache reusability, making efficient caching critical to reducing redundancy and improving speed. We analyze real-world KVC access patterns using publicly available traces and evaluate commercial key-value stores like Redis and state-of-the-art RDMA-based systems (CHIME [1] and Sherman [2]) for KVC metadata management. Our work demonstrates the lack of tailored storage solution for KVC prefilling, underscores the need for an efficient distributed caching system with optimized metadata management for LLM workloads, and provides insights into designing improved KVC management systems for scalable, low-latency inference.

[Arxiv](https://arxiv.org/abs/2505.21919)