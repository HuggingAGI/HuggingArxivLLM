# FB-RAG：优化RAG的双向查找方法

发布时间：2025年05月22日

`RAG` `信息检索` `生成技术`

> FB-RAG: Improving RAG with Forward and Backward Lookup

# 摘要

> 检索增强生成（RAG）系统的性能受检索器质量和检索上下文大小的影响很大。足够大的上下文确保了LLM输入中包含相关信息，但也引入了可能混淆模型的无关内容。而较小的上下文虽然减少了无关信息，却可能丢失回答问题所需的关键信息。这种权衡在处理复杂查询时尤为棘手，因为这些查询往往缺乏足够的信息来从完整上下文中提取相关片段。为此，我们提出了一种名为FB-RAG的新框架，通过结合反向查找（与查询重叠）和正向查找（与候选答案重叠）来优化RAG流程，从而精准检索出最相关的上下文片段以回答问题。我们在9个数据集上的实验证明，FB-RAG在性能上显著优于现有RAG和长上下文基线模型。此外，它还能在提升性能的同时减少延迟。通过对方法的优缺点进行深入分析，我们为未来研究提供了有价值的见解。

> The performance of Retrieval Augmented Generation (RAG) systems relies heavily on the retriever quality and the size of the retrieved context. A large enough context ensures that the relevant information is present in the input context for the LLM, but also incorporates irrelevant content that has been shown to confuse the models. On the other hand, a smaller context reduces the irrelevant information, but it often comes at the risk of losing important information necessary to answer the input question. This duality is especially challenging to manage for complex queries that contain little information to retrieve the relevant chunks from the full context. To address this, we present a novel framework, called FB-RAG, which enhances the RAG pipeline by relying on a combination of backward lookup (overlap with the query) and forward lookup (overlap with candidate reasons and answers) to retrieve specific context chunks that are the most relevant for answering the input query. Our evaluations on 9 datasets from two leading benchmarks show that FB-RAG consistently outperforms RAG and Long Context baselines developed recently for these benchmarks. We further show that FB-RAG can improve performance while reducing latency. We perform qualitative analysis of the strengths and shortcomings of our approach, providing specific insights to guide future work.

[Arxiv](https://arxiv.org/abs/2505.17206)