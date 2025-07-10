# 从排序到集合选取：检索增强生成的转变

发布时间：2025年07月09日

`RAG` `问答系统` `信息检索`

> Shifting from Ranking to Set Selection for Retrieval Augmented Generation

# 摘要

> 在检索增强生成（RAG）中，检索不仅要确保单个段落的相关性，还要保证整体段落集合的全面性。现有的方法主要基于单个相关性对前k个段落进行重新排序，但在多跳问答中，这种方法往往无法满足复杂查询的信息需求。为此，我们提出了一种集合式的段落选择方法，并引入了SETR。SETR通过链式推理明确识别查询的信息需求，并选择一个最优的段落集合，这些段落共同满足这些需求。在多跳RAG基准上的实验表明，SETR在答案正确性和检索质量方面均优于现有的基于专有LLM的重新排序器和开源基线，为RAG系统中的传统重新排序器提供了一个有效且高效的替代方案。代码可在https://github.com/LGAI-Research/SetR获取。

> Retrieval in Retrieval-Augmented Generation(RAG) must ensure that retrieved passages are not only individually relevant but also collectively form a comprehensive set. Existing approaches primarily rerank top-k passages based on their individual relevance, often failing to meet the information needs of complex queries in multi-hop question answering. In this work, we propose a set-wise passage selection approach and introduce SETR, which explicitly identifies the information requirements of a query through Chain-of-Thought reasoning and selects an optimal set of passages that collectively satisfy those requirements. Experiments on multi-hop RAG benchmarks show that SETR outperforms both proprietary LLM-based rerankers and open-source baselines in terms of answer correctness and retrieval quality, providing an effective and efficient alternative to traditional rerankers in RAG systems. The code is available at https://github.com/LGAI-Research/SetR

[Arxiv](https://arxiv.org/abs/2507.06838)