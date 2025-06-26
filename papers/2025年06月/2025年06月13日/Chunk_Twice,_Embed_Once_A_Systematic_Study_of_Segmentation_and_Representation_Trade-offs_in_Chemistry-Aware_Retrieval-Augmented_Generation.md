# 分块两次，嵌入一次：系统性研究化学感知检索增强生成中的分段与表示权衡

发布时间：2025年06月13日

`RAG` `科学文献`

> Chunk Twice, Embed Once: A Systematic Study of Segmentation and Representation Trade-offs in Chemistry-Aware Retrieval-Augmented Generation

# 摘要

> 在化学等关键领域，检索增强生成（RAG）系统正成为应对海量科学文献的得力工具。尽管RAG潜力无限，但其核心设计要素——如文档的分段与表达方式——在特定领域内的研究仍显不足。本研究首次对化学领域RAG系统的分块策略和嵌入模型进行了大规模、系统化的评估。我们深入分析了涵盖五个方法家族的25种分块方案，并在三个化学专用基准测试中对48种嵌入模型进行了全面评估，其中包括新推出的QuestChemRetrieval数据集。研究发现，递归标记分块方法（尤其是R100-0）表现最为优异，且资源消耗极低。此外，我们发现经过优化的检索嵌入（如Nomic和Intfloat E5变体）显著优于SciBERT等专用领域模型。通过公开我们的数据集、评估框架和实证基准，我们为打造高效智能的化学感知RAG系统提供了切实可行的实践指南。

> Retrieval-Augmented Generation (RAG) systems are increasingly vital for navigating the ever-expanding body of scientific literature, particularly in high-stakes domains such as chemistry. Despite the promise of RAG, foundational design choices -- such as how documents are segmented and represented -- remain underexplored in domain-specific contexts. This study presents the first large-scale, systematic evaluation of chunking strategies and embedding models tailored to chemistry-focused RAG systems. We investigate 25 chunking configurations across five method families and evaluate 48 embedding models on three chemistry-specific benchmarks, including the newly introduced QuestChemRetrieval dataset. Our results reveal that recursive token-based chunking (specifically R100-0) consistently outperforms other approaches, offering strong performance with minimal resource overhead. We also find that retrieval-optimized embeddings -- such as Nomic and Intfloat E5 variants -- substantially outperform domain-specialized models like SciBERT. By releasing our datasets, evaluation framework, and empirical benchmarks, we provide actionable guidelines for building effective and efficient chemistry-aware RAG systems.

[Arxiv](https://arxiv.org/abs/2506.17277)