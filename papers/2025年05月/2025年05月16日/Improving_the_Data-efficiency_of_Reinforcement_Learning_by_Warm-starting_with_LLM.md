# 利用LLM初始化提升强化学习的数据效率

发布时间：2025年05月16日

`LLM应用` `人工智能`

> Improving the Data-efficiency of Reinforcement Learning by Warm-starting with LLM

# 摘要

> 我们研究了大型语言模型 (LLM) 在预训练强化学习 (RL) 算法方面的应用，旨在提升其在经典马尔可夫决策过程 (MDP) 环境中的学习效果。本研究重点在于利用 LLM 生成一个离策略数据集，该数据集能够充分覆盖最优策略访问的状态-动作对。随后，我们结合 RL 算法探索环境并优化 LLM 建议的策略。我们的算法 LORO 凭借 LLM 提供的良好初始策略，不仅能够收敛到最优策略，还具有较高的采样效率。在 CartPole 和 Pendulum 等 OpenAI Gym 环境中，我们实证展示了 LORO 相较于纯 LLM 策略、纯 RL 以及两者的简单结合等基线算法的优越性，累积奖励达到了纯 RL 基线的 $4 	imes$ 倍。

> We investigate the usage of Large Language Model (LLM) in collecting high-quality data to warm-start Reinforcement Learning (RL) algorithms for learning in some classical Markov Decision Process (MDP) environments. In this work, we focus on using LLM to generate an off-policy dataset that sufficiently covers state-actions visited by optimal policies, then later using an RL algorithm to explore the environment and improve the policy suggested by the LLM. Our algorithm, LORO, can both converge to an optimal policy and have a high sample efficiency thanks to the LLM's good starting policy. On multiple OpenAI Gym environments, such as CartPole and Pendulum, we empirically demonstrate that LORO outperforms baseline algorithms such as pure LLM-based policies, pure RL, and a naive combination of the two, achieving up to $4 \times$ the cumulative rewards of the pure RL baseline.

[Arxiv](https://arxiv.org/abs/2505.10861)