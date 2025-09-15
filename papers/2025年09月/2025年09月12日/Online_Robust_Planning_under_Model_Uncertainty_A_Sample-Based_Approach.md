# 模型不确定性下的在线鲁棒规划：基于样本的方法

发布时间：2025年09月12日

`强化学习` `基础理论`

> Online Robust Planning under Model Uncertainty: A Sample-Based Approach

# 摘要

> 马尔可夫决策过程（MDPs）的在线规划让智能体通过从当前状态模拟未来轨迹来制定序贯决策，因此特别适用于大规模或动态环境。基于采样的方法（如稀疏采样和蒙特卡洛树搜索（MCTS））凭借其利用生成模型近似最优动作的能力而被广泛应用。但在实际应用中，生成模型往往从有限数据中学习，由此产生的近似误差可能导致性能下降或不安全行为。为解决这些问题，鲁棒马尔可夫决策过程（RMDPs）提供了模型不确定性下规划的原则性框架，不过现有方法计算量较大，难以满足实时需求。为此，我们提出了鲁棒稀疏采样（RSS）——首个适用于RMDPs的在线规划算法，具备有限样本的理论性能保证。与稀疏采样（估计标称值函数）不同，RSS借助样本平均近似（SAA）的高效性和理论特性计算鲁棒值函数，实现了在线场景下鲁棒策略的高效求解。此外，RSS适用于无限或连续状态空间，其采样和计算复杂度不受状态空间大小影响。我们不仅提供了理论性能保证，还通过实验证明，在动态不确定的环境中，RSS的表现优于标准稀疏采样。

> Online planning in Markov Decision Processes (MDPs) enables agents to make sequential decisions by simulating future trajectories from the current state, making it well-suited for large-scale or dynamic environments. Sample-based methods such as Sparse Sampling and Monte Carlo Tree Search (MCTS) are widely adopted for their ability to approximate optimal actions using a generative model. However, in practical settings, the generative model is often learned from limited data, introducing approximation errors that can degrade performance or lead to unsafe behaviors. To address these challenges, Robust MDPs (RMDPs) offer a principled framework for planning under model uncertainty, yet existing approaches are typically computationally intensive and not suited for real-time use. In this work, we introduce Robust Sparse Sampling (RSS), the first online planning algorithm for RMDPs with finite-sample theoretical performance guarantees. Unlike Sparse Sampling, which estimates the nominal value function, RSS computes a robust value function by leveraging the efficiency and theoretical properties of Sample Average Approximation (SAA), enabling tractable robust policy computation in online settings. RSS is applicable to infinite or continuous state spaces, and its sample and computational complexities are independent of the state space size. We provide theoretical performance guarantees and empirically show that RSS outperforms standard Sparse Sampling in environments with uncertain dynamics.

[Arxiv](https://arxiv.org/abs/2509.10162)