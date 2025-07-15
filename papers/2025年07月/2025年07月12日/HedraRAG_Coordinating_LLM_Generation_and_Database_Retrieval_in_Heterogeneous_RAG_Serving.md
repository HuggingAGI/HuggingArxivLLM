# HedraRAG: 异构RAG服务架构下大型语言模型生成与数据库检索的协同机制

发布时间：2025年07月12日

`RAG` `云计算` `计算机系统`

> HedraRAG: Coordinating LLM Generation and Database Retrieval in Heterogeneous RAG Serving

# 摘要

> 本文聚焦于异构检索增强生成（RAG）服务中的系统级挑战，特别是复杂多阶段工作流和多样化请求模式带来的执行效率问题。我们提出了HedraRAG，一个基于图抽象的运行时系统，该系统从阶段级并行性、请求内相似性和请求间倾斜性三个维度挖掘优化潜力。通过动态图变换（如节点拆分、重新排序、边添加和依赖重接线）应用于跨越并发请求的子图波前，这些优化机会得以实现。生成的执行计划通过混合CPU-GPU管道进行映射，从而提升资源利用率并降低延迟。在多种RAG工作流上的评估结果表明，HedraRAG的性能较现有框架提升了1.5倍至5倍，充分证明了生成和检索在服务环境中的高效协调能力。

> This paper addresses emerging system-level challenges in heterogeneous retrieval-augmented generation (RAG) serving, where complex multi-stage workflows and diverse request patterns complicate efficient execution. We present HedraRAG, a runtime system built on a graph-based abstraction that exposes optimization opportunities across stage-level parallelism, intra-request similarity, and inter-request skewness. These opportunities are realized through dynamic graph transformations, such as node splitting, reordering, edge addition, and dependency rewiring, applied to wavefronts of subgraphs spanning concurrent requests. The resulting execution plans are mapped onto hybrid CPU-GPU pipelines to improve resource utilization and reduce latency. Evaluations across a wide range of RAG workflows demonstrate speedups exceeding 1.5x and reaching up to 5x over existing frameworks, showcasing the effectiveness of coordinated generation and retrieval in serving environments.

[Arxiv](https://arxiv.org/abs/2507.09138)