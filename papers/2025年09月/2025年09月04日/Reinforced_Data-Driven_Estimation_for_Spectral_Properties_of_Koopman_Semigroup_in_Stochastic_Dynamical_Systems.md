# 随机动力系统中库普曼半群谱特性的增强数据驱动估计

发布时间：2025年09月04日

`强化学习` `基础理论`

> Reinforced Data-Driven Estimation for Spectral Properties of Koopman Semigroup in Stochastic Dynamical Systems

# 摘要

> 分析Koopman算子的谱特性是理解和预测复杂随机动力系统行为的关键。但像扩展动态模态分解（EDMD）及其变体这类数据驱动估计方法的准确性，很大程度上取决于采样轨迹数据的质量和位置。本文提出了一种名为增强随机动态模态分解的新框架，它将强化学习（RL）与随机动态模态分解（SDMD）相融合，实现了对随机动力系统数据收集过程的自动引导。我们把最优采样策略构建为强化学习问题，让智能体学习选择轨迹初始条件的策略。智能体通过基于谱一致性的奖励信号进行引导，这种谱一致性用于衡量估计的Koopman特征对系统演化的描述效果，并结合探索奖励以确保对状态空间的全面覆盖。我们在双阱势、随机Duffing振子和FitzHugh-Nagumo模型等典型系统上，采用Bandit算法、深度Q网络（DQN）和近端策略优化（PPO）算法验证了该方法的有效性。结果显示，强化学习智能体无需任何系统先验知识，就能自动发现动态关键区域。严谨的理论分析为所提算法提供了收敛保证，并将最终估计精度与学习到的采样策略质量直接挂钩。我们的研究为复杂随机系统的高效谱分析提供了一种稳健且自动化的方法。

> Analyzing the spectral properties of the Koopman operator is crucial for understanding and predicting the behavior of complex stochastic dynamical systems. However, the accuracy of data-driven estimation methods, such as Extended Dynamic Mode Decomposition (EDMD) and its variants, are heavily dependent on the quality and location of the sampled trajectory data. This paper introduces a novel framework, Reinforced Stochastic Dynamic Mode Decomposition, which integrates Reinforcement Learning (RL) with Stochastic Dynamic Mode Decomposition (SDMD) to automatically guide the data collection process in stochastic dynamical systems. We frame the optimal sampling strategy as an RL problem, where an agent learns a policy to select trajectory initial conditions. The agent is guided by a reward signal based on \emph{spectral consistency}, that is a measure of how well the estimated Koopman eigenpairs describe the system's evolution balanced with an exploration bonus to ensure comprehensive coverage of the state space. We demonstrate the effectiveness of our approach using Bandit algorithm, Deep Q-Network (DQN), and Proximal Policy Optimization (PPO) algorithms on canonical systems including the double-well potential, the stochastic Duffing oscillator and the FitzHugh-Nagumo model. Our results show that the RL agent automatically discovers dynamically significant regions without any prior knowledge of the system. Rigorous theoretical analysis establishes convergence guarantees for the proposed algorithms, directly linking the final estimation accuracy to the quality of the learned sampling policy. Our work presents a robust, automated methodology for the efficient spectral analysis of complex stochastic systems.

[Arxiv](https://arxiv.org/abs/2509.04265)