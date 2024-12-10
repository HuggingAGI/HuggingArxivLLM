# SiReRAG：为多跳推理进行相似及相关信息的索引

发布时间：2024年12月08日

`RAG` `多跳推理`

> SiReRAG: Indexing Similar and Related Information for Multihop Reasoning

# 摘要

> 索引是检索增强生成（RAG）系统取得出色性能的关键一步。然而，现有的方法要么依据语义相似性（相似性），要么依据相关信息（相关性）来组织数据，却未能全面兼顾这两方面。我们的分析显示，仅对一个方面进行建模会造成知识综合不充分，致使在需要多跳推理的复杂任务中表现欠佳。在本文中，我们提出了 SiReRAG，这是一种全新的 RAG 索引方法，明确兼顾了相似和相关信息。在相似性方面，我们参照现有工作并探索一些变化，基于递归总结构建相似性树。在相关性方面，SiReRAG 从文本中提取命题和实体，通过共享实体对命题分组，并生成递归总结构建相关性树。我们把相似性和相关性树都索引并展平到一个统一的检索池中。我们的实验表明，SiReRAG 在三个多跳数据集（MuSiQue、2WikiMultiHopQA 和 HotpotQA）上始终优于前沿的索引方法，F1 分数平均提高 1.9％。作为一种颇为有效的解决方案，SiReRAG 显著提升了现有的重排序方法，平均 F1 分数最高提高 7.8％。

> Indexing is an important step towards strong performance in retrieval-augmented generation (RAG) systems. However, existing methods organize data based on either semantic similarity (similarity) or related information (relatedness), but do not cover both perspectives comprehensively. Our analysis reveals that modeling only one perspective results in insufficient knowledge synthesis, leading to suboptimal performance on complex tasks requiring multihop reasoning. In this paper, we propose SiReRAG, a novel RAG indexing approach that explicitly considers both similar and related information. On the similarity side, we follow existing work and explore some variances to construct a similarity tree based on recursive summarization. On the relatedness side, SiReRAG extracts propositions and entities from texts, groups propositions via shared entities, and generates recursive summaries to construct a relatedness tree. We index and flatten both similarity and relatedness trees into a unified retrieval pool. Our experiments demonstrate that SiReRAG consistently outperforms state-of-the-art indexing methods on three multihop datasets (MuSiQue, 2WikiMultiHopQA, and HotpotQA), with an average 1.9% improvement in F1 scores. As a reasonably efficient solution, SiReRAG enhances existing reranking methods significantly, with up to 7.8% improvement in average F1 scores.

[Arxiv](https://arxiv.org/abs/2412.06206)