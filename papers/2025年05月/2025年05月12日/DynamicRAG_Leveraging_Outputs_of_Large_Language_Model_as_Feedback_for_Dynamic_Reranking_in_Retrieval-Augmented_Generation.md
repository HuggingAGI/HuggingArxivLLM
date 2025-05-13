# 动态RAG：将大型语言模型的输出作为反馈机制，应用于检索增强生成中的动态重排序。

发布时间：2025年05月12日

`RAG` `RAG系统`

> DynamicRAG: Leveraging Outputs of Large Language Model as Feedback for Dynamic Reranking in Retrieval-Augmented Generation

# 摘要

> 检索增强生成（RAG）系统通过结合大型语言模型（LLMs）与外部知识检索，在知识密集型任务中表现出色。其中，重排器作为关键组件，通过优化检索到的文档来提升生成质量与可解释性。然而，如何选择最优文档数量（k）仍是一个未解难题：文档过少可能导致关键信息缺失，而过多则会引入噪声和低效。尽管近期研究探索了基于LLMs的重排器，但它们主要依赖模型内部知识，忽视了LLMs可提供的丰富监督信号，例如利用生成质量作为反馈来优化重排决策。本文提出DynamicRAG，一种新颖的RAG框架，其中重排器会根据查询动态调整检索到的文档顺序和数量。我们将重排器建模为一个通过强化学习（RL）优化的智能体，使用LLM输出质量作为奖励。在七个知识密集型数据集上，DynamicRAG表现出色，达到当前最佳水平。模型、数据和代码可在https://github.com/GasolSun36/DynamicRAG获取

> Retrieval-augmented generation (RAG) systems combine large language models (LLMs) with external knowledge retrieval, making them highly effective for knowledge-intensive tasks. A crucial but often under-explored component of these systems is the reranker, which refines retrieved documents to enhance generation quality and explainability. The challenge of selecting the optimal number of documents (k) remains unsolved: too few may omit critical information, while too many introduce noise and inefficiencies. Although recent studies have explored LLM-based rerankers, they primarily leverage internal model knowledge and overlook the rich supervisory signals that LLMs can provide, such as using response quality as feedback for optimizing reranking decisions. In this paper, we propose DynamicRAG, a novel RAG framework where the reranker dynamically adjusts both the order and number of retrieved documents based on the query. We model the reranker as an agent optimized through reinforcement learning (RL), using rewards derived from LLM output quality. Across seven knowledge-intensive datasets, DynamicRAG demonstrates superior performance, achieving state-of-the-art results. The model, data and code are available at https://github.com/GasolSun36/DynamicRAG

[Arxiv](https://arxiv.org/abs/2505.07233)