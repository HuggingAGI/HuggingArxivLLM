# 从社区到可解释的网络与词嵌入：一种统一的办法

发布时间：2024年12月11日

`Agent`

> From communities to interpretable network and word embedding: an unified approach

# 摘要

> 对诸如人类社会互动或语言中的词汇共现等复杂系统的信息进行建模，有助于理解这些系统的组织方式和运作机制。这类系统能够通过网络来建模，而网络理论提供了一系列实用的方法来对其加以分析。在这些方法当中，图嵌入是一种强有力的工具，能够在向量化的特征空间里总结网络的交互情况和拓扑结构。当用于机器学习算法的输入时，嵌入向量有助于解决诸如链路预测、图匹配之类的常见图问题。词嵌入旨在展现单词的含义，从大型文本语料库中提取出来。尽管嵌入算法输入的信息结构有所不同，但许多图嵌入方法是由自然语言处理（NLP）中的方法改编和启发而来的。在这两个领域都能看到这些方法的局限性。其中大多数方法都需要漫长且耗费大量资源的训练。大多数方法的另一个弊端是它们属于黑箱，要理解信息的结构方式相当复杂。模型的可解释性能够在无需外部信息的情况下理解向量空间的结构，从而更易于进行审查。鉴于这两个限制，我们提出了一个新颖的框架，以有效地将网络顶点嵌入到可解释的向量空间中。我们的低维二分框架（LDBGF）借助网络的二分投影，利用团来降低维度。连同 LDBGF，我们介绍了该框架的两个基于社区而非团的实现：SINr-NR 和 SINr-MF。我们表明，SINr-MF 在经典图上表现出色，SINr-NR 能够生成可解释且在多次运行中稳定的高质量图和词嵌入。

> Modelling information from complex systems such as humans social interaction or words co-occurrences in our languages can help to understand how these systems are organized and function. Such systems can be modelled by networks, and network theory provides a useful set of methods to analyze them. Among these methods, graph embedding is a powerful tool to summarize the interactions and topology of a network in a vectorized feature space. When used in input of machine learning algorithms, embedding vectors help with common graph problems such as link prediction, graph matching, etc. Word embedding has the goal of representing the sense of words, extracting it from large text corpora. Despite differences in the structure of information in input of embedding algorithms, many graph embedding approaches are adapted and inspired from methods in NLP. Limits of these methods are observed in both domains. Most of these methods require long and resource greedy training. Another downside to most methods is that they are black-box, from which understanding how the information is structured is rather complex. Interpretability of a model allows understanding how the vector space is structured without the need for external information, and thus can be audited more easily. With both these limitations in mind, we propose a novel framework to efficiently embed network vertices in an interpretable vector space. Our Lower Dimension Bipartite Framework (LDBGF) leverages the bipartite projection of a network using cliques to reduce dimensionality. Along with LDBGF, we introduce two implementations of this framework that rely on communities instead of cliques: SINr-NR and SINr-MF. We show that SINr-MF can perform well on classical graphs and SINr-NR can produce high-quality graph and word embeddings that are interpretable and stable across runs.

[Arxiv](https://arxiv.org/abs/2412.08187)