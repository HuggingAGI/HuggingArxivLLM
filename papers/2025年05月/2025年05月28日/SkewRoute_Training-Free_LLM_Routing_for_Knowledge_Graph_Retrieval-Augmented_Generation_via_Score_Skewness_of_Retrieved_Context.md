# SkewRoute：基于检索上下文得分偏态的无需训练LLM路由方法，实现知识图谱增强生成

发布时间：2025年05月28日

`RAG` `人工智能` `知识图谱`

> SkewRoute: Training-Free LLM Routing for Knowledge Graph Retrieval-Augmented Generation via Score Skewness of Retrieved Context

# 摘要

> 大型语言模型在多项任务中表现出色，但部署时推理成本较高。为减少幻觉现象，许多系统采用知识图谱增强检索生成（KG-RAG）。然而，检索到的大量知识上下文进一步推高了推理成本。一种平衡性能与成本的解决方案是LLM路由，它将简单查询导向较小的模型，复杂查询导向较大的模型。然而，目前尚未有专门针对RAG的路由方法，现有基于训练的路由方法因需要大量训练数据，难以扩展至这一领域。我们发现检索评分器生成的分数分布与查询难度密切相关。基于此，我们提出了一种新颖的、无需训练的路由框架，这是首个专为KG-RAG设计的框架，能够在插件式部署中有效平衡性能与成本。实验表明，我们的方法在不降低响应质量的前提下，将对较大模型的调用减少了高达50%，展示了其在高效且可扩展的LLM部署中的潜力。

> Large language models excel at many tasks but often incur high inference costs during deployment. To mitigate hallucination, many systems use a knowledge graph to enhance retrieval-augmented generation (KG-RAG). However, the large amount of retrieved knowledge contexts increase these inference costs further. A promising solution to balance performance and cost is LLM routing, which directs simple queries to smaller LLMs and complex ones to larger LLMs. However, no dedicated routing methods currently exist for RAG, and existing training-based routers face challenges scaling to this domain due to the need for extensive training data. We observe that the score distributions produced by the retrieval scorer strongly correlate with query difficulty. Based on this, we propose a novel, training-free routing framework, the first tailored to KG-RAG that effectively balances performance and cost in a plug-and-play manner. Experiments show our method reduces calls to larger LLMs by up to 50% without sacrificing response quality, demonstrating its potential for efficient and scalable LLM deployment.

[Arxiv](https://arxiv.org/abs/2505.23841)