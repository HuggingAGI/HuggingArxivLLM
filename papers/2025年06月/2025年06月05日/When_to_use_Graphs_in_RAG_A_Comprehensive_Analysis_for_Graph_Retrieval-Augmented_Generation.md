# # RAG 中何时使用图：图检索增强生成的全面分析

发布时间：2025年06月05日

`RAG` `模型评估`

> When to use Graphs in RAG: A Comprehensive Analysis for Graph Retrieval-Augmented Generation

# 摘要

> 图检索增强生成（GraphRAG）作为一种强大的范式，通过整合外部知识来增强大型语言模型（LLMs）的能力。它利用图结构建模特定概念之间的层级关系，从而实现更连贯的知识检索和更准确的推理。然而，尽管GraphRAG在理论上具有潜力，近期研究却表明，在许多实际任务中，其表现往往逊色于传统的RAG方法。这促使我们提出了一个关键问题：GraphRAG真的有效吗？在哪些场景下，图结构能够为RAG系统带来实际优势？

为了探索这一问题，我们开发了GraphRAG-Bench，一个全面的基准测试框架，专门用于评估GraphRAG模型在层级知识检索和深度上下文推理方面的性能。该框架包含一个难度递增的综合数据集，涵盖了事实检索、复杂推理、上下文摘要和创意生成等多种任务，并对从图构建、知识检索到最终生成的整个流程进行全面评估。通过这一创新的基准测试，我们系统地分析了GraphRAG超越传统RAG的条件及其成功背后的原因，为其实际应用提供了宝贵的指导。所有相关资源和分析均已整理在https://github.com/GraphRAG-Bench/GraphRAG-Benchmark，供研究社区参考和使用。

> Graph retrieval-augmented generation (GraphRAG) has emerged as a powerful paradigm for enhancing large language models (LLMs) with external knowledge. It leverages graphs to model the hierarchical structure between specific concepts, enabling more coherent and effective knowledge retrieval for accurate reasoning.Despite its conceptual promise, recent studies report that GraphRAG frequently underperforms vanilla RAG on many real-world tasks. This raises a critical question: Is GraphRAG really effective, and in which scenarios do graph structures provide measurable benefits for RAG systems? To address this, we propose GraphRAG-Bench, a comprehensive benchmark designed to evaluate GraphRAG models onboth hierarchical knowledge retrieval and deep contextual reasoning. GraphRAG-Bench features a comprehensive dataset with tasks of increasing difficulty, coveringfact retrieval, complex reasoning, contextual summarization, and creative generation, and a systematic evaluation across the entire pipeline, from graph constructionand knowledge retrieval to final generation. Leveraging this novel benchmark, we systematically investigate the conditions when GraphRAG surpasses traditional RAG and the underlying reasons for its success, offering guidelines for its practical application. All related resources and analyses are collected for the community at https://github.com/GraphRAG-Bench/GraphRAG-Benchmark.

[Arxiv](https://arxiv.org/abs/2506.05690)