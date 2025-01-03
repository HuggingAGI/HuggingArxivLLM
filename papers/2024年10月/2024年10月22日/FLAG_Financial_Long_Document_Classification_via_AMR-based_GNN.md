# FLAG: 基于AMR图神经网络的金融长文档分类

发布时间：2024年10月22日

`LLM应用

理由：这篇论文主要讨论了如何利用大型语言模型（LLMs）和图神经网络（GNNs）结合抽象意义表示（AMR）来处理金融领域的长文档分类问题。虽然涉及了LLMs的应用，但重点在于如何通过AMR和GNNs来增强LLMs在金融文档分类中的表现。因此，这篇论文属于LLM应用的范畴。`

> FLAG: Financial Long Document Classification via AMR-based GNN

# 摘要

> 大型语言模型（LLMs）的兴起催生了对其在金融领域应用的广泛研究。然而，在处理长文档时，LLMs并未明确考虑语义关系，而是采用了完全或稀疏的注意力机制。近年来，抽象意义表示（AMR）取得了显著进展，它是一种基于图的文本表示方法，能够更好地保留语义关系。由于AMR能够在更深层次上捕捉语义，图神经网络（GNNs）可以充分利用它，构建基于LLM嵌入的文档级图表示，从而预测金融领域的目标指标。我们提出了FLAG：基于AMR的GNN进行金融长文档分类，这是一个基于AMR图的框架，用于生成长金融文档的文档级嵌入。我们从句子级AMR图构建文档级图，结合金融领域的专门LLM词嵌入，应用GNN进行深度学习，并验证了基于AMR的方法在预测长金融文档中目标数据方面的有效性。我们在多个经济部门的公司季度收益电话会议记录数据集以及S&P 1500综合指数中公司的最新收益电话会议语料库上进行了大量实验。结果表明，基于AMR的方法在预测不同时间范围内的股票价格趋势方面优于直接在文本上微调LLMs，并且优于之前利用文档图和GNNs进行文本分类的工作。

> The advent of large language models (LLMs) has initiated much research into their various financial applications. However, in applying LLMs on long documents, semantic relations are not explicitly incorporated, and a full or arbitrarily sparse attention operation is employed. In recent years, progress has been made in Abstract Meaning Representation (AMR), which is a graph-based representation of text to preserve its semantic relations. Since AMR can represent semantic relationships at a deeper level, it can be beneficially utilized by graph neural networks (GNNs) for constructing effective document-level graph representations built upon LLM embeddings to predict target metrics in the financial domain. We propose FLAG: Financial Long document classification via AMR-based GNN, an AMR graph based framework to generate document-level embeddings for long financial document classification. We construct document-level graphs from sentence-level AMR graphs, endow them with specialized LLM word embeddings in the financial domain, apply a deep learning mechanism that utilizes a GNN, and examine the efficacy of our AMR-based approach in predicting labeled target data from long financial documents. Extensive experiments are conducted on a dataset of quarterly earnings calls transcripts of companies in various sectors of the economy, as well as on a corpus of more recent earnings calls of companies in the S&P 1500 Composite Index. We find that our AMR-based approach outperforms fine-tuning LLMs directly on text in predicting stock price movement trends at different time horizons in both datasets. Our work also outperforms previous work utilizing document graphs and GNNs for text classification.

[Arxiv](https://arxiv.org/abs/2410.02024)