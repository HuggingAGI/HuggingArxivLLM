# 你好，世界！：让 GNN 与 LLM 携手交流

发布时间：2025年05月27日

`LLM应用

理由：这篇论文探讨了将大型语言模型（LLMs）应用于图神经网络（GNNs）中，提出了一种新的图语言网络（GLN），并展示了其在节点分类和链路预测任务中的应用效果。因此，它属于LLM应用类别。` `人工智能` `数据科学`

> 'Hello, World!': Making GNNs Talk with LLMs

# 摘要

> 图神经网络（GNNs）在各类图相关任务中表现卓越，但其高维隐藏表示使其成为不透明的黑箱模型。本研究提出了一种基于大型语言模型（LLMs）的图神经网络——图语言网络（GLN），其隐藏表示以人类可读的文本形式呈现。通过精心设计的提示词，GLN不仅集成了GNN的消息传递模块，还引入了包括图注意力机制和初始残差连接在内的高级GNN技术。GLN隐藏表示的可解释性使得我们能够直观分析节点表示在（1）不同层级间的变化，以及（2）在高级GNN技术下的演变，从而揭示GNN的内在工作机制。此外，我们还展示了GLN在节点分类和链路预测任务中具备强大的零样本性能，超越现有的基于LLM的基线方法。

> While graph neural networks (GNNs) have shown remarkable performance across diverse graph-related tasks, their high-dimensional hidden representations render them black boxes. In this work, we propose Graph Lingual Network (GLN), a GNN built on large language models (LLMs), with hidden representations in the form of human-readable text. Through careful prompt design, GLN incorporates not only the message passing module of GNNs but also advanced GNN techniques, including graph attention and initial residual connection. The comprehensibility of GLN's hidden representations enables an intuitive analysis of how node representations change (1) across layers and (2) under advanced GNN techniques, shedding light on the inner workings of GNNs. Furthermore, we demonstrate that GLN achieves strong zero-shot performance on node classification and link prediction, outperforming existing LLM-based baseline methods.

[Arxiv](https://arxiv.org/abs/2505.20742)