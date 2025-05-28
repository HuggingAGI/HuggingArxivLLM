# ReSCORE：无标签迭代式检索器训练方法，专为多跳问答设计，采用相关性与一致性监督机制

发布时间：2025年05月27日

`LLM应用` `问答系统` `信息检索`

> ReSCORE: Label-free Iterative Retriever Training for Multi-hop Question Answering with Relevance-Consistency Supervision

# 摘要

> 多跳问答（MHQA）需要在多个文档间进行推理，以解答复杂问题。相比稀疏方法（如BM25），密集检索器通常表现更优，因为它们能够利用语义嵌入。然而，密集检索器需要标注的查询-文档对进行微调，这对MHQA提出了巨大挑战，因为推理过程中查询（问题的重新表述）具有高度变异性。为解决这一问题，我们提出了ReSCORE（基于一致性和相关性的检索器监督方法），一种无需标注文档即可训练密集检索器的新方法。ReSCORE通过大规模语言模型，评估每个文档与问题的相关性以及与正确答案的一致性，并在迭代问答框架内利用这些评估结果来训练检索器。在三个MHQA基准上的实验结果表明，ReSCORE显著提升了检索性能，进而实现了当前最优的MHQA效果。我们的实现已开源，地址为：https://leeds1219.github.io/ReSCORE。

> Multi-hop question answering (MHQA) involves reasoning across multiple documents to answer complex questions. Dense retrievers typically outperform sparse methods like BM25 by leveraging semantic embeddings; however, they require labeled query-document pairs for fine-tuning. This poses a significant challenge in MHQA due to the high variability of queries (reformulated) questions throughout the reasoning steps. To overcome this limitation, we introduce Retriever Supervision with Consistency and Relevance (ReSCORE), a novel method for training dense retrievers for MHQA without labeled documents. ReSCORE leverages large language models to capture each documents relevance to the question and consistency with the correct answer and use them to train a retriever within an iterative question-answering framework. Experiments on three MHQA benchmarks demonstrate the effectiveness of ReSCORE, with significant improvements in retrieval, and in turn, the state-of-the-art MHQA performance. Our implementation is available at: https://leeds1219.github.io/ReSCORE.

[Arxiv](https://arxiv.org/abs/2505.21250)