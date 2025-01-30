# 查询感知的可学习图池化标记：大型语言模型的提示新策略

发布时间：2025年01月29日

`LLM应用

理由：这篇论文探讨了将大型语言模型（LLM）应用于图结构数据的处理任务，提出了一种名为可学习图池化标记（LGPT）的方法，并展示了其在图表示和图嵌入生成中的应用。论文的核心在于利用LLM来处理图数据，并提出了具体的应用方法和技术改进，因此属于LLM应用的范畴。` `社交网络` `知识图谱`

> Query-Aware Learnable Graph Pooling Tokens as Prompt for Large Language Models

# 摘要

> # 摘要
图结构数据在社交网络、引文网络、常识推理图和知识图谱等领域中至关重要。尽管图神经网络已广泛应用于图处理，但近期研究探索了将大型语言模型融入图任务的新方法。本文提出了一种名为可学习图池化标记（LGPT）的创新方法，有效解决了节点级投影的可扩展性问题和图级投影中的信息丢失问题。LGPT通过引入可学习参数作为大型语言模型中的标记，巧妙平衡了细粒度与全局图信息，实现了灵活高效的图表示。此外，我们还提出了一种早期查询融合技术，在构建图表示前融合查询上下文，从而生成更有效的图嵌入。该方法在GraphQA基准测试中实现了4.13%的性能提升，且无需训练大型语言模型，显著提升了处理复杂文本属性图数据的能力。

> Graph-structured data plays a vital role in numerous domains, such as social networks, citation networks, commonsense reasoning graphs and knowledge graphs. While graph neural networks have been employed for graph processing, recent advancements have explored integrating large language models for graph-based tasks. In this paper, we propose a novel approach named Learnable Graph Pooling Token (LGPT), which addresses the limitations of the scalability issues in node-level projection and information loss in graph-level projection. LGPT enables flexible and efficient graph representation by introducing learnable parameters that act as tokens in large language models, balancing fine-grained and global graph information. Additionally, we investigate an Early Query Fusion technique, which fuses query context before constructing the graph representation, leading to more effective graph embeddings. Our method achieves a 4.13\% performance improvement on the GraphQA benchmark without training the large language model, demonstrating significant gains in handling complex textual-attributed graph data.

[Arxiv](https://arxiv.org/abs/2501.17549)