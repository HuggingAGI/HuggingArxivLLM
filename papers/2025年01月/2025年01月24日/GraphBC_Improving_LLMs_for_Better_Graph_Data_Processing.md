# GraphBC: 提升LLMs在图数据处理中的表现

发布时间：2025年01月24日

`LLM应用

理由：这篇论文主要讨论了如何将大型语言模型（LLMs）应用于图相关任务，并提出了一种新的模型框架GraphBC来解决现有方法中的问题。论文的重点在于如何通过改进LLMs的输入和推理过程来提升其在图任务中的性能，这属于LLM在实际应用中的改进和优化，因此分类为LLM应用。` `图数据处理`

> GraphBC: Improving LLMs for Better Graph Data Processing

# 摘要

> 大型语言模型（LLMs）在各领域的成功促使研究人员将其应用于图相关任务，通过将图数据转换为自然语言文本。然而，自然语言具有顺序性，而图数据则不然。我们发现，当图中节点或边的顺序在自然语言描述中被打乱时，尽管描述的是同一个图，模型性能却会在高性能和随机猜测之间波动。此外，由于LLMs的输入上下文长度有限，现有方法通常随机采样目标节点的邻居作为其邻域的代表，这可能并不总是有助于准确推理。为解决这些问题，我们提出了GraphBC。这一新颖的模型框架包含一个顺序选择器模块，用于确保图的正确序列化顺序，以及一个子图采样模块，用于采样结构更优的子图以提升推理效果。我们还通过蒸馏提出了Graph CoT，并通过指令调优增强了LLM在图任务中的推理和零-shot学习能力。在多个数据集上的节点分类和图问答实验表明，GraphBC显著提升了LLMs在图任务中的性能和泛化能力。

> The success of Large Language Models (LLMs) in various domains has led researchers to apply them to graph-related problems by converting graph data into natural language text. However, unlike graph data, natural language inherently has sequential order. We observe that when the order of nodes or edges in the natural language description of a graph is shuffled, despite describing the same graph, model performance fluctuates between high performance and random guessing. Additionally, due to the limited input context length of LLMs, current methods typically randomly sample neighbors of target nodes as representatives of their neighborhood, which may not always be effective for accurate reasoning. To address these gaps, we introduce GraphBC. This novel model framework features an Order Selector Module to ensure proper serialization order of the graph and a Subgraph Sampling Module to sample subgraphs with better structure for better reasoning. Furthermore, we propose Graph CoT obtained through distillation, and enhance LLM's reasoning and zero-shot learning capabilities for graph tasks through instruction tuning. Experiments on multiple datasets for node classification and graph question-answering demonstrate that GraphBC improves LLMs' performance and generalization ability on graph tasks.

[Arxiv](https://arxiv.org/abs/2501.14427)