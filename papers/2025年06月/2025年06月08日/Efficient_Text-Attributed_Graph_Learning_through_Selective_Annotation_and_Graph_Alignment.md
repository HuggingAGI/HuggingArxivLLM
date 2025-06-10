# 高效文本属性图学习：选择性标注与图对齐的结合

发布时间：2025年06月08日

`LLM应用

理由：该论文主要探讨了如何利用大型语言模型（LLMs）来增强图神经网络（GNNs）在文本属性图（TAGs）中的表现。虽然它涉及图结构和标注方法的创新，但核心在于应用LLMs来提升节点特征，属于LLM的应用场景。` `图神经网络` `图结构数据`

> Efficient Text-Attributed Graph Learning through Selective Annotation and Graph Alignment

# 摘要

> 在文本属性图（TAGs）领域，传统图神经网络（GNNs）常因节点复杂文本信息而表现不佳。近期研究通过大型语言模型（LLMs）增强节点特征，但这些方法需大量标注或微调，耗时费力。为解决这一难题，我们提出GAGA框架，通过标注少量代表性节点和边，大幅节省标注成本。GAGA构建标注图，捕捉关键标注间的拓扑关系，并借助两级对齐模块，将标注图与TAG深度结合。实验显示，GAGA在分类任务中表现优异，仅需标注1%的数据即可达到甚至超越现有最优方法的水平，充分彰显其高效性。

> In the realm of Text-attributed Graphs (TAGs), traditional graph neural networks (GNNs) often fall short due to the complex textual information associated with each node. Recent methods have improved node representations by leveraging large language models (LLMs) to enhance node text features, but these approaches typically require extensive annotations or fine-tuning across all nodes, which is both time-consuming and costly. To overcome these challenges, we introduce GAGA, an efficient framework for TAG representation learning. GAGA reduces annotation time and cost by focusing on annotating only representative nodes and edges. It constructs an annotation graph that captures the topological relationships among these annotations. Furthermore, GAGA employs a two-level alignment module to effectively integrate the annotation graph with the TAG, aligning their underlying structures. Experiments show that GAGA achieves classification accuracies on par with or surpassing state-of-the-art methods while requiring only 1% of the data to be annotated, demonstrating its high efficiency.

[Arxiv](https://arxiv.org/abs/2506.07168)