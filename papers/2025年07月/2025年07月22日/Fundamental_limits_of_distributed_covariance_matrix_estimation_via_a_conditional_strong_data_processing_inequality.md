# 基于条件强数据处理不等式探讨分布式协方差矩阵估计的根本限制

发布时间：2025年07月22日

`其他` `统计学` `计算机科学`

> Fundamental limits of distributed covariance matrix estimation via a conditional strong data processing inequality

# 摘要

> 高维协方差矩阵的估计在众多领域中扮演着关键角色。本文深入探讨了特征分割设置下分布式协方差估计的理论边界，特别是在智能体间通信受限的场景中。具体而言，我们研究了多个智能体各自观察来自子高斯分布随机向量的独立同分布样本的不同组件的情况。一个中心服务器的目标是利用各智能体通信的有限比特来精确估计完整的协方差矩阵。我们成功获得了在算子范数和弗罗贝尼乌斯范数下的协方差矩阵估计的近紧最小最大下界。我们的核心创新在于提出了一种新型技术工具——条件强数据处理不等式（C-SDPI）系数，它不仅继承了传统强数据处理不等式（SDPI）的关键性质，如张量化，还能够量化状态相关信道中的平均收缩，显著优于最坏情况下的SDPI系数。通过结合Geng-Nair的加倍技巧和算子Jensen不等式，我们成功计算了高斯混合信道的C-SDPI系数。这一成果被进一步用于建立估计误差的最小最大下界，清晰地揭示了样本量、通信成本与数据维度之间的复杂权衡关系。基于此，我们提出了一种近最优的估计协议，其样本和通信需求与理论下界相差仅对数因子。与现有文献不同，我们的框架不依赖于无限样本或高斯分布的假设，因而具有广泛的适用性。最后，我们还将分析拓展至交互协议领域，证实了交互机制相较于非交互方案能够显著降低通信需求，为实际应用提供了重要的理论支持。

> Estimating high-dimensional covariance matrices is a key task across many fields. This paper explores the theoretical limits of distributed covariance estimation in a feature-split setting, where communication between agents is constrained. Specifically, we study a scenario in which multiple agents each observe different components of i.i.d. samples drawn from a sub-Gaussian random vector. A central server seeks to estimate the complete covariance matrix using a limited number of bits communicated by each agent. We obtain a nearly tight minimax lower bound for covariance matrix estimation under operator norm and Frobenius norm. Our main technical tool is a novel generalization of the strong data processing inequality (SDPI), termed the Conditional Strong Data Processing Inequality (C-SDPI) coefficient, introduced in this work. The C-SDPI coefficient shares key properties such as tensorization with the conventional SDPI. Crucially, it quantifies the average contraction in a state-dependent channel and can be significantly lower than the worst-case SDPI coefficient over the state input.
  Utilizing the doubling trick of Geng-Nair and an operator Jensen inequality, we compute this coefficient for Gaussian mixture channels. We then employ it to establish minimax lower bounds on estimation error, capturing the trade-offs among sample size, communication cost, and data dimensionality. Building on this, we present a nearly optimal estimation protocol whose sample and communication requirements match the lower bounds up to logarithmic factors. Unlike much of the existing literature, our framework does not assume infinite samples or Gaussian distributions, making it broadly applicable. Finally, we extend our analysis to interactive protocols, showing interaction can significantly reduce communication requirements compared to non-interactive schemes.

[Arxiv](https://arxiv.org/abs/2507.16953)