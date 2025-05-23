# # HASH-RAG：连接深度哈希与检索器，实现高效、精细的检索与增强生成

发布时间：2025年05月21日

`RAG` `问答系统`

> HASH-RAG: Bridging Deep Hashing with Retriever for Efficient, Fine Retrieval and Augmented Generation

# 摘要

> 在扩展到大规模知识库时，检索增强生成（RAG）面临着保持上下文相关性的同时提升效率的挑战。我们提出的Hash-RAG框架，通过深度哈希技术与系统性优化的结合，成功解决了这一难题。该框架直接从知识库代码中学习二进制哈希码，避免了中间特征提取步骤，从而大幅降低了存储和计算开销。在此基础上，我们构建了一个高效的哈希检索框架，并进一步开发了细粒度分块的基础。为此，我们设计了一个基于提示的分块到上下文（PGCC）模块，通过提示工程，该模块能够有效利用检索到的哈希索引命题及其原始文档片段，显著提升了LLM的上下文感知能力。实验结果表明，在NQ、TriviaQA和HotpotQA数据集上，我们的方法使检索时间减少了90%，同时保持了良好的召回性能。此外，与现有基线相比，该系统在EM分数上提升了1.4-4.3%。

> Retrieval-Augmented Generation (RAG) encounters efficiency challenges when scaling to massive knowledge bases while preserving contextual relevance. We propose Hash-RAG, a framework that integrates deep hashing techniques with systematic optimizations to address these limitations. Our queries directly learn binary hash codes from knowledgebase code, eliminating intermediate feature extraction steps, and significantly reducing storage and computational overhead. Building upon this hash-based efficient retrieval framework, we establish the foundation for fine-grained chunking. Consequently, we design a Prompt-Guided Chunk-to-Context (PGCC) module that leverages retrieved hash-indexed propositions and their original document segments through prompt engineering to enhance the LLM's contextual awareness. Experimental evaluations on NQ, TriviaQA, and HotpotQA datasets demonstrate that our approach achieves a 90% reduction in retrieval time compared to conventional methods while maintaining considerate recall performance. Additionally, The proposed system outperforms retrieval/non-retrieval baselines by 1.4-4.3% in EM scores.

[Arxiv](https://arxiv.org/abs/2505.16133)