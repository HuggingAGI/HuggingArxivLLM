# OSCAR：在线软压缩与重排序

发布时间：2025年03月17日

`RAG` `计算优化`

> OSCAR: Online Soft Compression And Reranking

# 摘要

> 检索增强生成（RAG）通过整合外部知识来提升大型语言模型（LLMs）的能力，从而提高准确性和相关性。然而，随着检索规模的扩大，扩展RAG流水线仍然面临高昂的计算成本。为了解决这一问题，我们提出了OSCAR，这是一种新型的基于查询的在线软压缩方法，能够在减少计算开销的同时保持性能。与传统的硬压缩方法（缩短检索到的文本）或软压缩方法（将文档离线映射到连续嵌入）不同，OSCAR在推理时动态压缩检索到的信息，从而消除存储开销并实现更高的压缩率。此外，我们将OSCAR扩展为同时执行重排序，进一步优化RAG流水线的效率。我们的实验表明，OSCAR实现了最先进的性能，推理速度提升了2-5倍，且对于参数规模从1B到24B的LLMs，准确率几乎没有下降。模型可在以下链接获取：https://huggingface.co/collections/naver/oscar-67d446a8e3a2551f57464295。

> Retrieval-Augmented Generation (RAG) enhances Large Language Models (LLMs) by integrating external knowledge, leading to improved accuracy and relevance. However, scaling RAG pipelines remains computationally expensive as retrieval sizes grow. To address this, we introduce OSCAR, a novel query-dependent online soft compression method that reduces computational overhead while preserving performance. Unlike traditional hard compression methods, which shorten retrieved texts, or soft compression approaches, which map documents to continuous embeddings offline, OSCAR dynamically compresses retrieved information at inference time, eliminating storage overhead and enabling higher compression rates. Additionally, we extend OSCAR to simultaneously perform reranking, further optimizing the efficiency of the RAG pipeline. Our experiments demonstrate state-of-the-art performance with a 2-5x speed-up in inference and minimal to no loss in accuracy for LLMs ranging from 1B to 24B parameters. The models are available at: https://huggingface.co/collections/naver/oscar-67d446a8e3a2551f57464295.

[Arxiv](https://arxiv.org/abs/2504.07109)