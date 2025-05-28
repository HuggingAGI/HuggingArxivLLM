# # syftr：生成式AI的帕累托最优解决方案

发布时间：2025年05月26日

`RAG` `生成式AI` `智能体`

> syftr: Pareto-Optimal Generative AI

# 摘要

> 检索增强生成（RAG）管道是将大型语言模型（LLMs）应用于专有或动态数据的核心技术。但构建有效的RAG流程充满挑战，需要在向量数据库、嵌入模型、文本分割器、检索器和合成LLMs之间进行谨慎选择。随着智能体范式的兴起，这一挑战变得更加复杂。验证器、重写器和重排序器等模块——每个模块都有复杂的超参数依赖关系——必须经过精心调整。在性能敏感的应用中，平衡延迟、准确性和成本之间的权衡变得越来越困难。我们引入了syftr框架，它能够在广泛的智能体和非智能体RAG配置空间中进行高效的多目标搜索。通过贝叶斯优化，syftr能够发现帕累托最优的流程，这些流程能够同时优化任务准确性和成本。一种新颖的提前终止机制进一步提高了效率，通过剔除明显次优的候选方案。在多个RAG基准测试中，syftr找到的流程平均成本仅为最优质流程的约十分之一，同时保持了大部分准确性。此外，syftr的设计和优化能力使其能够集成新模块，从而更轻松、更快地实现高性能生成式AI管道。

> Retrieval-Augmented Generation (RAG) pipelines are central to applying large language models (LLMs) to proprietary or dynamic data. However, building effective RAG flows is complex, requiring careful selection among vector databases, embedding models, text splitters, retrievers, and synthesizing LLMs. The challenge deepens with the rise of agentic paradigms. Modules like verifiers, rewriters, and rerankers-each with intricate hyperparameter dependencies have to be carefully tuned. Balancing tradeoffs between latency, accuracy, and cost becomes increasingly difficult in performance-sensitive applications.
  We introduce syftr, a framework that performs efficient multi-objective search over a broad space of agentic and non-agentic RAG configurations. Using Bayesian Optimization, syftr discovers Pareto-optimal flows that jointly optimize task accuracy and cost. A novel early-stopping mechanism further improves efficiency by pruning clearly suboptimal candidates. Across multiple RAG benchmarks, syftr finds flows which are on average approximately 9 times cheaper while preserving most of the accuracy of the most accurate flows on the Pareto-frontier. Furthermore, syftr's ability to design and optimize allows integrating new modules, making it even easier and faster to realize high-performing generative AI pipelines.

[Arxiv](https://arxiv.org/abs/2505.20266)