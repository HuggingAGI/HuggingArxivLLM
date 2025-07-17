# LLMs能否发现欺诈者？多层级增强的 LLM 图欺诈检测

发布时间：2025年07月16日

`LLM应用

摘要讨论了如何将大型语言模型（LLMs）应用于图欺诈检测，提出了一种名为MLED的多级增强框架，结合文本信息和图结构，提升检测效果。这属于LLM的具体应用场景。` `欺诈检测`

> Can LLMs Find Fraudsters? Multi-level LLM Enhanced Graph Fraud Detection

# 摘要

> 图欺诈检测吸引了广泛关注，因为图神经网络（GNNs）在建模多模态数据中的复杂关系方面表现出色。然而，现有的图欺诈检测方法通常依赖预处理的节点嵌入和预定义的图结构来识别欺诈者，这种方法忽视了原始文本信息中蕴含的丰富语义线索。尽管大型语言模型（LLMs）在处理文本信息方面表现出色，但如何将处理后的文本嵌入与图结构进行有效融合仍是当前的重大挑战。本文中，我们提出了一种名为 MLED 的多级 LLM 增强图欺诈检测框架。在 MLED 框架中，我们利用 LLMs 从文本信息中提取外部知识，从而提升图欺诈检测的效果。为了将 LLMs 与图结构信息相结合，并提升区分欺诈者的能力，我们设计了一个多级 LLM 增强框架，其中包括类型级增强器和关系级增强器。前者旨在增强欺诈者与良性实体之间的差异，后者则提升欺诈者在不同关系中的重要性。在四个真实世界数据集上的实验结果表明，作为一款通用框架，MLED 在图欺诈检测中实现了领先性能，并且能够有效应用于现有方法。

> Graph fraud detection has garnered significant attention as Graph Neural Networks (GNNs) have proven effective in modeling complex relationships within multimodal data. However, existing graph fraud detection methods typically use preprocessed node embeddings and predefined graph structures to reveal fraudsters, which ignore the rich semantic cues contained in raw textual information. Although Large Language Models (LLMs) exhibit powerful capabilities in processing textual information, it remains a significant challenge to perform multimodal fusion of processed textual embeddings with graph structures. In this paper, we propose a \textbf{M}ulti-level \textbf{L}LM \textbf{E}nhanced Graph Fraud \textbf{D}etection framework called MLED. In MLED, we utilize LLMs to extract external knowledge from textual information to enhance graph fraud detection methods. To integrate LLMs with graph structure information and enhance the ability to distinguish fraudsters, we design a multi-level LLM enhanced framework including type-level enhancer and relation-level enhancer. One is to enhance the difference between the fraudsters and the benign entities, the other is to enhance the importance of the fraudsters in different relations. The experiments on four real-world datasets show that MLED achieves state-of-the-art performance in graph fraud detection as a generalized framework that can be applied to existing methods.

[Arxiv](https://arxiv.org/abs/2507.11997)