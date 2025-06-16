# # 基于图的 RAG 增强：通过全局查询消歧和依赖感知重排序

发布时间：2025年06月07日

`RAG` `知识图谱` `问答系统`

> Graph-based RAG Enhancement via Global Query Disambiguation and Dependency-Aware Reranking

# 摘要

> 当代图基检索增强生成（RAG）方法通常从提取用户查询中的实体开始，利用预构建的知识图谱检索相关信息。然而，这种仅依赖实体级别提取的方法可能导致关键信息的遗漏或误解，进而引发检索结果的不相关或矛盾，甚至加剧幻觉风险。为了解决这一问题，我们提出了PankRAG框架，它结合了全局感知的分层查询解析策略和依赖感知重排序机制。PankRAG通过构建多级解析路径，捕获查询中的并行和顺序依赖关系，引导大型语言模型（LLMs）进行结构化推理。随后，其依赖感知重排序器利用已解析子问题的依赖结构，丰富和验证检索结果，提升后续推理的准确性。实证评估显示，PankRAG在多个基准测试中表现优于现有最优方法，展现了其强大的稳健性和广泛的适用性。

> Contemporary graph-based retrieval-augmented generation (RAG) methods typically begin by extracting entities from user queries and then leverage pre-constructed knowledge graphs to retrieve related relationships and metadata. However, this pipeline's exclusive reliance on entity-level extraction can lead to the misinterpretation or omission of latent yet critical information and relations. As a result, retrieved content may be irrelevant or contradictory, and essential knowledge may be excluded, exacerbating hallucination risks and degrading the fidelity of generated responses. To address these limitations, we introduce PankRAG, a framework that combines a globally aware, hierarchical query-resolution strategy with a novel dependency-aware reranking mechanism. PankRAG first constructs a multi-level resolution path that captures both parallel and sequential interdependencies within a query, guiding large language models (LLMs) through structured reasoning. It then applies its dependency-aware reranker to exploit the dependency structure among resolved sub-questions, enriching and validating retrieval results for subsequent sub-questions. Empirical evaluations demonstrate that PankRAG consistently outperforms state-of-the-art approaches across multiple benchmarks, underscoring its robustness and generalizability.

[Arxiv](https://arxiv.org/abs/2506.11106)