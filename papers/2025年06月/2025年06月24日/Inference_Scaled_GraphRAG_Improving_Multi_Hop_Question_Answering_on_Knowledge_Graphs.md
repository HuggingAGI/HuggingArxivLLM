# 推理扩展的GraphRAG：优化知识图谱多跳问答

发布时间：2025年06月24日

`RAG` `知识图谱` `问答系统`

> Inference Scaled GraphRAG: Improving Multi Hop Question Answering on Knowledge Graphs

# 摘要

> 大型语言模型（LLMs）在语言理解和生成方面表现优异，但受限于对结构化上下文和多跳信息的有限访问，它们在知识密集型推理任务上的表现仍不尽如人意。检索增强生成（RAG）通过将生成过程基于检索到的上下文，部分缓解了这一问题，但传统的RAG和GraphRAG方法往往无法有效捕捉知识图谱中节点间的关系结构。我们引入了推理扩展的GraphRAG（Inference-Scaled GraphRAG），这是一种通过推理时的计算扩展来增强LLM图推理能力的新颖框架。我们的方法结合了顺序扩展与深度链式思维图遍历，以及并行扩展与基于多数投票的采样轨迹，在交错的推理-执行循环中实现。在GRBench基准上的实验表明，我们的方法显著提升了多跳问答性能，相较于传统GraphRAG和先前的图遍历基线，取得了显著的性能提升。这些发现表明，推理时的扩展为利用LLM进行结构化知识推理提供了一种实用且架构无关的解决方案。


> Large Language Models (LLMs) have achieved impressive capabilities in language understanding and generation, yet they continue to underperform on knowledge-intensive reasoning tasks due to limited access to structured context and multi-hop information. Retrieval-Augmented Generation (RAG) partially mitigates this by grounding generation in retrieved context, but conventional RAG and GraphRAG methods often fail to capture relational structure across nodes in knowledge graphs. We introduce Inference-Scaled GraphRAG, a novel framework that enhances LLM-based graph reasoning by applying inference-time compute scaling. Our method combines sequential scaling with deep chain-of-thought graph traversal, and parallel scaling with majority voting over sampled trajectories within an interleaved reasoning-execution loop. Experiments on the GRBench benchmark demonstrate that our approach significantly improves multi-hop question answering performance, achieving substantial gains over both traditional GraphRAG and prior graph traversal baselines. These findings suggest that inference-time scaling is a practical and architecture-agnostic solution for structured knowledge reasoning with LLMs

[Arxiv](https://arxiv.org/abs/2506.19967)