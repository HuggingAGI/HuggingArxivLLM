# 大型语言模型是否具备上下文图学习能力？

发布时间：2025年02月19日

`RAG` `图结构` `图学习`

> Are Large Language Models In-Context Graph Learners?

# 摘要

> 大型语言模型（LLMs）在处理语言或图像等非结构化输入时展现了卓越的上下文推理能力。然而，由于缺乏对非欧几里得结构的理解，LLMs在处理图等结构化数据时表现挣扎，其性能显著落后于图神经网络（GNNs）。本文提出了一种全新的视角：将图数据的学习过程视为检索辅助生成（RAG）过程，其中节点或边等特定实例作为查询，图本身则作为检索到的上下文。基于这一见解，我们提出了一系列RAG框架，旨在提升LLMs在图学习任务中的上下文学习能力。实验结果表明，我们的RAG框架显著提升了LLMs在基于图的任务中的性能，尤其是在必须使用预训练好的LLMs且无法修改或只能通过API访问的情况下。

> Large language models (LLMs) have demonstrated remarkable in-context reasoning capabilities across a wide range of tasks, particularly with unstructured inputs such as language or images. However, LLMs struggle to handle structured data, such as graphs, due to their lack of understanding of non-Euclidean structures. As a result, without additional fine-tuning, their performance significantly lags behind that of graph neural networks (GNNs) in graph learning tasks. In this paper, we show that learning on graph data can be conceptualized as a retrieval-augmented generation (RAG) process, where specific instances (e.g., nodes or edges) act as queries, and the graph itself serves as the retrieved context. Building on this insight, we propose a series of RAG frameworks to enhance the in-context learning capabilities of LLMs for graph learning tasks. Comprehensive evaluations demonstrate that our proposed RAG frameworks significantly improve LLM performance on graph-based tasks, particularly in scenarios where a pretrained LLM must be used without modification or accessed via an API.

[Arxiv](https://arxiv.org/abs/2502.13562)