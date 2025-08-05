# 中心化自适应采样：可靠独立多智能体策略协同训练新方案

发布时间：2025年08月01日

`Agent` `机器人`

> Centralized Adaptive Sampling for Reliable Co-Training of Independent Multi-Agent Policies

# 摘要

> 独立的策略梯度算法在合作性和无冲突的多智能体强化学习（MARL）任务中被广泛采用，但已知在每个智能体的策略梯度指向次优平衡点时，这些算法在收敛性上表现不佳。在这项研究中，我们发现了一种更为微妙的失效模式，它甚至可能在所有智能体的期望策略梯度都指向最优解时出现。在收集了有限数量的轨迹后，独立动作采样的随机性可能导致联合数据分布偏离预期的联合在线策略分布。这种相对于联合在线策略分布的采样误差会生成不准确的梯度估计，可能导致智能体收敛到次优解。本文探讨了通过协调动作选择减少联合采样误差的可能性，以及这样做是否能提高MARL中策略梯度学习的可靠性。为此，我们引入了一种自适应动作采样方法来减少联合采样误差。我们的方法，多智能体近端鲁棒在线策略采样（MA-PROPS），采用了一个集中化的策略行为，我们不断调整它以增加对当前相对于当前联合策略来说采样不足的联合动作的概率。我们在多种多智能体游戏中对MA-PROPS进行了实证评估，并证明了（1）MA-PROPS比标准的在线策略采样更有效地减少了联合采样误差，以及（2）提高了独立策略梯度算法的可靠性，增加了训练运行中收敛到最优联合策略的比例。

> Independent on-policy policy gradient algorithms are widely used for multi-agent reinforcement learning (MARL) in cooperative and no-conflict games, but they are known to converge suboptimally when each agent's policy gradient points toward a suboptimal equilibrium. In this work, we identify a subtler failure mode that arises \textit{even when the expected policy gradients of all agents point toward an optimal solution.} After collecting a finite set of trajectories, stochasticity in independent action sampling can cause the joint data distribution to deviate from the expected joint on-policy distribution. This \textit{sampling error} w.r.t. the joint on-policy distribution produces inaccurate gradient estimates that can lead agents to converge suboptimally. In this paper, we investigate if joint sampling error can be reduced through coordinated action selection and whether doing so improves the reliability of policy gradient learning in MARL. Toward this end, we introduce an adaptive action sampling approach to reduce joint sampling error. Our method, Multi-Agent Proximal Robust On-Policy Sampling (MA-PROPS), uses a centralized behavior policy that we continually adapt to place larger probability on joint actions that are currently under-sampled w.r.t. the current joint policy. We empirically evaluate MA-PROPS in a diverse range of multi-agent games and demonstrate that (1) MA-PROPS reduces joint sampling error more efficiently than standard on-policy sampling and (2) improves the reliability of independent policy gradient algorithms, increasing the fraction of training runs that converge to an optimal joint policy.

[Arxiv](https://arxiv.org/abs/2508.01049)