# RiemannGFM: 基于黎曼几何的图基础模型学习

发布时间：2025年02月05日

`LLM理论

理由：这篇论文主要探讨了如何利用大型语言模型（LLM）来处理图数据，并提出了一个新的预训练模型RiemannGFM。论文的核心在于理论上的创新，即通过结构词汇表和黎曼几何的结合来解决图数据的泛化问题。虽然涉及到了LLM的应用，但重点在于理论框架的构建和模型的预训练方法，因此更适合归类为LLM理论。` `图神经网络` `人工智能`

> RiemannGFM: Learning a Graph Foundation Model from Riemannian Geometry

# 摘要

> 基础模型开启了人工智能的新纪元，通过预训练单一模型，实现跨数据集的可迁移性。图神经网络擅长处理无处不在的非欧几里得结构——图数据，但泛化能力不足。因此，图基础模型备受关注，近期研究尝试利用大型语言模型。然而，现有研究多聚焦于文本属性图，而许多真实图缺乏丰富的文本属性。此外，为大型语言模型定制的序列图描述忽略了图的结构复杂性。这些局限引发了一个关键问题：能否超越大型语言模型，预训练一个通用模型来学习任何图的结构知识？在语言或视觉领域，答案是共享词汇表。我们发现图领域也存在共享子结构，从而为图基础模型开辟了新方向——结构词汇表。我们提出了一种简单而有效的树和环的结构词汇表，并探索了其与黎曼几何的内在联系。基于此，我们提出了通用预训练模型RiemannGFM。具体而言，我们首先构建了一个新的产品束，以涵盖词汇表的多样几何结构。然后，在该空间上堆叠黎曼层，无论特定图如何，结构词汇表都在黎曼流形中学习，实现跨领域可迁移性。大量实验验证了RiemannGFM在各种真实图上的卓越表现。

> The foundation model has heralded a new era in artificial intelligence, pretraining a single model to offer cross-domain transferability on different datasets. Graph neural networks excel at learning graph data, the omnipresent non-Euclidean structure, but often lack the generalization capacity. Hence, graph foundation model is drawing increasing attention, and recent efforts have been made to leverage Large Language Models. On the one hand, existing studies primarily focus on text-attributed graphs, while a wider range of real graphs do not contain fruitful textual attributes. On the other hand, the sequential graph description tailored for the Large Language Model neglects the structural complexity, which is a predominant characteristic of the graph. Such limitations motivate an important question: Can we go beyond Large Language Models, and pretrain a universal model to learn the structural knowledge for any graph? The answer in the language or vision domain is a shared vocabulary. We observe the fact that there also exist shared substructures underlying graph domain, and thereby open a new opportunity of graph foundation model with structural vocabulary. The key innovation is the discovery of a simple yet effective structural vocabulary of trees and cycles, and we explore its inherent connection to Riemannian geometry. Herein, we present a universal pretraining model, RiemannGFM. Concretely, we first construct a novel product bundle to incorporate the diverse geometries of the vocabulary. Then, on this constructed space, we stack Riemannian layers where the structural vocabulary, regardless of specific graph, is learned in Riemannian manifold offering cross-domain transferability. Extensive experiments show the effectiveness of RiemannGFM on a diversity of real graphs.

[Arxiv](https://arxiv.org/abs/2502.03251)