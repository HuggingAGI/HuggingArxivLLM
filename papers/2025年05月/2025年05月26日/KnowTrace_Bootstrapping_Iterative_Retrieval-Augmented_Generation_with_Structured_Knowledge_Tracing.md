# 知迹：基于结构化知识追踪的迭代检索增强生成自举方法

发布时间：2025年05月26日

`RAG` `问答系统` `知识图谱`

> KnowTrace: Bootstrapping Iterative Retrieval-Augmented Generation with Structured Knowledge Tracing

# 摘要

> 检索增强生成（RAG）的最新进展为大型语言模型（LLMs）赋予了处理复杂多跳问题的能力，通过迭代检索相关知识来实现。这些方法通常交替运用LLM推理与检索，将外部信息整合到模型上下文中。然而，随着上下文规模的不断扩大，LLM捕捉关键信息间关联的难度也随之增加，而无效推理步骤更是加剧了这一负担。本文提出了一种名为KnowTrace的优雅RAG框架，旨在（1）缓解上下文过载问题，（2）提升多步推理的质量。与简单堆叠检索内容不同，KnowTrace能够自主追踪所需的知识三元组，构建与输入问题相关的知识图谱。这种结构化设计不仅为LLM提供了清晰的推理上下文，还激发了一种知识回溯机制，用于识别有助于自举过程的生成内容作为监督数据。实验结果表明，KnowTrace在三个多跳问答基准测试中均超越现有方法，其自举版本更进一步放大了性能优势。

> Recent advances in retrieval-augmented generation (RAG) furnish large language models (LLMs) with iterative retrievals of relevant information to handle complex multi-hop questions. These methods typically alternate between LLM reasoning and retrieval to accumulate external information into the LLM's context. However, the ever-growing context inherently imposes an increasing burden on the LLM to perceive connections among critical information pieces, with futile reasoning steps further exacerbating this overload issue. In this paper, we present KnowTrace, an elegant RAG framework to (1) mitigate the context overload and (2) bootstrap higher-quality multi-step reasoning. Instead of simply piling the retrieved contents, KnowTrace autonomously traces out desired knowledge triplets to organize a specific knowledge graph relevant to the input question. Such a structured workflow not only empowers the LLM with an intelligible context for inference, but also naturally inspires a reflective mechanism of knowledge backtracing to identify contributive LLM generations as process supervision data for self-bootstrapping. Extensive experiments show that KnowTrace consistently surpasses existing methods across three multi-hop question answering benchmarks, and the bootstrapped version further amplifies the gains.

[Arxiv](https://arxiv.org/abs/2505.20245)