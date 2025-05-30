# # 增强型语言模型的查询路由机制

发布时间：2025年05月28日

`RAG` `信息检索` `问答系统`

> Query Routing for Retrieval-Augmented Language Models

# 摘要

> 检索增强生成（RAG）显著提升了大型语言模型（LLMs）在知识密集型任务上的性能。然而，在RAG框架下，不同LLMs的响应质量存在显著差异，这使得需要智能路由机制来选择最适合每个查询的模型。而现有基于静态参数化知识表示的路由方法在RAG场景中表现不佳。针对这一问题，我们重新定义了新的检索增强LLM路由问题，将检索文档的影响纳入路由框架。我们提出了RAGRouter，一种感知RAG的路由设计，利用对比学习，RAGRouter能够捕捉文档嵌入和RAG能力嵌入的变化，从而实现更加明智的路由决策。在多种知识密集型任务和检索设置下的大量实验表明，RAGRouter平均比最佳单个LLM高出3.61%，比现有路由方法高出3.29%-9.33%。通过扩展的基于分数阈值的机制，在低延迟约束下，它还实现了强大的性能与效率的权衡。

> Retrieval-Augmented Generation (RAG) significantly improves the performance of Large Language Models (LLMs) on knowledge-intensive tasks. However, varying response quality across LLMs under RAG necessitates intelligent routing mechanisms, which select the most suitable model for each query from multiple retrieval-augmented LLMs via a dedicated router model. We observe that external documents dynamically affect LLMs' ability to answer queries, while existing routing methods, which rely on static parametric knowledge representations, exhibit suboptimal performance in RAG scenarios. To address this, we formally define the new retrieval-augmented LLM routing problem, incorporating the influence of retrieved documents into the routing framework. We propose RAGRouter, a RAG-aware routing design, which leverages document embeddings and RAG capability embeddings with contrastive learning to capture knowledge representation shifts and enable informed routing decisions. Extensive experiments on diverse knowledge-intensive tasks and retrieval settings show that RAGRouter outperforms the best individual LLM by 3.61% on average and existing routing methods by 3.29%-9.33%. With an extended score-threshold-based mechanism, it also achieves strong performance-efficiency trade-offs under low-latency constraints.

[Arxiv](https://arxiv.org/abs/2505.23052)