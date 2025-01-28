# ASRank: 基于答案线索的零-shot 文档检索重排序

发布时间：2025年01月25日

`RAG

理由：这篇论文主要讨论了检索增强生成（RAG）模型在开放域问答领域的应用，并提出了一种新的重排序方法ASRank来提升检索文档的质量。论文的核心内容围绕RAG模型的改进和应用展开，因此应归类为RAG。` `信息检索` `问答系统`

> ASRank: Zero-Shot Re-Ranking with Answer Scent for Document Retrieval

# 摘要

> 检索增强生成（RAG）模型在开放域问答领域备受瞩目。RAG的效果高度依赖于检索文档的质量，但传统方法往往难以将最相关的文档排在前列。本文提出了一种名为ASRank的新重排序方法，它利用零-shot答案线索对检索文档进行评分，并通过预训练的大型语言模型计算文档答案与线索的匹配概率。实验表明，ASRank在NQ、TriviaQA、WebQA等多个数据集上表现优异，尤其是在NQ上，Top-1准确率从$19.2\%$提升至$46.5\%$（MSS）和$22.1\%$提升至$47.3\%$（BM25）。与现有方法相比，ASRank在多个数据集上的检索性能显著领先（ASRank的47.3 Top-1 vs BM25的UPR的35.4）。

> Retrieval-Augmented Generation (RAG) models have drawn considerable attention in modern open-domain question answering. The effectiveness of RAG depends on the quality of the top retrieved documents. However, conventional retrieval methods sometimes fail to rank the most relevant documents at the top. In this paper, we introduce ASRank, a new re-ranking method based on scoring retrieved documents using zero-shot answer scent which relies on a pre-trained large language model to compute the likelihood of the document-derived answers aligning with the answer scent. Our approach demonstrates marked improvements across several datasets, including NQ, TriviaQA, WebQA, ArchivalQA, HotpotQA, and Entity Questions. Notably, ASRank increases Top-1 retrieval accuracy on NQ from $19.2\%$ to $46.5\%$ for MSS and $22.1\%$ to $47.3\%$ for BM25. It also shows strong retrieval performance on several datasets compared to state-of-the-art methods (47.3 Top-1 by ASRank vs 35.4 by UPR by BM25).

[Arxiv](https://arxiv.org/abs/2501.15245)