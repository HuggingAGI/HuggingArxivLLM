# StreamingRAG: 实时上下文检索与生成框架

发布时间：2025年01月23日

`RAG

理由：这篇论文提出了一种名为StreamingRAG的框架，专门用于处理流数据，并实时构建动态知识图谱。该框架结合了多模态大模型（MM-LLMs）来实现时间感知的场景表示，并快速响应事件或用户查询。StreamingRAG的核心是实时检索增强生成（RAG）技术，旨在克服传统RAG系统在实时分析中的不足。因此，这篇论文应归类为RAG。`

> StreamingRAG: Real-time Contextual Retrieval and Generation Framework

# 摘要

> 从医疗、交通、遥感等多模态数据流中提取实时洞察仍具挑战。高计算需求和知识局限限制了多模态大模型（MM-LLMs）的应用。传统RAG系统虽能弥补知识不足，但预处理缓慢，难以满足实时分析需求。为此，我们提出StreamingRAG，一种专为流数据设计的RAG框架。它实时构建场景-对象-实体关系的动态知识图谱，利用MM-LLMs实现时间感知的场景表示，并快速响应事件或用户查询。StreamingRAG克服了现有方法的不足，在实时分析（吞吐量提升5-6倍）、上下文准确性（通过时间知识图谱）和资源消耗（轻量级模型减少2-3倍）方面取得了显著提升。

> Extracting real-time insights from multi-modal data streams from various domains such as healthcare, intelligent transportation, and satellite remote sensing remains a challenge. High computational demands and limited knowledge scope restrict the applicability of Multi-Modal Large Language Models (MM-LLMs) on these data streams. Traditional Retrieval-Augmented Generation (RAG) systems address knowledge limitations of these models, but suffer from slow preprocessing, making them unsuitable for real-time analysis. We propose StreamingRAG, a novel RAG framework designed for streaming data. StreamingRAG constructs evolving knowledge graphs capturing scene-object-entity relationships in real-time. The knowledge graph achieves temporal-aware scene representations using MM-LLMs and enables timely responses for specific events or user queries. StreamingRAG addresses limitations in existing methods, achieving significant improvements in real-time analysis (5-6x faster throughput), contextual accuracy (through a temporal knowledge graph), and reduced resource consumption (using lightweight models by 2-3x).

[Arxiv](https://arxiv.org/abs/2501.14101)