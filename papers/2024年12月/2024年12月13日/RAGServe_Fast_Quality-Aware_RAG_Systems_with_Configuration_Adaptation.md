# RAGServe: 配置自适应的快速质量感知 RAG 系统

发布时间：2024年12月13日

`RAG

理由：这篇论文主要讨论了RAG（检索增强生成）系统的优化问题，特别是如何通过联合调度查询和动态调整RAG配置来平衡生成质量和延迟。论文的核心内容围绕RAG系统的改进和应用，因此应归类为RAG。` `问答系统` `检索增强生成`

> RAGServe: Fast Quality-Aware RAG Systems with Configuration Adaptation

# 摘要

> RAG（检索增强生成）让LLMs借助外部知识生成更优质的响应，但增加外部知识往往会以响应延迟为代价提升生成质量。以往的研究要么通过优化RAG查询调度来减少延迟，要么通过调整RAG工作流程来最大化质量，但它们在平衡延迟和质量方面仍有不足。本文提出的RAGServe是首个联合调度查询并动态调整每个查询的关键RAG配置（如检索文本块数量和合成方法）的系统，旨在平衡质量优化与延迟减少。基于4个流行的RAG-QA数据集，RAGServe在不牺牲生成质量的情况下，将生成延迟降低了$1.64-2.54	imes$，表现优于现有RAG优化方案。

> RAG (Retrieval Augmented Generation) allows LLMs (large language models) to generate better responses with external knowledge, but using more external knowledge often improves generation quality at the expense of response delay. Prior work either reduces the response delay (through better scheduling of RAG queries) or strives to maximize quality (which involves tuning the RAG workflow), but they fall short in optimizing the tradeoff between the delay and quality of RAG responses. This paper presents RAGServe, the first RAG system that jointly schedules queries and adapts the key RAG configurations of each query, such as the number of retrieved text chunks and synthesis methods, in order to balance quality optimization and response delay reduction. Using 4 popular RAG-QA datasets, we show that compared with the state-of-the-art RAG optimization schemes, RAGServe reduces the generation latency by $1.64-2.54\times$ without sacrificing generation quality.

[Arxiv](https://arxiv.org/abs/2412.10543)