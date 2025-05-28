# LLM引导的强化学习：基于策略调制突破训练瓶颈

发布时间：2025年05月26日

`LLM应用`

> LLM-Guided Reinforcement Learning: Addressing Training Bottlenecks through Policy Modulation

# 摘要

> 尽管强化学习 (RL) 在多个领域取得了显著成功，但训练复杂任务的有效策略仍具挑战性。智能体往往陷入局部最优解，难以最大化长期奖励。现有的缓解训练瓶颈的方法主要分为两类：(i) 自动化策略改进，通过识别过去轨迹中的关键状态来优化策略，但模型训练成本高昂且结果不确定；(ii) 人类在环改进，利用人类反馈纠正智能体行为，但难以扩展到大规模或连续动作空间的环境。在本研究中，我们提出了一种基于大语言模型 (LLM) 的策略调制框架，无需额外模型训练或人工干预，即可提升 RL 训练效果。具体而言，我们首先利用 LLM 从次优智能体的轨迹中识别关键状态，随后 LLM 提供动作建议并分配隐式奖励以优化策略。在标准 RL 基准上的实验结果表明，我们的方法显著超越现有最优基线，充分证明了基于 LLM 的解释在解决 RL 训练瓶颈方面的有效性。

> While reinforcement learning (RL) has achieved notable success in various domains, training effective policies for complex tasks remains challenging. Agents often converge to local optima and fail to maximize long-term rewards. Existing approaches to mitigate training bottlenecks typically fall into two categories: (i) Automated policy refinement, which identifies critical states from past trajectories to guide policy updates, but suffers from costly and uncertain model training; and (ii) Human-in-the-loop refinement, where human feedback is used to correct agent behavior, but this does not scale well to environments with large or continuous action spaces. In this work, we design a large language model-guided policy modulation framework that leverages LLMs to improve RL training without additional model training or human intervention. We first prompt an LLM to identify critical states from a sub-optimal agent's trajectories. Based on these states, the LLM then provides action suggestions and assigns implicit rewards to guide policy refinement. Experiments across standard RL benchmarks demonstrate that our method outperforms state-of-the-art baselines, highlighting the effectiveness of LLM-based explanations in addressing RL training bottlenecks.

[Arxiv](https://arxiv.org/abs/2505.20671)