# 超越块和图：通过三元组驱动的思考实现检索增强生成

发布时间：2025年08月04日

`RAG` `人工智能` `智能对话系统`

> Beyond Chunks and Graphs: Retrieval-Augmented Generation through Triplet-Driven Thinking

# 摘要

> 检索增强生成（RAG）对于减少大型语言模型中的幻觉现象以及整合外部知识至关重要。然而，先进的RAG系统在性能与效率之间面临着权衡。多轮RAG方法虽然推理能力强，但会导致过多的LLM调用和高昂的token成本；而基于图的RAG方法则面临计算成本高昂、容易出错的图构建问题以及检索冗余的困扰。为了解决这些问题，我们提出了一种名为T$^2$RAG的新型框架，该框架基于简单的、无图的知识库，该知识库存储了原子三元组。T$^2$RAG通过LLM将问题分解为可搜索的三元组，并包含占位符，然后通过从三元组数据库中检索证据来逐步解决这些占位符。实验结果表明，T$^2$RAG在六个数据集上平均性能提升了11%，同时将检索成本降低了45%，显著超越了现有的多轮和图RAG方法。我们的代码可在https://github.com/rockcor/T2RAG上获取。

> Retrieval-augmented generation (RAG) is critical for reducing hallucinations and incorporating external knowledge into Large Language Models (LLMs). However, advanced RAG systems face a trade-off between performance and efficiency. Multi-round RAG approaches achieve strong reasoning but incur excessive LLM calls and token costs, while Graph RAG methods suffer from computationally expensive, error-prone graph construction and retrieval redundancy. To address these challenges, we propose T$^2$RAG, a novel framework that operates on a simple, graph-free knowledge base of atomic triplets. T$^2$RAG leverages an LLM to decompose questions into searchable triplets with placeholders, which it then iteratively resolves by retrieving evidence from the triplet database. Empirical results show that T$^2$RAG significantly outperforms state-of-the-art multi-round and Graph RAG methods, achieving an average performance gain of up to 11\% across six datasets while reducing retrieval costs by up to 45\%. Our code is available at https://github.com/rockcor/T2RAG

[Arxiv](https://arxiv.org/abs/2508.02435)