# HiChunk：基于层级分块的检索增强生成评估与增强

发布时间：2025年09月16日

`RAG` `基础理论`

> HiChunk: Evaluating and Enhancing Retrieval-Augmented Generation with Hierarchical Chunking

# 摘要

> 检索增强生成（RAG）技术通过整合外部知识源，有效提升了语言模型的响应能力。然而，文档分块作为RAG系统的关键环节，目前仍缺乏有效的评估工具。本文首先剖析了现有RAG评估基准无法有效评估文档分块质量的原因，核心问题在于证据稀疏性。基于此，我们提出了HiCBench基准，其中包含人工标注的多级文档分块点、合成的证据密集型问答（QA）对及其对应的证据来源。此外，我们还提出了HiChunk框架——一个基于微调LLM的多级文档结构化框架，该框架结合自动合并（Auto-Merge）检索算法以提升检索质量。实验结果显示，HiCBench能够有效评估不同分块方法对整个RAG流程的影响；同时，HiChunk在合理耗时内实现了更优的分块质量，进而提升了RAG系统的整体性能。

> Retrieval-Augmented Generation (RAG) enhances the response capabilities of language models by integrating external knowledge sources. However, document chunking as an important part of RAG system often lacks effective evaluation tools. This paper first analyzes why existing RAG evaluation benchmarks are inadequate for assessing document chunking quality, specifically due to evidence sparsity. Based on this conclusion, we propose HiCBench, which includes manually annotated multi-level document chunking points, synthesized evidence-dense quetion answer(QA) pairs, and their corresponding evidence sources. Additionally, we introduce the HiChunk framework, a multi-level document structuring framework based on fine-tuned LLMs, combined with the Auto-Merge retrieval algorithm to improve retrieval quality. Experiments demonstrate that HiCBench effectively evaluates the impact of different chunking methods across the entire RAG pipeline. Moreover, HiChunk achieves better chunking quality within reasonable time consumption, thereby enhancing the overall performance of RAG systems.

[Arxiv](https://arxiv.org/abs/2509.11552)