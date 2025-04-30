# ARCS：智能增强检索代码合成的迭代优化方法

发布时间：2025年04月29日

`LLM应用

理由：这篇论文主要探讨了如何将增强生成（RAG）与链式推理（CoT）结合，用于代码生成、补全和翻译。虽然提到了基于代理的RAG机制，但整体研究重点在于如何通过RAG和CoT提升代码综合能力，并在实际应用中展示其效果。因此，这篇论文更符合LLM应用的分类，因为它展示了RAG技术在实际任务中的应用和效果。` `超级计算` `软件工程`

> ARCS: Agentic Retrieval-Augmented Code Synthesis with Iterative Refinement

# 摘要

> # 摘要
在超级计算领域，高效且优化的代码生成是充分发挥高性能计算系统的关键。我们提出了一种名为“智能检索增强代码综合（ARCS）”的先进框架，专注于精确、稳健且高效的代码生成、补全和翻译。ARCS框架将增强生成（RAG）与链式推理（CoT）相结合，系统性分解并迭代优化复杂编程任务。基于代理的RAG机制检索相关代码片段，而实时执行反馈则驱动候选解决方案的合成。这一过程被形式化为一个状态-动作搜索树优化问题，在保证代码正确性的同时提升编辑效率。在Geeks4Geeks和HumanEval基准测试中，ARCS在代码翻译和生成质量上显著超越传统提示方法。通过实现可扩展且精准的代码综合能力，ARCS为超级计算应用中的代码开发自动化与优化提供了变革性潜力，从而提升计算资源利用率。

> In supercomputing, efficient and optimized code generation is essential to leverage high-performance systems effectively. We propose Agentic Retrieval-Augmented Code Synthesis (ARCS), an advanced framework for accurate, robust, and efficient code generation, completion, and translation. ARCS integrates Retrieval-Augmented Generation (RAG) with Chain-of-Thought (CoT) reasoning to systematically break down and iteratively refine complex programming tasks. An agent-based RAG mechanism retrieves relevant code snippets, while real-time execution feedback drives the synthesis of candidate solutions. This process is formalized as a state-action search tree optimization, balancing code correctness with editing efficiency. Evaluations on the Geeks4Geeks and HumanEval benchmarks demonstrate that ARCS significantly outperforms traditional prompting methods in translation and generation quality. By enabling scalable and precise code synthesis, ARCS offers transformative potential for automating and optimizing code development in supercomputing applications, enhancing computational resource utilization.

[Arxiv](https://arxiv.org/abs/2504.20434)