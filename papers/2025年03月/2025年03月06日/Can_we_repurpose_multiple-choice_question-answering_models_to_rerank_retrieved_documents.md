# 能不能把多项选择问答模型改造成用来重新排序检索到的文档呢？

发布时间：2025年03月06日

`RAG` `信息检索`

> Can we repurpose multiple-choice question-answering models to rerank retrieved documents?

# 摘要

> 将选择题问答模型（MCQA）用于文档重排序不仅可行，而且具有重要价值。这项研究基于MCQA决策与交叉编码器语义相关性评估的数学相似性，开发出了R*模型——一个结合这两种方法的验证性模型。R*以深度和精准度评估文档相关性，展示了如何将MCQA的原则应用于提升信息检索（IR）和检索增强生成（RAG）系统中的重排序性能。通过实验验证，R*证明了它可以提高检索准确性，并通过展示一个轻量级的MCQA重排序实际原型，为该领域的发展做出了贡献。

> Yes, repurposing multiple-choice question-answering (MCQA) models for document reranking is both feasible and valuable. This preliminary work is founded on mathematical parallels between MCQA decision-making and cross-encoder semantic relevance assessments, leading to the development of R*, a proof-of-concept model that harmonizes these approaches. Designed to assess document relevance with depth and precision, R* showcases how MCQA's principles can improve reranking in information retrieval (IR) and retrieval-augmented generation (RAG) systems -- ultimately enhancing search and dialogue in AI-powered systems. Through experimental validation, R* proves to improve retrieval accuracy and contribute to the field's advancement by demonstrating a practical prototype of MCQA for reranking by keeping it lightweight.

[Arxiv](https://arxiv.org/abs/2504.06276)