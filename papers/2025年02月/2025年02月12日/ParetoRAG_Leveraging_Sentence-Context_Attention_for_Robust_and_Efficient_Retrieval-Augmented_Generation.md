# ParetoRAG：基于句子上下文注意力机制的健壮高效检索增强生成

发布时间：2025年02月12日

`RAG` `生成技术` `知识图谱`

> ParetoRAG: Leveraging Sentence-Context Attention for Robust and Efficient Retrieval-Augmented Generation

# 摘要

> 检索增强生成（RAG）系统通过整合外部知识来提升大型语言模型（LLMs）的能力，但它们仍然面临检索效率低下和模型无法有效过滤无关信息的持续挑战。我们提出了ParetoRAG，一个基于帕累托法则的无监督框架，通过句子级优化来提升RAG系统的性能。ParetoRAG将段落分解为句子，并在保持上下文连贯性的同时动态调整核心内容的权重，从而在不额外训练或使用API资源的情况下，实现了检索精度和生成质量的双重提升。这一框架已在多种数据集、LLMs和检索器上得到了实证验证。

> While Retrieval-Augmented Generation (RAG) systems enhance Large Language Models (LLMs) by incorporating external knowledge, they still face persistent challenges in retrieval inefficiency and the inability of LLMs to filter out irrelevant information. We present ParetoRAG, an unsupervised framework that optimizes RAG systems through sentence-level refinement guided by the Pareto principle. By decomposing paragraphs into sentences and dynamically re-weighting core content while preserving contextual coherence, ParetoRAG achieves dual improvements in both retrieval precision and generation quality without requiring additional training or API resources. This framework has been empirically validated across various datasets, LLMs, and retrievers.

[Arxiv](https://arxiv.org/abs/2502.08178)