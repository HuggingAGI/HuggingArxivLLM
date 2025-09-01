# 面向稀疏奖励强化学习的LLM驱动内在动机

发布时间：2025年08月25日

`强化学习` `基础理论`

> LLM-Driven Intrinsic Motivation for Sparse Reward Reinforcement Learning

# 摘要

> 本文探索了两种内在动机策略的融合，旨在提升强化学习（RL）智能体在极度稀疏奖励环境中的学习效率——这类环境中正反馈极为罕见，导致传统学习方法举步维艰。我们提出将变分状态内在奖励（VSIMR）与基于大型语言模型（LLMs）的内在奖励方法相结合：前者利用变分自编码器（VAEs）对状态新颖性进行奖励，后者则借助LLMs的预训练知识，根据环境和目标描述生成奖励信号，为智能体提供引导。我们在稀疏奖励基准环境MiniGrid DoorKey中，基于演员-评论家（A2C）智能体实现了这一组合策略。实证结果显示，与单独使用任一策略或无法有效学习的标准A2C智能体相比，该组合策略显著提升了智能体的性能和采样效率。学习曲线分析进一步揭示，这种组合能有效互补环境与任务的不同需求：VSIMR推动智能体探索新状态，LLM衍生的奖励则助力其逐步向目标靠近并加以利用。

> This paper explores the combination of two intrinsic motivation strategies to improve the efficiency of reinforcement learning (RL) agents in environments with extreme sparse rewards, where traditional learning struggles due to infrequent positive feedback. We propose integrating Variational State as Intrinsic Reward (VSIMR), which uses Variational AutoEncoders (VAEs) to reward state novelty, with an intrinsic reward approach derived from Large Language Models (LLMs). The LLMs leverage their pre-trained knowledge to generate reward signals based on environment and goal descriptions, guiding the agent. We implemented this combined approach with an Actor-Critic (A2C) agent in the MiniGrid DoorKey environment, a benchmark for sparse rewards. Our empirical results show that this combined strategy significantly increases agent performance and sampling efficiency compared to using each strategy individually or a standard A2C agent, which failed to learn. Analysis of learning curves indicates that the combination effectively complements different aspects of the environment and task: VSIMR drives exploration of new states, while the LLM-derived rewards facilitate progressive exploitation towards goals.

[Arxiv](https://arxiv.org/abs/2508.18420)