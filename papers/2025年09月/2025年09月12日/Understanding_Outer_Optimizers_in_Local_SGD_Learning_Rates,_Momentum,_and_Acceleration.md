# # 理解局部SGD中的外部优化器：学习率、动量与加速

发布时间：2025年09月12日

`其他` `基础理论`

> Understanding Outer Optimizers in Local SGD: Learning Rates, Momentum, and Acceleration

# 摘要

> 现代机器学习的训练往往依赖大规模批处理、分布式数据及海量并行计算硬件（如移动设备等边缘设备或分布式数据中心）。在这类场景中，通信已成为主要瓶颈，而局部随机梯度下降（Local SGD）等方法在降低额外通信开销方面展现出巨大潜力。局部随机梯度下降包含三个部分：局部优化过程、聚合机制，以及利用节点聚合更新生成新模型的外优化器。尽管已有大量文献研究局部优化过程中超参数的影响，但外优化器及其超参数的选择仍不明确。本文研究了外优化器在局部随机梯度下降中的作用，并为该算法证明了新的收敛保证。具体而言，我们发现调整外学习率能够（a）在优化误差与随机梯度噪声方差之间进行权衡，（b）弥补内学习率调优不当的问题。我们的理论表明，外学习率有时应设置为大于【数学公式】的值。我们将研究结果扩展到外优化器中使用动量的场景，并发现动量调整后的外学习率具有类似作用。我们还研究了外优化器中的加速策略，结果表明，加速策略能根据通信轮数提升收敛速率，优于先前在局部应用加速的算法。最后，我们提出了一种新的局部随机梯度下降数据依赖分析方法，为外学习率调整提供了更深入的见解。我们通过标准语言模型和多种外优化器开展了全面实验，验证了理论的有效性。

> Modern machine learning often requires training with large batch size, distributed data, and massively parallel compute hardware (like mobile and other edge devices or distributed data centers). Communication becomes a major bottleneck in such settings but methods like Local Stochastic Gradient Descent (Local SGD) show great promise in reducing this additional communication overhead. Local SGD consists of three parts: a local optimization process, an aggregation mechanism, and an outer optimizer that uses the aggregated updates from the nodes to produce a new model. While there exists an extensive literature on understanding the impact of hyperparameters in the local optimization process, the choice of outer optimizer and its hyperparameters is less clear. We study the role of the outer optimizer in Local SGD, and prove new convergence guarantees for the algorithm. In particular, we show that tuning the outer learning rate allows us to (a) trade off between optimization error and stochastic gradient noise variance, and (b) make up for ill-tuning of the inner learning rate. Our theory suggests that the outer learning rate should sometimes be set to values greater than $1$. We extend our results to settings where we use momentum in the outer optimizer, and we show a similar role for the momentum-adjusted outer learning rate. We also study acceleration in the outer optimizer and show that it improves the convergence rate as a function of the number of communication rounds, improving upon the convergence rate of prior algorithms that apply acceleration locally. Finally, we also introduce a novel data-dependent analysis of Local SGD that yields further insights on outer learning rate tuning. We conduct comprehensive experiments with standard language models and various outer optimizers to validate our theory.

[Arxiv](https://arxiv.org/abs/2509.10439)