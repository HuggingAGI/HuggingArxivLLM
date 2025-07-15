# 动作分块强化学习

发布时间：2025年07月10日

`Agent

理由：这篇论文探讨了强化学习（RL）中的改进方法，特别是针对长周期和稀疏奖励任务的Q-chunking方法。强化学习涉及智能体（Agent）在环境中的学习，因此属于Agent类别。` `人工智能`

> Reinforcement Learning with Action Chunking

# 摘要

> 我们提出了一种简单而有效的强化学习（RL）改进方法——Q-chunking，特别适用于长周期、稀疏奖励的任务。该方法专为线下到线上强化学习场景设计，旨在通过利用线下先验数据集来最大化线上学习的样本效率。在这一场景中，如何有效探索和高效利用样本仍然是核心挑战，因为我们并不清楚如何利用线下数据获得良好的探索策略。我们的关键洞察是，模仿学习中广受欢迎的动作分块技术——即预测未来一系列动作而非每一步单独预测——可以应用于基于时间差分（TD）的强化学习方法，从而缓解探索难题。Q-chunking通过在“分块”动作空间中直接运行强化学习，使代理能够（1）利用线下数据中的时间一致行为进行更有效的在线探索，以及（2）采用无偏的n步备份实现更稳定和高效的TD学习。实验结果表明，Q-chunking在离线性能和在线样本效率方面表现优异，在多种长周期、稀疏奖励的操作任务中超越了现有的最佳线下到线上方法。

> We present Q-chunking, a simple yet effective recipe for improving reinforcement learning (RL) algorithms for long-horizon, sparse-reward tasks. Our recipe is designed for the offline-to-online RL setting, where the goal is to leverage an offline prior dataset to maximize the sample-efficiency of online learning. Effective exploration and sample-efficient learning remain central challenges in this setting, as it is not obvious how the offline data should be utilized to acquire a good exploratory policy. Our key insight is that action chunking, a technique popularized in imitation learning where sequences of future actions are predicted rather than a single action at each timestep, can be applied to temporal difference (TD)-based RL methods to mitigate the exploration challenge. Q-chunking adopts action chunking by directly running RL in a 'chunked' action space, enabling the agent to (1) leverage temporally consistent behaviors from offline data for more effective online exploration and (2) use unbiased $n$-step backups for more stable and efficient TD learning. Our experimental results demonstrate that Q-chunking exhibits strong offline performance and online sample efficiency, outperforming prior best offline-to-online methods on a range of long-horizon, sparse-reward manipulation tasks.

[Arxiv](https://arxiv.org/abs/2507.07969)