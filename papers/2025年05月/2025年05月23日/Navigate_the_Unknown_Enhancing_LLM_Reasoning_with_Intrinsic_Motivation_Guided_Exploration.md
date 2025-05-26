# # 探索未知领域：基于内在动机引导的探索方法，提升大语言模型推理能力

发布时间：2025年05月23日

`LLM应用` `人工智能`

> Navigate the Unknown: Enhancing LLM Reasoning with Intrinsic Motivation Guided Exploration

# 摘要

> 强化学习（RL）已成为提升大型语言模型（LLMs）推理能力的关键方法。然而，现有方法如PPO和GRPO存在明显局限：依赖稀疏奖励信号导致反馈不足，系统性偏见使模型更倾向于利用熟悉路径而非探索新解。这些缺陷严重制约了复杂推理任务的表现。为此，我们提出了一种名为i-MENTOR的新方法，旨在通过密集奖励和强化探索来克服这些挑战。i-MENTOR的三大创新包括：轨迹感知的探索奖励、动态奖励缩放机制和优势保留的奖励实现。实验结果表明，i-MENTOR在Countdown-4数据集上实现了22.39%的性能提升，展现了其显著优势。

> Reinforcement learning (RL) has emerged as a pivotal method for improving the reasoning capabilities of Large Language Models (LLMs). However, prevalent RL approaches such as Proximal Policy Optimization (PPO) and Group-Regularized Policy Optimization (GRPO) face critical limitations due to their reliance on sparse outcome-based rewards and inadequate mechanisms for incentivizing exploration. These limitations result in inefficient guidance for multi-step reasoning processes. Specifically, sparse reward signals fail to deliver effective or sufficient feedback, particularly for challenging problems. Furthermore, such reward structures induce systematic biases that prioritize exploitation of familiar trajectories over novel solution discovery. These shortcomings critically hinder performance in complex reasoning tasks, which inherently demand iterative refinement across ipntermediate steps. To address these challenges, we propose an Intrinsic Motivation guidEd exploratioN meThOd foR LLM Reasoning (i-MENTOR), a novel method designed to both deliver dense rewards and amplify explorations in the RL-based training paradigm. i-MENTOR introduces three key innovations: trajectory-aware exploration rewards that mitigate bias in token-level strategies while maintaining computational efficiency; dynamic reward scaling to stabilize exploration and exploitation in large action spaces; and advantage-preserving reward implementation that maintains advantage distribution integrity while incorporating exploratory guidance. Experiments across three public datasets demonstrate i-MENTOR's effectiveness with a 22.39% improvement on the difficult dataset Countdown-4.

[Arxiv](https://arxiv.org/abs/2505.17621)