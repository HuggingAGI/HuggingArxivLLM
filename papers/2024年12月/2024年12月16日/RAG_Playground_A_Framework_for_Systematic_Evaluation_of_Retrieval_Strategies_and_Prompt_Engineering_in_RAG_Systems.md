# RAG 游乐场：用于系统评估 RAG 系统中检索策略和提示工程的框架

发布时间：2024年12月16日

`RAG` `语言模型`

> RAG Playground: A Framework for Systematic Evaluation of Retrieval Strategies and Prompt Engineering in RAG Systems

# 摘要

> 我们带来了 RAG Playground 这一开源框架，用于对检索增强生成（RAG）系统展开系统性评估。此框架实现并对比了三种检索方式：朴素向量搜索、重排序以及混合向量-关键字搜索，还结合了采用不同提示策略的 ReAct 代理。我们引入了具备新指标的全面评估框架，并给出了在各类检索配置中对不同语言模型（Llama 3.1 和 Qwen 2.5）的实证结果。我们的实验显示，借助混合搜索方法和结构化的自我评估提示，性能有显著提升，在我们的多指标评估框架中通过率高达 72.7％。结果也凸显了提示工程在 RAG 系统里的重要性，我们的自定义提示代理在检索准确率和响应质量方面呈现出持续的进步。

> We present RAG Playground, an open-source framework for systematic evaluation of Retrieval-Augmented Generation (RAG) systems. The framework implements and compares three retrieval approaches: naive vector search, reranking, and hybrid vector-keyword search, combined with ReAct agents using different prompting strategies. We introduce a comprehensive evaluation framework with novel metrics and provide empirical results comparing different language models (Llama 3.1 and Qwen 2.5) across various retrieval configurations. Our experiments demonstrate significant performance improvements through hybrid search methods and structured self-evaluation prompting, achieving up to 72.7% pass rate on our multi-metric evaluation framework. The results also highlight the importance of prompt engineering in RAG systems, with our custom-prompted agents showing consistent improvements in retrieval accuracy and response quality.

[Arxiv](https://arxiv.org/abs/2412.12322)