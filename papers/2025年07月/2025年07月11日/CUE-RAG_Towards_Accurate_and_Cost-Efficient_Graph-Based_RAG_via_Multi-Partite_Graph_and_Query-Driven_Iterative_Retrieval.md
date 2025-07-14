# # CUE-RAG：迈向准确且成本高效的基于图的RAG

发布时间：2025年07月11日

`RAG` `问答系统` `知识图谱`

> CUE-RAG: Towards Accurate and Cost-Efficient Graph-Based RAG via Multi-Partite Graph and Query-Driven Iterative Retrieval

# 摘要

> 尽管大型语言模型（LLMs）取得了显著进展，但其在问答（QA）任务中的性能仍受限于缺乏特定领域和最新的知识。检索增强生成（RAG）通过引入外部信息（通常来自图结构化数据）来解决这一问题。然而，现有的基于图的RAG方法由于在检索过程中信息提取不完整且未充分利用查询信息，导致图质量较差。为克服这些限制，我们提出了CUE-RAG，这是一种创新方法，包含以下三个要素：(1) 一个多部图索引，整合文本片段、知识单元和实体，以多层级粒度捕获语义内容；(2) 一种混合提取策略，在减少LLM令牌使用的同时，仍能生成准确且无歧义的知识单元；(3) Q-Iter，一种基于查询的迭代检索策略，通过语义搜索和受限图遍历提升相关性。在三个问答基准上的实验表明，CUE-RAG显著超越了现有的先进基线，准确率提高了99.33%，F1分数提高了113.51%，同时将索引成本降低了72.58%。值得注意的是，即使在不使用LLM进行索引的情况下，CUE-RAG仍能与基线持平或超越。这些结果证明了CUE-RAG在推进基于图的RAG系统方面的有效性和成本效益。

> Despite the remarkable progress of Large Language Models (LLMs), their performance in question answering (QA) remains limited by the lack of domain-specific and up-to-date knowledge. Retrieval-Augmented Generation (RAG) addresses this limitation by incorporating external information, often from graph-structured data. However, existing graph-based RAG methods suffer from poor graph quality due to incomplete extraction and insufficient utilization of query information during retrieval. To overcome these limitations, we propose CUE-RAG, a novel approach that introduces (1) a multi-partite graph index incorporates text Chunks, knowledge Units, and Entities to capture semantic content at multiple levels of granularity, (2) a hybrid extraction strategy that reduces LLM token usage while still producing accurate and disambiguated knowledge units, and (3) Q-Iter, a query-driven iterative retrieval strategy that enhances relevance through semantic search and constrained graph traversal. Experiments on three QA benchmarks show that CUE-RAG significantly outperforms state-of-the-art baselines, achieving up to 99.33% higher Accuracy and 113.51% higher F1 score while reducing indexing costs by 72.58%. Remarkably, CUE-RAG matches or outperforms baselines even without using an LLM for indexing. These results demonstrate the effectiveness and cost-efficiency of CUE-RAG in advancing graph-based RAG systems.

[Arxiv](https://arxiv.org/abs/2507.08445)