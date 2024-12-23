# 离线强化学习应用于 LLM 的多步推理

发布时间：2024年12月20日

`LLM应用` `语言模型`

> Offline Reinforcement Learning for LLM Multi-Step Reasoning

# 摘要

> 通过离线强化学习（RL）提升大型语言模型（LLMs）的多步推理能力，对于让其迅速适应复杂任务极为关键。尽管直接偏好优化（DPO）在使LLMs契合人类偏好方面颇具潜力，但它不太适用于多步推理任务，原因在于：（1）DPO依赖成对的偏好数据，而多步推理任务难以轻易获取此类数据；（2）它对所有标记同等对待，导致在多步推理任务的信用分配中效果不佳，因为这类任务通常奖励稀疏。在本研究中，我们提出了OREO（离线推理优化），这是一种用于增强LLM多步推理的离线RL方法。基于先前最大熵强化学习工作的见解，它通过优化软贝尔曼方程共同学习策略模型和价值函数。从原理上讲，它降低了收集成对数据的需求，并能实现更优的信用分配。从实践来看，OREO在多步推理基准测试中超越了现有的离线学习方法，涵盖数学推理任务（GSM8K、MATH）和具身代理控制（ALFWorld）。当有更多资源可用时，该方法能够扩展至多迭代框架。此外，学到的价值函数可免费用于引导树搜索，从而在测试时进一步提升性能。

> Improving the multi-step reasoning ability of large language models (LLMs) with offline reinforcement learning (RL) is essential for quickly adapting them to complex tasks. While Direct Preference Optimization (DPO) has shown promise in aligning LLMs with human preferences, it is less suitable for multi-step reasoning tasks because (1) DPO relies on paired preference data, which is not readily available for multi-step reasoning tasks, and (2) it treats all tokens uniformly, making it ineffective for credit assignment in multi-step reasoning tasks, which often come with sparse reward. In this work, we propose OREO (Offline Reasoning Optimization), an offline RL method for enhancing LLM multi-step reasoning. Building on insights from previous works of maximum entropy reinforcement learning, it jointly learns a policy model and value function by optimizing the soft Bellman Equation. We show in principle that it reduces the need to collect pairwise data and enables better credit assignment. Empirically, OREO surpasses existing offline learning methods on multi-step reasoning benchmarks, including mathematical reasoning tasks (GSM8K, MATH) and embodied agent control (ALFWorld). The approach can be extended to a multi-iteration framework when additional resources are available. Furthermore, the learned value function can be leveraged to guide the tree search for free, which can further boost performance during test time.

[Arxiv](https://arxiv.org/abs/2412.16145)