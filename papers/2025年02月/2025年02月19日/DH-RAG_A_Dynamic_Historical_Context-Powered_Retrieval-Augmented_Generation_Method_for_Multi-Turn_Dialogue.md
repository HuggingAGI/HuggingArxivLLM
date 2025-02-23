# DH-RAG：一种基于动态历史上下文的检索增强生成方法，专为多轮对话设计

发布时间：2025年02月19日

`RAG` `问答系统` `对话系统`

> DH-RAG: A Dynamic Historical Context-Powered Retrieval-Augmented Generation Method for Multi-Turn Dialogue

# 摘要

> 检索增强生成（RAG）系统在问答和多轮对话中表现优异 \citep{lewis2020retrieval}。然而，传统方法虽依赖静态知识库，却忽视了对话中的动态历史信息。为解决这一问题，我们提出了DH-RAG——一种基于动态历史上下文的增强生成方法。DH-RAG灵感源自人类对话中的记忆与即时背景结合机制 \citep{stafford1987conversational}。该方法由两大模块构成：通过整合当前与过往交互生成查询的重构模块，以及在对话全程更新历史背景的动态模块。DH-RAG的核心是一个动态历史数据库，并通过聚类、匹配和追踪策略进一步优化。实验结果表明，DH-RAG显著提升了响应质量和对话流畅度，在多个基准测试中超越传统模型。

> Retrieval-Augmented Generation (RAG) systems have shown substantial benefits in applications such as question answering and multi-turn dialogue \citep{lewis2020retrieval}. However, traditional RAG methods, while leveraging static knowledge bases, often overlook the potential of dynamic historical information in ongoing conversations. To bridge this gap, we introduce DH-RAG, a Dynamic Historical Context-Powered Retrieval-Augmented Generation Method for Multi-Turn Dialogue. DH-RAG is inspired by human cognitive processes that utilize both long-term memory and immediate historical context in conversational responses \citep{stafford1987conversational}. DH-RAG is structured around two principal components: a History-Learning based Query Reconstruction Module, designed to generate effective queries by synthesizing current and prior interactions, and a Dynamic History Information Updating Module, which continually refreshes historical context throughout the dialogue. The center of DH-RAG is a Dynamic Historical Information database, which is further refined by three strategies within the Query Reconstruction Module: Historical Query Clustering, Hierarchical Matching, and Chain of Thought Tracking. Experimental evaluations show that DH-RAG significantly surpasses conventional models on several benchmarks, enhancing response relevance, coherence, and dialogue quality.

[Arxiv](https://arxiv.org/abs/2502.13847)