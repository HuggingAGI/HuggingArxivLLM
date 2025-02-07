# 受大脑启发的稀疏训练让Transformers和LLMs也能像全连接网络一样高效运行。

发布时间：2025年01月31日

`其他

**理由：**
这篇论文主要讨论了脑启发网络科学原理在训练稀疏连接人工神经网络（ANNs）中的应用，特别是动态稀疏训练（DST）和Cannistraci-Hebb训练（CHT）的改进方法。虽然提到了Transformer机器翻译任务和语言建模，但论文的核心内容并不直接涉及大型语言模型（LLM）的理论、应用、Agent或RAG（Retrieval-Augmented Generation）技术。因此，将其分类为“其他”更为合适。` `人工智能` `神经网络`

> Brain-inspired sparse training enables Transformers and LLMs to perform as fully connected

# 摘要

> # 摘要
本研究旨在拓展脑启发网络科学原理在训练稀疏连接人工神经网络（ANNs）中的应用。动态稀疏训练（DST）虽能降低ANNs的计算负担，但在高稀疏度下保持性能仍具挑战。Cannistraci-Hebb训练（CHT）作为一种脑启发方法，通过无梯度、拓扑驱动的链接再生，在超稀疏（1%连接或更低）条件下展现出优于全连接网络的性能。然而，CHT存在两大局限：（i）其O(Nd^3)的时间复杂度限制了其仅适用于超稀疏网络；（ii）早期训练阶段选择高预测分数链接的策略不适用于连接不稳定的网络。为此，我们提出了一种GPU友好的CH链接预测器近似方法，将计算复杂度降至O(N^3)，实现了CHT在大规模模型中的快速应用。我们还引入了Cannistraci-Hebb训练软规则（CHTs），在链接移除与再生中采用采样策略，平衡网络拓扑的探索与利用。为进一步提升性能，我们将CHTs与Sigmoid渐进密度衰减（CHTss）结合。实验结果显示，仅用1%的连接，CHTs在视觉分类任务的MLP上便超越全连接网络，部分网络节点压缩至<30%。使用5%的连接，CHTss在两个Transformer机器翻译任务中表现更优。而30%的连接下，CHTss在语言建模中不仅优于其他动态稀疏训练方法，还在零-shot评估中超越了全连接网络。

> This study aims to enlarge our current knowledge on application of brain-inspired network science principles for training artificial neural networks (ANNs) with sparse connectivity. Dynamic sparse training (DST) can reduce the computational demands in ANNs, but faces difficulties to keep peak performance at high sparsity levels. The Cannistraci-Hebb training (CHT) is a brain-inspired method for growing connectivity in DST. CHT leverages a gradient-free, topology-driven link regrowth, which has shown ultra-sparse (1% connectivity or lower) advantage across various tasks compared to fully connected networks. Yet, CHT suffers two main drawbacks: (i) its time complexity is O(Nd^3) - N node network size, d node degree - hence it can apply only to ultra-sparse networks. (ii) it selects top link prediction scores, which is inappropriate for the early training epochs, when the network presents unreliable connections. We propose a GPU-friendly approximation of the CH link predictor, which reduces the computational complexity to O(N^3), enabling a fast implementation of CHT in large-scale models. We introduce the Cannistraci-Hebb training soft rule (CHTs), which adopts a strategy for sampling connections in both link removal and regrowth, balancing the exploration and exploitation of network topology. To improve performance, we integrate CHTs with a sigmoid gradual density decay (CHTss). Empirical results show that, using 1% of connections, CHTs outperforms fully connected networks in MLP on visual classification tasks, compressing some networks to < 30% nodes. Using 5% of the connections, CHTss outperforms fully connected networks in two Transformer-based machine translation tasks. Using 30% of the connections, CHTss achieves superior performance compared to other dynamic sparse training methods in language modeling, and it surpasses the fully connected counterpart in zero-shot evaluations.

[Arxiv](https://arxiv.org/abs/2501.19107)