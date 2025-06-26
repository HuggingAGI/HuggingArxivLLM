# 基于会话意图驱动的GraphRAG：通过自适应双重检索方法增强多轮对话系统，实现对话流程模式与上下文语义的优化结合。

发布时间：2025年06月24日

`RAG` `客户服务` `对话系统`

> Conversational Intent-Driven GraphRAG: Enhancing Multi-Turn Dialogue Systems through Adaptive Dual-Retrieval of Flow Patterns and Context Semantics

# 摘要

> 我们提出了一种名为 CID-GraphRAG（基于对话意图的图检索增强生成）的创新框架，旨在解决现有对话系统在多轮客服对话中同时维护上下文连贯性和目标导向性方面的不足。与仅依赖语义相似性（如 Conversation RAG）或标准知识图谱（如 GraphRAG）的传统 RAG 系统不同，CID-GraphRAG 通过分析历史对话构建动态意图转换图，并采用双重检索机制，自适应地平衡基于意图的图遍历和语义搜索。这种方法使系统能够同时利用对话意图流模式和上下文语义，显著提升检索和回复质量。在真实客服对话数据上的广泛实验中，我们结合自动评估指标和基于大语言模型的评估方法，结果表明，CID-GraphRAG 在所有评估标准上均显著优于 Conversation RAG 和 GraphRAG 基线模型。具体而言，与 Conversation RAG 相比，CID-GraphRAG 在 BLEU、ROUGE-L 和 METEOR 等自动评估指标上分别提升了 11%、5% 和 6%，而在基于大语言模型的评估中，回复质量更是提升了 58%。这些结果充分证明，意图转换结构与语义检索的结合产生了协同效应，这种效果是单一方法无法独立实现的。因此，CID-GraphRAG 成功解决了知识密集型多轮对话中保持上下文连贯性和目标导向性方面的挑战，是一个有效的框架。

> We present CID-GraphRAG (Conversational Intent-Driven Graph Retrieval Augmented Generation), a novel framework that addresses the limitations of existing dialogue systems in maintaining both contextual coherence and goal-oriented progression in multi-turn customer service conversations. Unlike traditional RAG systems that rely solely on semantic similarity (Conversation RAG) or standard knowledge graphs (GraphRAG), CID-GraphRAG constructs dynamic intent transition graphs from goal achieved historical dialogues and implements a dual-retrieval mechanism that adaptively balances intent-based graph traversal with semantic search. This approach enables the system to simultaneously leverage both conversional intent flow patterns and contextual semantics, significantly improving retrieval quality and response quality. In extensive experiments on real-world customer service dialogues, we employ both automatic metrics and LLM-as-judge assessments, demonstrating that CID-GraphRAG significantly outperforms both semantic-based Conversation RAG and intent-based GraphRAG baselines across all evaluation criteria. Quantitatively, CID-GraphRAG demonstrates substantial improvements over Conversation RAG across automatic metrics, with relative gains of 11% in BLEU, 5% in ROUGE-L, 6% in METEOR, and most notably, a 58% improvement in response quality according to LLM-as-judge evaluations. These results demonstrate that the integration of intent transition structures with semantic retrieval creates a synergistic effect that neither approach achieves independently, establishing CID-GraphRAG as an effective framework for addressing the challenges of maintaining contextual coherence and goal-oriented progression in knowledge-intensive multi-turn dialogues.

[Arxiv](https://arxiv.org/abs/2506.19385)