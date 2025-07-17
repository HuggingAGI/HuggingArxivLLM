# # 化沙为金：通过因果边界循环数据架起策略内与策略外学习的桥梁
通过因果边界，将数据循环利用，架起策略内与策略外学习之间的桥梁。

发布时间：2025年07月15日

`Agent` `机器人控制`

> Turning Sand to Gold: Recycling Data to Bridge On-Policy and Off-Policy Learning via Causal Bound

# 摘要

> 深度强化学习（DRL）代理在解决跨领域复杂决策任务方面表现出色。然而，它们通常需要大量的训练步骤和庞大的经验回放缓冲区，导致显著的计算和资源需求。为了解决这些挑战，我们引入了一项新颖的理论成果，将Neyman-Rubin因果框架融入到DRL中。与大多数专注于限制反事实损失的方法不同，我们建立了事实损失的因果边界，这与DRL中的策略内损失类似。该边界通过将过去的价值网络输出存储在经验回放缓冲区中进行计算，有效利用了通常被丢弃的数据。在Atari 2600和MuJoCo领域对DQN和SAC等代理进行的广泛实验表明，奖励比率提高了高达2,427%，优于未采用我们提出方法的相同代理，并将经验回放缓冲区的大小减少了高达96%，在几乎不增加额外成本的情况下显著提高了样本效率。

> Deep reinforcement learning (DRL) agents excel in solving complex decision-making tasks across various domains. However, they often require a substantial number of training steps and a vast experience replay buffer, leading to significant computational and resource demands. To address these challenges, we introduce a novel theoretical result that leverages the Neyman-Rubin potential outcomes framework into DRL. Unlike most methods that focus on bounding the counterfactual loss, we establish a causal bound on the factual loss, which is analogous to the on-policy loss in DRL. This bound is computed by storing past value network outputs in the experience replay buffer, effectively utilizing data that is usually discarded. Extensive experiments across the Atari 2600 and MuJoCo domains on various agents, such as DQN and SAC, achieve up to 2,427% higher reward ratio, outperforming the same agents without our proposed term, and reducing the experience replay buffer size by up to 96%, significantly improving sample efficiency at negligible cost.

[Arxiv](https://arxiv.org/abs/2507.11269)