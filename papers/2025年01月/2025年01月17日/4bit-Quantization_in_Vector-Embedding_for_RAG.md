# RAG中的向量嵌入4位量化

发布时间：2025年01月17日

`RAG

理由：这篇论文主要讨论了检索增强生成（RAG）技术，并提出了使用4位量化技术来减少高维嵌入向量的内存占用，从而优化RAG系统的性能。论文的核心内容围绕RAG技术的改进和应用，因此应归类为RAG。` `信息检索`

> 4bit-Quantization in Vector-Embedding for RAG

# 摘要

> 检索增强生成（RAG）是一种极具潜力的技术，能够有效应对大型语言模型（LLMs）的两大局限：一是训练数据可能导致信息过时，二是模型可能生成事实不准确的响应，即所谓的“幻觉”。RAG通过利用高维空间中的嵌入向量存储相关文档数据库，旨在缓解这些问题。然而，高维嵌入的一个显著挑战是其内存占用巨大，尤其是在处理大规模文档数据库时。为此，我们提出使用4位量化技术存储嵌入向量，将精度从32位浮点数降至4位整数，从而大幅减少内存需求。这一方法不仅显著降低了高维向量数据库的内存占用，使得RAG系统在资源受限环境中更易部署，还因向量精度降低而加速了搜索过程。我们的代码已开源，详见https://github.com/taeheej/4bit-Quantization-in-Vector-Embedding-for-RAG。

> Retrieval-augmented generation (RAG) is a promising technique that has shown great potential in addressing some of the limitations of large language models (LLMs). LLMs have two major limitations: they can contain outdated information due to their training data, and they can generate factually inaccurate responses, a phenomenon known as hallucinations. RAG aims to mitigate these issues by leveraging a database of relevant documents, which are stored as embedding vectors in a high-dimensional space. However, one of the challenges of using high-dimensional embeddings is that they require a significant amount of memory to store. This can be a major issue, especially when dealing with large databases of documents. To alleviate this problem, we propose the use of 4-bit quantization to store the embedding vectors. This involves reducing the precision of the vectors from 32-bit floating-point numbers to 4-bit integers, which can significantly reduce the memory requirements. Our approach has several benefits. Firstly, it significantly reduces the memory storage requirements of the high-dimensional vector database, making it more feasible to deploy RAG systems in resource-constrained environments. Secondly, it speeds up the searching process, as the reduced precision of the vectors allows for faster computation. Our code is available at https://github.com/taeheej/4bit-Quantization-in-Vector-Embedding-for-RAG

[Arxiv](https://arxiv.org/abs/2501.10534)