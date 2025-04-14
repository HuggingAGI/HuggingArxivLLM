# PCA-RAG：通过主成分分析实现高效检索增强生成

发布时间：2025年04月11日

`RAG` `金融科技`

> PCA-RAG: Principal Component Analysis for Efficient Retrieval-Augmented Generation

# 摘要

> 检索增强生成（RAG）已成为一种强大的范式，用于将大型语言模型与外部知识源相结合，显著提升了智能体响应的精确性。然而，高维语言模型嵌入（通常在数百到数千维度之间）在存储和延迟方面可能带来可扩展性挑战，尤其是在处理海量金融文本语料库时。本文研究了使用主成分分析（PCA）来降低嵌入维度，从而缓解计算瓶颈，同时不会造成较大的准确性损失。我们采用真实世界数据集进行了实验，并在全维和PCA压缩嵌入下，比较了不同的相似性和距离度量。实验结果表明，将向量从3,072维降至110维，检索操作速度提升了高达【数学公式】倍，索引大小减少了【数学公式】倍，与基于人工标注的相似性评分相比，相关性指标仅出现了适度下降。这些发现表明，基于PCA的压缩方法在检索保真度和资源效率之间提供了一种可行的平衡，这对于实时系统（如Zanista AI的	extit{Newswitch}平台）至关重要。最终，我们的研究强调了在金融和交易等知识密集型领域，通过利用经典降维技术来扩展RAG架构的实用性，这些领域需要在速度、内存效率和准确性之间进行联合优化。

> Retrieval-Augmented Generation (RAG) has emerged as a powerful paradigm for grounding large language models in external knowledge sources, improving the precision of agents responses. However, high-dimensional language model embeddings, often in the range of hundreds to thousands of dimensions, can present scalability challenges in terms of storage and latency, especially when processing massive financial text corpora. This paper investigates the use of Principal Component Analysis (PCA) to reduce embedding dimensionality, thereby mitigating computational bottlenecks without incurring large accuracy losses. We experiment with a real-world dataset and compare different similarity and distance metrics under both full-dimensional and PCA-compressed embeddings. Our results show that reducing vectors from 3,072 to 110 dimensions provides a sizeable (up to $60\times$) speedup in retrieval operations and a $\sim 28.6\times$ reduction in index size, with only moderate declines in correlation metrics relative to human-annotated similarity scores. These findings demonstrate that PCA-based compression offers a viable balance between retrieval fidelity and resource efficiency, essential for real-time systems such as Zanista AI's \textit{Newswitch} platform. Ultimately, our study underscores the practicality of leveraging classical dimensionality reduction techniques to scale RAG architectures for knowledge-intensive applications in finance and trading, where speed, memory efficiency, and accuracy must jointly be optimized.

[Arxiv](https://arxiv.org/abs/2504.08386)