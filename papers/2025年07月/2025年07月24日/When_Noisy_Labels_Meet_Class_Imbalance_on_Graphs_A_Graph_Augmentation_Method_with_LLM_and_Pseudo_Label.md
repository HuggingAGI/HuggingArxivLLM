# 噪声标签与图类别不平衡的相遇：LLM与伪标签驱动的图增强方法

发布时间：2025年07月24日

`LLM应用` `图数据` `数据处理`

> When Noisy Labels Meet Class Imbalance on Graphs: A Graph Augmentation Method with LLM and Pseudo Label

# 摘要

> 类别不平衡的图节点分类是一个实用但尚未充分探索的研究问题。尽管近期研究试图解决这一问题，但他们通常假设在处理类别不平衡图时标签是干净且可靠的。这一假设常常与现实世界图的性质相悖，因为标签中经常包含噪声。鉴于这一研究空白，本文系统性地研究了具有噪声标签的类别不平衡图上的鲁棒节点分类问题。我们提出了GraphALP，一个基于大型语言模型（LLMs）和伪标签技术的新型图增强框架。具体来说，我们设计了一种基于LLMs的过采样方法来生成合成少数节点，从而产生标签准确的少数节点以缓解类别不平衡问题。在类别平衡的图基础上，我们开发了一种动态加权的伪标签方法，以获得高置信度的伪标签从而降低标签噪声比例。此外，我们还实现了一种二次LLM引导的过采样机制，以缓解伪标签可能引起的潜在类别分布偏斜。实验结果表明，GraphALP在具有噪声标签的类别不平衡图上优于现有最优方法。

> Class-imbalanced graph node classification is a practical yet underexplored research problem. Although recent studies have attempted to address this issue, they typically assume clean and reliable labels when processing class-imbalanced graphs. This assumption often violates the nature of real-world graphs, where labels frequently contain noise. Given this gap, this paper systematically investigates robust node classification for class-imbalanced graphs with noisy labels. We propose GraphALP, a novel Graph Augmentation framework based on Large language models (LLMs) and Pseudo-labeling techniques. Specifically, we design an LLM-based oversampling method to generate synthetic minority nodes, producing label-accurate minority nodes to alleviate class imbalance. Based on the class-balanced graphs, we develop a dynamically weighted pseudo-labeling method to obtain high-confidence pseudo labels to reduce label noise ratio. Additionally, we implement a secondary LLM-guided oversampling mechanism to mitigate potential class distribution skew caused by pseudo labels. Experimental results show that GraphALP achieves superior performance over state-of-the-art methods on class-imbalanced graphs with noisy labels.

[Arxiv](https://arxiv.org/abs/2507.18153)