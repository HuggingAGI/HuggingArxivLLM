# 文档段落分割：助力抽取式问答

发布时间：2025年01月16日

`RAG

理由：这篇论文主要讨论了检索增强生成（RAG）中的分块过程，并提出了一个新的框架（LGMGC）来优化这一过程。由于RAG是论文的核心主题，并且论文的重点是改进RAG流程中的分块方法，因此将其分类为RAG是合适的。` `信息检索`

> Passage Segmentation of Documents for Extractive Question Answering

# 摘要

> 检索增强生成（RAG）在开放域问答中表现出色，但其中的分块过程却常被忽视。本研究聚焦分块在提升密集段落检索和端到端RAG流程性能中的关键作用，并提出了Logits-Guided Multi-Granular Chunker（LGMGC）这一创新框架。LGMGC能够将长文档智能分割为不同粒度的自包含分块。实验结果显示，LGMGC不仅优化了检索步骤，而且在RAG流程中超越了现有分块方法。

> Retrieval-Augmented Generation (RAG) has proven effective in open-domain question answering. However, the chunking process, which is essential to this pipeline, often receives insufficient attention relative to retrieval and synthesis components. This study emphasizes the critical role of chunking in improving the performance of both dense passage retrieval and the end-to-end RAG pipeline. We then introduce the Logits-Guided Multi-Granular Chunker (LGMGC), a novel framework that splits long documents into contextualized, self-contained chunks of varied granularity. Our experimental results, evaluated on two benchmark datasets, demonstrate that LGMGC not only improves the retrieval step but also outperforms existing chunking methods when integrated into a RAG pipeline.

[Arxiv](https://arxiv.org/abs/2501.09940)