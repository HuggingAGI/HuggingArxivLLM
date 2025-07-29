# 策略悬崖：大型语言模型中奖励-策略映射图的理论分析

发布时间：2025年07月27日

`LLM理论` `人工智能`

> The Policy Cliff: A Theoretical Analysis of Reward-Policy Maps in Large Language Models

# 摘要

> 强化学习（RL）在塑造大语言模型行为中扮演关键角色，但其脆弱性常常导致推理错误和指令违背等问题。本文提出了一种严格的数学框架，揭示策略脆弱性源于非唯一最优动作，并通过“有效奖励”聚合机制分析多奖励环境下的稳定性。熵正则化虽能恢复稳定性，却增加了随机性。我们的框架统一解释了欺骗性推理等实证现象，为设计更安全的AI系统提供了理论依据。

> Reinforcement learning (RL) plays a crucial role in shaping the behavior of large language and reasoning models (LLMs/LRMs). However, it often produces brittle and unstable policies, leading to critical failures such as spurious reasoning, deceptive alignment, and instruction disobedience that undermine the trustworthiness and safety of LLMs/LRMs. Currently, these issues lack a unified theoretical explanation and are typically addressed using ad-hoc heuristics. This paper presents a rigorous mathematical framework for analyzing the stability of the mapping from a reward function to the optimal policy. We show that policy brittleness often stems from non-unique optimal actions, a common occurrence when multiple valid traces exist in a reasoning task. This theoretical lens provides a unified explanation for a range of seemingly disparate failures, reframing them as rational outcomes of optimizing rewards that may be incomplete or noisy, especially in the presence of action degeneracy. We extend this analysis from the fundamental single-reward setting to the more realistic multi-reward RL across diverse domains, showing how stability is governed by an "effective reward" aggregation mechanism. We also prove that entropy regularization restores policy stability at the cost of increased stochasticity. Our framework provides a unified explanation for recent empirical findings on deceptive reasoning, instruction-following trade-offs, and RLHF-induced sophistry, and is further validated through perturbation experiments in multi-reward RL. This work advances policy-stability analysis from empirical heuristics towards a principled theory, offering essential insights for designing safer and more trustworthy AI systems.

[Arxiv](https://arxiv.org/abs/2507.20150)