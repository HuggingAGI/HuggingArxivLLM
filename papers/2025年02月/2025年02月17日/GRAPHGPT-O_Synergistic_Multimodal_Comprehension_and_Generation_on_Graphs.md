# GRAPHGPT-O：基于图的协同多模态理解和生成

发布时间：2025年02月17日

`LLM应用

摘要讨论了多模态大型语言模型的应用，提出了一种新方法来处理多模态数据，属于LLM的应用层面。` `人工智能` `图计算`

> GRAPHGPT-O: Synergistic Multimodal Comprehension and Generation on Graphs

# 摘要

> 多模态大型语言模型（MLLMs）的快速发展推动了文本与图像等多种模态在大型语言模型（LLM）框架内的深度整合。然而，文本与图像间通常存在复杂关联，形成多模态属性图（MMAG）。当前研究尚未充分探索MLLMs如何在MMAG中有效融合关系信息（即图结构）与语义信息（即文本和图像），以实现更高效的多模态理解和生成。为此，我们提出GraphGPT-o，旨在支持在MMAG上实现全模态理解和创作。我们的研究分为三个主要部分：首先，全面探索了多种线性化变体，以将语义与结构信息有效转化为MLLMs的输入形式；其次，提出了一种创新的分层对齐器，实现深度图编码，成功弥合了MMAG与MLLMs之间的技术鸿沟；最后，深入研究了推理选择机制，使MLLMs能够适应图场景中交错的文本与图像生成需求。通过在不同领域的三个数据集上进行的广泛实验，我们验证了所提方法的有效性。相关数据集和代码将在论文正式接收后开放共享。

> The rapid development of Multimodal Large Language Models (MLLMs) has enabled the integration of multiple modalities, including texts and images, within the large language model (LLM) framework. However, texts and images are usually interconnected, forming a multimodal attributed graph (MMAG). It is underexplored how MLLMs can incorporate the relational information (\textit{i.e.}, graph structure) and semantic information (\textit{i.e.,} texts and images) on such graphs for multimodal comprehension and generation. In this paper, we propose GraphGPT-o, which supports omni-multimodal understanding and creation on MMAGs. We first comprehensively study linearization variants to transform semantic and structural information as input for MLLMs. Then, we propose a hierarchical aligner that enables deep graph encoding, bridging the gap between MMAGs and MLLMs. Finally, we explore the inference choices, adapting MLLM to interleaved text and image generation in graph scenarios. Extensive experiments on three datasets from different domains demonstrate the effectiveness of our proposed method. Datasets and codes will be open-sourced upon acceptance.

[Arxiv](https://arxiv.org/abs/2502.11925)