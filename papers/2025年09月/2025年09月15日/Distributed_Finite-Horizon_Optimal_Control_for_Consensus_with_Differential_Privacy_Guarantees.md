# 带差分隐私保障的分布式有限时域一致性最优控制

发布时间：2025年09月15日

`Agent` `工业与制造`

> Distributed Finite-Horizon Optimal Control for Consensus with Differential Privacy Guarantees

# 摘要

> 本文针对多智能体系统（MAS）的隐私保护一致性控制问题，提出了一种基于差分隐私的解决方案。我们设计了一种新颖的分布式有限时域线性二次调节器（LQR）框架，该框架允许智能体共享各自的状态信息，同时确保其本地成对权重矩阵的机密性——这些矩阵在MAS中属于敏感数据。保护这些矩阵可有效保障每个智能体的私有成本函数及控制偏好。具体而言，我们的解决方案向通信的状态信息中注入与一致性误差相关的拉普拉斯噪声，并在本地成本函数中采用精心设计的时变缩放因子。{该方法确保有界一致性，且无需依赖特定噪声分布假设，即可为权重矩阵实现严格的【数学公式】-差分隐私。}此外，我们通过分析明确了一致性精度与隐私水平之间的权衡关系，并就如何通过适当缩放LQR权重矩阵和隐私预算来提升一致性性能提供了清晰指导。

> This paper addresses the problem of privacy-preserving consensus control for multi-agent systems (MAS) using differential privacy. We propose a novel distributed finite-horizon linear quadratic regulator (LQR) framework, in which agents share individual state information while preserving the confidentiality of their local pairwise weight matrices, which are considered sensitive data in MAS. Protecting these matrices effectively safeguards each agent's private cost function and control preferences. Our solution injects consensus error-dependent Laplace noise into the communicated state information and employs a carefully designed time-dependent scaling factor in the local cost functions. {This approach guarantees bounded consensus and achieves rigorous $ε$-differential privacy for the weight matrices without relying on specific noise distribution assumptions.} Additionally, we analytically characterize the trade-off between consensus accuracy and privacy level, offering clear guidelines on how to enhance consensus performance through appropriate scaling of the LQR weight matrices and the privacy budget.

[Arxiv](https://arxiv.org/abs/2509.11917)