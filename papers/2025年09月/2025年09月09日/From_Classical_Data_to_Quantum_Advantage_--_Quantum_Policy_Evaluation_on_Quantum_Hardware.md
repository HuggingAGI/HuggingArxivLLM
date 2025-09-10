# 从经典数据迈向量子优势——量子硬件上的量子策略评估

发布时间：2025年09月09日

`强化学习` `基础理论`

> From Classical Data to Quantum Advantage -- Quantum Policy Evaluation on Quantum Hardware

# 摘要

> 量子策略评估（QPE）是强化学习（RL）领域的一种算法，其效率相比同类经典蒙特卡洛估计提升了平方级。该算法借助有限马尔可夫决策过程的直接量子力学实现，通过幺正算子对智能体与环境进行建模，使二者在叠加态下交换状态、动作与奖励。以往，为开展说明性基准测试，量子环境需通过量子模拟器手动实现并进行参数化。本文提出，可通过量子硬件上的量子机器学习（QML），从经典观测数据集中学习上述环境参数。随后，将学习得到的量子环境应用于QPE，同样在量子硬件上完成策略评估计算。实验结果表明，尽管面临噪声干扰、相干时间短等挑战，QML与QPE的融合仍为强化学习领域实现量子优势展现出广阔前景。

> Quantum policy evaluation (QPE) is a reinforcement learning (RL) algorithm which is quadratically more efficient than an analogous classical Monte Carlo estimation. It makes use of a direct quantum mechanical realization of a finite Markov decision process, in which the agent and the environment are modeled by unitary operators and exchange states, actions, and rewards in superposition. Previously, the quantum environment has been implemented and parametrized manually for an illustrative benchmark using a quantum simulator. In this paper, we demonstrate how these environment parameters can be learned from a batch of classical observational data through quantum machine learning (QML) on quantum hardware. The learned quantum environment is then applied in QPE to also compute policy evaluations on quantum hardware. Our experiments reveal that, despite challenges such as noise and short coherence times, the integration of QML and QPE shows promising potential for achieving quantum advantage in RL.

[Arxiv](https://arxiv.org/abs/2509.07614)