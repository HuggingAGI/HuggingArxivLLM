# TeleRAG：高效检索增强生成推理，结合前瞻检索

发布时间：2025年02月28日

`RAG` `系统优化` `高效推理`

> TeleRAG: Efficient Retrieval-Augmented Generation Inference with Lookahead Retrieval

# 摘要

> 检索增强生成（RAG）通过整合外部数据源扩展了大型语言模型（LLMs），显著提升了事实准确性和领域覆盖范围。然而，现代RAG流水线依赖大型数据存储，在延迟敏感型部署中面临挑战，尤其在GPU内存有限的情况下。为解决这一问题，我们提出了TeleRAG——一个高效推理系统，能够在极低GPU内存需求下显著降低RAG延迟。TeleRAG的核心创新是预取检索，这是一种预取机制，能够预判所需数据并将其从CPU并行传输至GPU，与LLM生成过程同步进行。通过利用RAG流水线的模块化特性、倒排文件索引（IVF）搜索算法以及查询间的相似性，TeleRAG实现了数据传输与计算的最优重叠。实验结果表明，相比现有最优系统，TeleRAG将端到端RAG推理延迟平均降低了1.72倍，为先进RAG应用提供了更快、更内存高效的部署方案。

> Retrieval-augmented generation (RAG) extends large language models (LLMs) with external data sources to enhance factual correctness and domain coverage. Modern RAG pipelines rely on large datastores, leading to system challenges in latency-sensitive deployments, especially when limited GPU memory is available. To address these challenges, we propose TeleRAG, an efficient inference system that reduces RAG latency with minimal GPU memory requirements. The core innovation of TeleRAG is lookahead retrieval, a prefetching mechanism that anticipates required data and transfers it from CPU to GPU in parallel with LLM generation. By leveraging the modularity of RAG pipelines, the inverted file index (IVF) search algorithm and similarities between queries, TeleRAG optimally overlaps data movement and computation. Experimental results show that TeleRAG reduces end-to-end RAG inference latency by up to 1.72x on average compared to state-of-the-art systems, enabling faster, more memory-efficient deployments of advanced RAG applications.

[Arxiv](https://arxiv.org/abs/2502.20969)