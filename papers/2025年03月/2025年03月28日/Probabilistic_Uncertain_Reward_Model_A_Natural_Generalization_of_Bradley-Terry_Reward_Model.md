# # 摘要
基于概率的不确定奖励模型：一种 Bradley-Terry 奖励模型的自然拓展

发布时间：2025年03月28日

`LLM理论` `人工智能`

> Probabilistic Uncertain Reward Model: A Natural Generalization of Bradley-Terry Reward Model

# 摘要

> 人类反馈的强化学习（RLHF）在大型语言模型训练中扮演着关键角色。然而，奖励作弊这一现象——即模型利用奖励模型中的缺陷——仍是实现稳健且可扩展智能的主要障碍。现有研究尝试通过不确定奖励模型来解决这一问题，但它们往往缺乏系统性或理论基础，未能有效建模偏好数据中的内在不确定性。本文提出了一种概率不确定奖励模型（PURM），这是对经典Bradley-Terry奖励模型的自然扩展。该模型直接从偏好数据中学习奖励分布，并通过奖励分布间的平均重叠区域量化每样本的不确定性。为了缓解奖励作弊问题，我们还将不确定性感知惩罚引入近端策略优化（PPO），利用学习到的不确定性动态平衡奖励优化与探索。我们还提供了一种轻量级且易于使用的PURM实现方案。实验结果表明，与基线方法相比，PURM不仅显著延迟了奖励作弊的出现，还在稳定性和有效性方面取得了更优的最终奖励性能。

> Reinforcement Learning from Human Feedback (RLHF) has emerged as a critical technique for training large language models. However, reward hacking-a phenomenon where models exploit flaws in the reward model-remains a significant barrier to achieving robust and scalable intelligence through long-term training. Existing studies have proposed uncertain reward model to address reward hacking, however, they often lack systematic or theoretical foundations, failing to model the uncertainty intrinsically emerging from preference data. In this paper, we propose the Probabilistic Uncertain Reward Model (PURM), a natural generalization of the classical Bradley-Terry reward model. PURM learns reward distributions directly from preference data and quantifies per-sample uncertainty via the average overlap area between reward distributions. To mitigate reward hacking, we further introduce an uncertainty-aware penalty into Proximal Policy Optimization (PPO), which leverages the learned uncertainty to dynamically balance reward optimization and exploration. We propose a lightweight and easy-to-use implementation of PURM. Experiments demonstrate that PURM significantly delays the onset of reward hacking while improving final reward performance, outperforming baseline methods in both stability and effectiveness.

[Arxiv](https://arxiv.org/abs/2503.22480)