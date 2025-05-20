# # 知识增强的RAG框架：Know3-RAG——具备自适应检索、生成和过滤功能
Know3-RAG 是一个知识增强的RAG（检索增强生成）框架，该框架集成了自适应检索、生成和过滤功能，形成了一体化的解决方案。

发布时间：2025年05月18日

`RAG` `问答系统` `知识图谱`

> Know3-RAG: A Knowledge-aware RAG Framework with Adaptive Retrieval, Generation, and Filtering

# 摘要

> 大型语言模型（LLMs）在自然语言生成领域取得了显著进展，但生成幻觉或无依据内容的倾向仍是关键问题。为提升事实可靠性，检索增强生成（RAG）在推理过程中整合外部知识。然而，现有RAG系统面临两大限制：（1）受限于外部知识监督，导致适应性控制不可靠；（2）不准确或不相关的引用引发幻觉。为解决这些问题，我们提出Know3-RAG，一种基于知识增强的RAG框架，利用知识图谱（KGs）的结构化知识指导RAG过程的三个核心阶段，包括检索、生成和筛选。具体而言，我们引入了知识感知的自适应检索模块，通过KG嵌入评估生成答案的置信度并确定检索需求；知识增强的引用生成策略，通过KG衍生实体丰富查询以提升引用相关性；以及基于知识的引用筛选机制，确保引用的语义一致性和事实准确性。在多个开放领域问答基准上的实验表明，Know3-RAG始终超越强基线模型，显著减少幻觉并提升答案可靠性。

> Recent advances in large language models (LLMs) have led to impressive progress in natural language generation, yet their tendency to produce hallucinated or unsubstantiated content remains a critical concern. To improve factual reliability, Retrieval-Augmented Generation (RAG) integrates external knowledge during inference. However, existing RAG systems face two major limitations: (1) unreliable adaptive control due to limited external knowledge supervision, and (2) hallucinations caused by inaccurate or irrelevant references. To address these issues, we propose Know3-RAG, a knowledge-aware RAG framework that leverages structured knowledge from knowledge graphs (KGs) to guide three core stages of the RAG process, including retrieval, generation, and filtering. Specifically, we introduce a knowledge-aware adaptive retrieval module that employs KG embedding to assess the confidence of the generated answer and determine retrieval necessity, a knowledge-enhanced reference generation strategy that enriches queries with KG-derived entities to improve generated reference relevance, and a knowledge-driven reference filtering mechanism that ensures semantic alignment and factual accuracy of references. Experiments on multiple open-domain QA benchmarks demonstrate that Know3-RAG consistently outperforms strong baselines, significantly reducing hallucinations and enhancing answer reliability.

[Arxiv](https://arxiv.org/abs/2505.12662)