# MAIN-RAG: 多代理过滤检索增强生成

发布时间：2024年12月31日

`RAG

理由：这篇论文主要讨论了检索增强生成（RAG）系统的改进，提出了一个名为MAIN-RAG的框架，利用多个LLM智能体协作过滤和评分检索文档，以提高RAG系统的性能。因此，这篇论文的核心内容与RAG相关，应归类为RAG。` `问答系统`

> MAIN-RAG: Multi-Agent Filtering Retrieval-Augmented Generation

# 摘要

> # 摘要
大型语言模型（LLMs）在自然语言处理任务中扮演着重要角色，但常常生成过时或错误信息。检索增强生成（RAG）通过引入外部实时信息检索，提升了LLM响应的准确性。然而，现有RAG系统在检索文档质量上存在挑战，不相关或噪声文档会降低性能、增加计算开销并削弱响应可靠性。为此，我们提出了多智能体过滤检索增强生成（MAIN-RAG），这是一个无需训练的RAG框架，利用多个LLM智能体协作过滤和评分检索文档。MAIN-RAG引入了自适应过滤机制，根据评分分布动态调整相关性过滤阈值，有效减少噪声并保持高召回率。该方法通过智能体间的共识确保稳健的文档选择，无需额外训练数据或微调。在四个问答基准测试中，MAIN-RAG表现优于传统RAG方法，答案准确率提升2-11%，同时减少了不相关文档的检索数量。定量分析显示，我们的方法在响应一致性和答案准确性上优于基线方法，为基于训练的解决方案提供了一个实用且具有竞争力的替代方案。

> Large Language Models (LLMs) are becoming essential tools for various natural language processing tasks but often suffer from generating outdated or incorrect information. Retrieval-Augmented Generation (RAG) addresses this issue by incorporating external, real-time information retrieval to ground LLM responses. However, the existing RAG systems frequently struggle with the quality of retrieval documents, as irrelevant or noisy documents degrade performance, increase computational overhead, and undermine response reliability. To tackle this problem, we propose Multi-Agent Filtering Retrieval-Augmented Generation (MAIN-RAG), a training-free RAG framework that leverages multiple LLM agents to collaboratively filter and score retrieved documents. Specifically, MAIN-RAG introduces an adaptive filtering mechanism that dynamically adjusts the relevance filtering threshold based on score distributions, effectively minimizing noise while maintaining high recall of relevant documents. The proposed approach leverages inter-agent consensus to ensure robust document selection without requiring additional training data or fine-tuning. Experimental results across four QA benchmarks demonstrate that MAIN-RAG consistently outperforms traditional RAG approaches, achieving a 2-11% improvement in answer accuracy while reducing the number of irrelevant retrieved documents. Quantitative analysis further reveals that our approach achieves superior response consistency and answer accuracy over baseline methods, offering a competitive and practical alternative to training-based solutions.

[Arxiv](https://arxiv.org/abs/2501.00332)