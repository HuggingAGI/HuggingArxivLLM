# 图到文本或图到标记：LLM 在图学习中的新视角

发布时间：2025年01月02日

`LLM应用

理由：这篇论文主要讨论了如何将图数据结构转换为文本表示，以便利用大型语言模型（LLMs）来处理和理解图。虽然涉及到图数据结构和LLMs的结合，但核心内容集中在如何应用LLMs来处理图数据，因此归类为“LLM应用”更为合适。` `图分析`

> Graph2text or Graph2token: A Perspective of Large Language Models for Graph Learning

# 摘要

> # 摘要
图作为一种表示不规则网络的数据结构，广泛应用于现实世界的诸多场景。传统方法通过直接建模图结构取得了显著成果，但图的不规则性也带来了瓶颈。为此，一种创新方案是将图转换为文本表示，从而借助大型语言模型（LLMs）的强大能力来处理和理解图。本文全面回顾了将LLMs应用于图的方法，统称为LLM4graph。其核心在于将图转换为文本，以便LLMs进行分析和理解。基于此，我们从转换角度提出了一种新的LLM4graph方法分类，将现有方法分为Graph2text和Graph2token两类，分别将图转换为文本或token作为LLMs的输入。我们还总结了转换过程中的四大挑战，以问题导向的方式系统梳理现有方法。此外，针对实际需求，我们为研究人员提供了在不同图和硬件条件下选择合适模型和LLMs的实用指南，并展望了LLM4graph的五大未来研究方向。

> Graphs are data structures used to represent irregular networks and are prevalent in numerous real-world applications. Previous methods directly model graph structures and achieve significant success. However, these methods encounter bottlenecks due to the inherent irregularity of graphs. An innovative solution is converting graphs into textual representations, thereby harnessing the powerful capabilities of Large Language Models (LLMs) to process and comprehend graphs. In this paper, we present a comprehensive review of methodologies for applying LLMs to graphs, termed LLM4graph. The core of LLM4graph lies in transforming graphs into texts for LLMs to understand and analyze. Thus, we propose a novel taxonomy of LLM4graph methods in the view of the transformation. Specifically, existing methods can be divided into two paradigms: Graph2text and Graph2token, which transform graphs into texts or tokens as the input of LLMs, respectively. We point out four challenges during the transformation to systematically present existing methods in a problem-oriented perspective. For practical concerns, we provide a guideline for researchers on selecting appropriate models and LLMs for different graphs and hardware constraints. We also identify five future research directions for LLM4graph.

[Arxiv](https://arxiv.org/abs/2501.01124)