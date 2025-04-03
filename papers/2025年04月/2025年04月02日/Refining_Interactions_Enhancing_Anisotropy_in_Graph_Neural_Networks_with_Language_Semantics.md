# 优化交互：语言语义助力图神经网络增强各向异性

发布时间：2025年04月02日

`LLM理论

理由：这篇论文提出了一种新的框架LanSAGNN，结合了大型语言模型（LLMs）和图神经网络（GNNs），以改进LLMs在图任务中的性能。它探讨了如何通过定制的语义信息和双层微调架构来提升模型的有效性，属于方法论上的创新，因此归类为LLM理论。` `图神经网络`

> Refining Interactions: Enhancing Anisotropy in Graph Neural Networks with Language Semantics

# 摘要

> 大型语言模型（LLMs）与图神经网络（GNNs）的结合最近被提出用于增强文本属性图（TAGs）的能力。目前大多数方法直接将图结构或邻接节点的文本描述输入LLMs。然而，这些方法往往导致LLMs将结构信息简单地视为通用上下文文本，从而限制了其在图相关任务中的有效性。本文中，我们提出了LanSAGNN（语言语义各向异性图神经网络），一种将各向异性GNNs的概念扩展到自然语言层面的框架。该模型利用LLMs提取定制的语义信息，有效捕捉节点关系中的独特交互。此外，我们还提出了一种高效的双层LLMs微调架构，以更好地将LLMs的输出与图任务对齐。实验结果表明，LanSAGNN显著提升了现有基于LLMs的方法，同时并未增加复杂度，并且在面对干扰时也表现出强大的鲁棒性。

> The integration of Large Language Models (LLMs) with Graph Neural Networks (GNNs) has recently been explored to enhance the capabilities of Text Attribute Graphs (TAGs). Most existing methods feed textual descriptions of the graph structure or neighbouring nodes' text directly into LLMs. However, these approaches often cause LLMs to treat structural information simply as general contextual text, thus limiting their effectiveness in graph-related tasks. In this paper, we introduce LanSAGNN (Language Semantic Anisotropic Graph Neural Network), a framework that extends the concept of anisotropic GNNs to the natural language level. This model leverages LLMs to extract tailor-made semantic information for node pairs, effectively capturing the unique interactions within node relationships. In addition, we propose an efficient dual-layer LLMs finetuning architecture to better align LLMs' outputs with graph tasks. Experimental results demonstrate that LanSAGNN significantly enhances existing LLM-based methods without increasing complexity while also exhibiting strong robustness against interference.

[Arxiv](https://arxiv.org/abs/2504.01429)