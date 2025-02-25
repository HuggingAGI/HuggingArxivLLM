# # 平衡 RAG-Text2SQL 系统中的内容规模问题

发布时间：2025年01月28日

`RAG

摘要讨论了将检索增强生成（RAG）与Text2SQL模型相结合的方法，重点在于RAG在提升系统性能中的应用，以及优化检索文档的质量和规模。因此，这篇论文属于RAG类别。` `数据库`

> Balancing Content Size in RAG-Text2SQL System

# 摘要

> 大型语言模型（LLMs）为将自然语言查询转换为SQL命令提供了有前景的解决方案，实现了与数据库的无缝交互。然而，Text2SQL系统存在幻觉、知识过时和推理不可追踪等固有局限。为解决这些问题，将检索增强生成（RAG）与Text2SQL模型相结合的方法逐渐兴起。RAG作为检索机制，为查询生成提供表结构和元数据等关键上下文信息。尽管潜力巨大，但RAG+Text2SQL系统的性能受制于检索文档的质量和规模。更丰富的文档内容虽能提升模式相关性和检索准确性，但也可能引入噪音，随着Text2SQL模型提示规模的增加，幻觉风险上升，查询准确性下降。本研究深入探讨了文档规模与质量的权衡，寻求优化系统性能的平衡点。我们识别了性能下降的关键阈值，并提出了应对这些挑战的实用策略。此外，我们还研究了Text2SQL模型中的幻觉现象，强调精心编排的文档展示在减少错误中的关键作用。我们的研究成果为增强RAG+Text2SQL系统的稳健性提供了指导，为实际应用提供了宝贵的见解。

> Large Language Models (LLMs) have emerged as a promising solution for converting natural language queries into SQL commands, enabling seamless database interaction. However, these Text-to-SQL (Text2SQL) systems face inherent limitations, hallucinations, outdated knowledge, and untraceable reasoning. To address these challenges, the integration of retrieval-augmented generation (RAG) with Text2SQL models has gained traction. RAG serves as a retrieval mechanism, providing essential contextual information, such as table schemas and metadata, to enhance the query generation process. Despite their potential, RAG + Text2SQL systems are susceptible to the quality and size of retrieved documents. While richer document content can improve schema relevance and retrieval accuracy, it also introduces noise, increasing the risk of hallucinations and reducing query fidelity as the prompt size of the Text2SQL model increases. This research investigates the nuanced trade-off between document size and quality, aiming to strike a balance that optimizes system performance. Key thresholds are identified where performance degradation occurs, along with actionable strategies to mitigate these challenges. Additionally, we explore the phenomenon of hallucinations in Text2SQL models, emphasizing the critical role of curated document presentation in minimizing errors. Our findings provide a roadmap for enhancing the robustness of RAG + Text2SQL systems, offering practical insights for real-world applications.

[Arxiv](https://arxiv.org/abs/2502.15723)