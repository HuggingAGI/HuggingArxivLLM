# 神经图匹配提升分子机器学习中检索增强生成的效果

发布时间：2025年02月25日

`RAG` `质谱分析`

> Neural Graph Matching Improves Retrieval Augmented Generation in Molecular Machine Learning

# 摘要

> 随着几何深度学习的进展，分子机器学习逐渐崭露头角。与此同时，检索增强生成已成为一种与语言模型搭配使用的原则性方法。然而，如何将检索增强技术最优地融入分子机器学习领域仍是未知数。图神经网络若想通过巧妙的匹配方法理解检索分子与目标分子的结构对齐，将从中获益匪浅。神经图匹配通过显式建模两个结构图之间的节点和边亲和力，并利用一种噪声鲁棒的端到端神经网络来学习亲和度指标，提供了一个极具吸引力的解决方案。我们将此方法应用于质谱模拟，并引入了MARASON，这是一个结合神经图匹配来增强基于碎片化的神经网络的全新模型。实验结果凸显了我们设计的有效性，MARASON实现了28%的top-1准确率，相较于非检索增强的最先进方法19%的准确率有了显著提升。此外，MARASON在与naive的检索增强生成方法以及传统的图匹配方法的对比中均表现更优。

> Molecular machine learning has gained popularity with the advancements of geometric deep learning. In parallel, retrieval-augmented generation has become a principled approach commonly used with language models. However, the optimal integration of retrieval augmentation into molecular machine learning remains unclear. Graph neural networks stand to benefit from clever matching to understand the structural alignment of retrieved molecules to a query molecule. Neural graph matching offers a compelling solution by explicitly modeling node and edge affinities between two structural graphs while employing a noise-robust, end-to-end neural network to learn affinity metrics. We apply this approach to mass spectrum simulation and introduce MARASON, a novel model that incorporates neural graph matching to enhance a fragmentation-based neural network. Experimental results highlight the effectiveness of our design, with MARASON achieving 28% top-1 accuracy, a substantial improvement over the non-retrieval state-of-the-art accuracy of 19%. Moreover, MARASON outperforms both naive retrieval-augmented generation methods and traditional graph matching approaches.

[Arxiv](https://arxiv.org/abs/2502.17874)