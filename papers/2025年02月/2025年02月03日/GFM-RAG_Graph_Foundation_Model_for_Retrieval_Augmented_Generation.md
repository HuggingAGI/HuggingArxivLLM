# GFM-RAG: 图基础模型助力检索增强生成

发布时间：2025年02月03日

`RAG

理由：这篇论文主要讨论了检索增强生成（RAG）的改进方法，特别是通过图增强的检索增强生成（GraphRAG）和提出的新型图基础模型（GFM-RAG）。论文的核心内容集中在如何通过图结构推理来提升RAG的性能，因此它属于RAG分类。` `知识图谱` `问答系统`

> GFM-RAG: Graph Foundation Model for Retrieval Augmented Generation

# 摘要

> # 摘要
检索增强生成（RAG）在将知识融入大型语言模型（LLMs）中表现出色。然而，传统RAG难以捕捉知识片段间的复杂关系，限制了其在多源知识整合的复杂推理中的表现。最近，图增强的检索增强生成（GraphRAG）通过构建图结构显式建模这些关系，提升了检索效率。尽管如此，图结构中的噪声和不完整性仍制约其性能。为此，我们提出了GFM-RAG，一种新型图基础模型（GFM），用于检索增强生成。GFM-RAG采用创新的图神经网络，通过图结构推理捕捉复杂的查询-知识关系。拥有8M参数的GFM在大规模数据集上进行了两阶段训练，涵盖60个知识图谱、14M三元组和700k文档。这使得GFM-RAG在性能和泛化能力上表现卓越，成为首个无需微调即可应用于未见数据集的图基础模型。在三个多跳QA数据集和七个特定领域RAG数据集上的实验表明，GFM-RAG在保持高效和符合神经缩放定律的同时，实现了最先进的性能，展现了其进一步优化的潜力。

> Retrieval-augmented generation (RAG) has proven effective in integrating knowledge into large language models (LLMs). However, conventional RAGs struggle to capture complex relationships between pieces of knowledge, limiting their performance in intricate reasoning that requires integrating knowledge from multiple sources. Recently, graph-enhanced retrieval augmented generation (GraphRAG) builds graph structure to explicitly model these relationships, enabling more effective and efficient retrievers. Nevertheless, its performance is still hindered by the noise and incompleteness within the graph structure. To address this, we introduce GFM-RAG, a novel graph foundation model (GFM) for retrieval augmented generation. GFM-RAG is powered by an innovative graph neural network that reasons over graph structure to capture complex query-knowledge relationships. The GFM with 8M parameters undergoes a two-stage training process on large-scale datasets, comprising 60 knowledge graphs with over 14M triples and 700k documents. This results in impressive performance and generalizability for GFM-RAG, making it the first graph foundation model applicable to unseen datasets for retrieval without any fine-tuning required. Extensive experiments on three multi-hop QA datasets and seven domain-specific RAG datasets demonstrate that GFM-RAG achieves state-of-the-art performance while maintaining efficiency and alignment with neural scaling laws, highlighting its potential for further improvement.

[Arxiv](https://arxiv.org/abs/2502.01113)