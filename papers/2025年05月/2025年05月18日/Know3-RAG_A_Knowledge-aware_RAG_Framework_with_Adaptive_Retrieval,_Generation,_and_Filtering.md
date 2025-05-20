# Know3-RAG：知识增强的RAG框架，支持自适应检索、生成与过滤。

发布时间：2025年05月18日

`RAG` `问答系统` `知识图谱`

> Know3-RAG: A Knowledge-aware RAG Framework with Adaptive Retrieval, Generation, and Filtering

# 摘要

> 尽管大型语言模型（LLMs）在自然语言生成领域取得了显著进展，但生成不实或缺乏依据内容的问题仍是关键挑战。为提升事实可靠性，检索增强生成（RAG）通过整合外部知识来优化推理过程。然而，现有RAG系统存在两大局限：外部知识监督不足导致的自适应控制不可靠，以及不准确或不相关参考引发的幻觉问题。针对这些问题，我们提出了Know3-RAG框架，该框架利用知识图谱（KGs）的结构化知识，从检索、生成到过滤三个核心环节全面优化RAG过程。具体而言，Know3-RAG通过KG嵌入评估生成答案的信心并决定检索需求；通过KG衍生实体丰富查询以提升参考相关性；并通过知识驱动的机制确保参考的语义一致性和事实准确性。在多个开放领域问答基准测试中，Know3-RAG显著优于现有基线模型，大幅降低了幻觉现象，同时提升了答案的可靠性。

> Recent advances in large language models (LLMs) have led to impressive progress in natural language generation, yet their tendency to produce hallucinated or unsubstantiated content remains a critical concern. To improve factual reliability, Retrieval-Augmented Generation (RAG) integrates external knowledge during inference. However, existing RAG systems face two major limitations: (1) unreliable adaptive control due to limited external knowledge supervision, and (2) hallucinations caused by inaccurate or irrelevant references. To address these issues, we propose Know3-RAG, a knowledge-aware RAG framework that leverages structured knowledge from knowledge graphs (KGs) to guide three core stages of the RAG process, including retrieval, generation, and filtering. Specifically, we introduce a knowledge-aware adaptive retrieval module that employs KG embedding to assess the confidence of the generated answer and determine retrieval necessity, a knowledge-enhanced reference generation strategy that enriches queries with KG-derived entities to improve generated reference relevance, and a knowledge-driven reference filtering mechanism that ensures semantic alignment and factual accuracy of references. Experiments on multiple open-domain QA benchmarks demonstrate that Know3-RAG consistently outperforms strong baselines, significantly reducing hallucinations and enhancing answer reliability.

[Arxiv](https://arxiv.org/abs/2505.12662)