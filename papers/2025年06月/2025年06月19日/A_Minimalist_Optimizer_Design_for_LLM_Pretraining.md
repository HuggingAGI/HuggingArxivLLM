# 极简主义的优化器设计用于LLM预训练

发布时间：2025年06月19日

`LLM理论` `机器学习`

> A Minimalist Optimizer Design for LLM Pretraining

# 摘要

> 训练大型语言模型 (LLMs) 通常依赖于自适应优化器如Adam，这些优化器需要大量内存来维护一阶和二阶矩矩阵，即优化器状态。尽管近期研究如GaLore、Fira和APOLLO提出了状态压缩变体以减少内存消耗，但一个根本性问题仍未解决：在LLM预训练中，真正维持最先进性能所需的最小优化器状态量是多少？本研究采用自底向上的方法系统性地探讨这一问题。

我们发现两种内存和计算高效的优化技术特别有效：(1) 按列归一化梯度显著提升了普通SGD的性能，且无需动量；(2) 仅在输出层添加一阶动量（此处梯度方差最大）即可达到与全自适应方法如Muon相媲美的性能。基于这些发现，我们提出了SCALE（随机列归一化最后一层动量），这是一种结合列归一化SGD与最后一层动量的新优化器，其中列归一化指沿输出维度对梯度进行归一化。

在多个LLaMA模型（60M-1B参数量）上，SCALE在仅占用总内存35-45%的情况下，性能可与Adam匹敌甚至超越。它还始终优于GaLore、Fira和APOLLO等内存高效优化器，在内存受限的大规模预训练中是一个极具竞争力的选择。对于LLaMA 7B模型，SCALE在困惑度和内存消耗方面均超越了最先进方法APOLLO。此外，我们的方法为更复杂的优化器设计提供了一个极简的基准。


> Training large language models (LLMs) typically relies on adaptive optimizers such as Adam, which require significant memory to maintain first- and second-moment matrices, known as optimizer states. While recent works such as GaLore, Fira, and APOLLO have proposed state-compressed variants to reduce memory consumption, a fundamental question remains: What is the minimal amount of optimizer state that is truly necessary to retain state-of-the-art performance in LLM pretraining? In this work, we systematically investigate this question using a bottom-up approach. We find that two memory- and compute-efficient optimization techniques are particularly effective: (1) column-wise gradient normalization significantly boosts the performance of plain SGD without requiring momentum; and (2) adding first-order momentum only to the output layer - where gradient variance is highest - yields performance competitive with fully adaptive methods such as Muon. Based on these insights, we propose SCALE (Stochastic Column-normalized Last-layer Momentum), a new optimizer that combines column-normalized SGD with last-layer momentum, where column normalization refers to normalizing the gradient along the output dimension. Across multiple LLaMA models (60M-1B), SCALE matches or exceeds the performance of Adam while using only 35-45% of the total memory. It also consistently outperforms memory-efficient optimizers such as GaLore, Fira, and APOLLO, making it a strong candidate for large-scale pretraining under memory constraints. For the LLaMA 7B model, SCALE outperforms the state-of-the-art method APOLLO in terms of both perplexity and memory consumption. In addition, our method serves as a minimalist baseline for more sophisticated optimizer design.

[Arxiv](https://arxiv.org/abs/2506.16659)