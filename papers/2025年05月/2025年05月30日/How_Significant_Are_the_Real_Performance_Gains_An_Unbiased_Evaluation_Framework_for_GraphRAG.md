# 实际性能提升究竟有多大？无偏见的GraphRAG评估框架

发布时间：2025年05月30日

`RAG` `评估框架` `问答系统`

> How Significant Are the Real Performance Gains? An Unbiased Evaluation Framework for GraphRAG

# 摘要

> 通过从知识图谱中检索上下文，基于图的检索增强生成（GraphRAG）增强了大型语言模型（LLMs），能够生成高质量的回答来回应用户的问题。许多GraphRAG方法已被提出，并在答案质量方面展现了令人鼓舞的性能。然而，我们发现目前针对GraphRAG的答案评估框架存在两个关键缺陷：无关问题和评估偏见，这可能导致对性能的有偏甚至错误的结论。为了解决这两个问题，我们提出了一种无偏评估框架，采用基于图-文基础的问题生成方法，以产生与底层数据集更相关的问题，以及一种无偏评估流程，以消除基于LLM的答案评估中的偏见。我们将我们的无偏框架应用于评估3种代表性的GraphRAG方法，并发现它们的性能提升比之前报告的要温和得多。尽管我们的评估框架可能仍存在缺陷，但它呼吁进行科学的评估，为GraphRAG研究奠定坚实的基础。

> By retrieving contexts from knowledge graphs, graph-based retrieval-augmented generation (GraphRAG) enhances large language models (LLMs) to generate quality answers for user questions. Many GraphRAG methods have been proposed and reported inspiring performance in answer quality. However, we observe that the current answer evaluation framework for GraphRAG has two critical flaws, i.e., unrelated questions and evaluation biases, which may lead to biased or even wrong conclusions on performance. To tackle the two flaws, we propose an unbiased evaluation framework that uses graph-text-grounded question generation to produce questions that are more related to the underlying dataset and an unbiased evaluation procedure to eliminate the biases in LLM-based answer assessment. We apply our unbiased framework to evaluate 3 representative GraphRAG methods and find that their performance gains are much more moderate than reported previously. Although our evaluation framework may still have flaws, it calls for scientific evaluations to lay solid foundations for GraphRAG research.

[Arxiv](https://arxiv.org/abs/2506.06331)