# AdaGrad 邂逅 Muon：正交更新的自适应步长

发布时间：2025年09月02日

`其他` `基础理论`

> AdaGrad Meets Muon: Adaptive Stepsizes for Orthogonal Updates

# 摘要

> 近期提出的Muon优化器借助正交化动量更新权重矩阵，在大语言模型训练中已取得显著实证成效。但目前尚不清楚如何为这类正交化更新确定学习率。相比之下，AdaGrad是一种广泛应用的自适应方法，其核心是利用累积的历史梯度对随机梯度进行缩放。为此，我们提出了一种名为AdaGO的新算法，它将基于范数的AdaGrad型步长与正交化更新方向相融合，兼具两种方法的优势。与Muon的其他自适应变体不同，AdaGO保留了更新方向的正交性（可理解为谱下降方向），同时通过累积的历史梯度范数对方向进行缩放，从而让步长能够自适应优化地形。AdaGO的实现只需对Muon稍作修改，仅需额外计算一个标量变量——累积平方梯度范数，因此兼具计算高效性和内存高效性。在标准平滑性及无偏有界方差噪声假设下，我们为随机和确定性场景中的非凸函数确立了最优理论收敛率。在CIFAR-10分类与函数回归任务上的实证结果显示，AdaGO性能超越了Muon和Adam。

> The recently proposed Muon optimizer updates weight matrices via orthogonalized momentum and has demonstrated strong empirical success in large language model training. However, it remains unclear how to determine the learning rates for such orthogonalized updates. AdaGrad, by contrast, is a widely used adaptive method that scales stochastic gradients by accumulated past gradients. We propose a new algorithm, AdaGO, which combines a norm-based AdaGrad-type stepsize with an orthogonalized update direction, bringing together the benefits of both approaches. Unlike other adaptive variants of Muon, AdaGO preserves the orthogonality of the update direction, which can be interpreted as a spectral descent direction, while adapting the stepsizes to the optimization landscape by scaling the direction with accumulated past gradient norms. The implementation of AdaGO requires only minimal modification to Muon, with a single additional scalar variable, the accumulated squared gradient norms, to be computed, making it computationally and memory efficient. Optimal theoretical convergence rates are established for nonconvex functions in both stochastic and deterministic settings under standard smoothness and unbiased bounded-variance noise assumptions. Empirical results on CIFAR-10 classification and function regression demonstrate that AdaGO outperforms Muon and Adam.

[Arxiv](https://arxiv.org/abs/2509.02981)