# 无偏与符号压缩在分布式学习中的应用：通过SDEs比较噪声鲁棒性

发布时间：2025年02月24日

`其他

理由：这篇论文主要研究的是分布式优化方法，特别是压缩技术在大型模型中的应用，以及通过随机微分方程分析这些算法的性能。虽然提到了大型语言模型，但其核心内容是关于分布式训练中的通信效率和优化方法，而不是直接涉及LLM的应用或理论。因此，它更适合归类到“其他”类别。` `机器学习` `计算机科学`

> Unbiased and Sign Compression in Distributed Learning: Comparing Noise Resilience via SDEs

# 摘要

> 在处理大规模模型和数据集的机器学习管道中，分布式方法至关重要。然而，这些方法的收益往往伴随着中心服务器与代理节点之间通信开销的增加，这可能成为主要瓶颈，使训练过程成本高昂甚至不可行。压缩方法，如量化和稀疏化，可以缓解这一问题。然而，这些方法在面对大型语言模型中有时会观察到的重尾梯度噪声时的鲁棒性，仍然缺乏深入理解。本研究通过随机微分方程（SDEs）分析了分布式压缩随机梯度下降（DCSGD）和分布式符号随机梯度下降（DSignSGD），填补这一研究空白。我们的研究结果显示，带有无偏压缩的DCSGD对随机梯度噪声更为敏感，而DSignSGD即使在存在大型重尾噪声的情况下仍保持稳健。此外，我们提出了新的超参数调节缩放规则，以缓解压缩带来的性能下降。这些发现通过多种深度学习架构和数据集的实证验证，为分布式优化提供了实用建议。

> Distributed methods are essential for handling machine learning pipelines comprising large-scale models and datasets. However, their benefits often come at the cost of increased communication overhead between the central server and agents, which can become the main bottleneck, making training costly or even unfeasible in such systems. Compression methods such as quantization and sparsification can alleviate this issue. Still, their robustness to large and heavy-tailed gradient noise, a phenomenon sometimes observed in language modeling, remains poorly understood. This work addresses this gap by analyzing Distributed Compressed SGD (DCSGD) and Distributed SignSGD (DSignSGD) using stochastic differential equations (SDEs). Our results show that DCSGD with unbiased compression is more vulnerable to noise in stochastic gradients, while DSignSGD remains robust, even under large and heavy-tailed noise. Additionally, we propose new scaling rules for hyperparameter tuning to mitigate performance degradation due to compression. These findings are empirically validated across multiple deep learning architectures and datasets, providing practical recommendations for distributed optimization.

[Arxiv](https://arxiv.org/abs/2502.17009)