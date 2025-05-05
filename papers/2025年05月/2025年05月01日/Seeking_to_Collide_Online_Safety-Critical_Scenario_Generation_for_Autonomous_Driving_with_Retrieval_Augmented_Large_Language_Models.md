# 主动碰撞：基于检索增强大型语言模型的自动驾驶安全场景在线生成

发布时间：2025年05月01日

`Agent` `自动驾驶` `交通安全`

> Seeking to Collide: Online Safety-Critical Scenario Generation for Autonomous Driving with Retrieval Augmented Large Language Models

# 摘要

> 模拟测试是验证自动驾驶汽车 (AVs) 的关键环节，但现有场景生成方法存在两大局限：要么过度拟合常见驾驶模式，要么以离线、非交互式的方式运行，无法发现罕见的安全关键边缘案例。本文提出了一种在线的、检索增强型大型语言模型 (LLM) 框架，专注于生成安全关键驾驶场景。

我们的方法采用基于LLM的行为分析器，从实时观测状态中推断出后方车辆最具威胁的意图，随后调用其他LLM代理生成可行的对抗轨迹。为了解决灾难性遗忘问题并加速模型适应，我们引入了动态记忆和检索机制，通过存储意图-规划器对并自动扩展行为库，帮助模型快速适应新意图。

实验结果表明，我们的模型在Waymo开放运动数据集上的表现显著优于现有方法，将平均最小碰撞时间从1.62秒降低到1.08秒，并实现了75%的碰撞率，展现出强大的安全性能。


> Simulation-based testing is crucial for validating autonomous vehicles (AVs), yet existing scenario generation methods either overfit to common driving patterns or operate in an offline, non-interactive manner that fails to expose rare, safety-critical corner cases. In this paper, we introduce an online, retrieval-augmented large language model (LLM) framework for generating safety-critical driving scenarios. Our method first employs an LLM-based behavior analyzer to infer the most dangerous intent of the background vehicle from the observed state, then queries additional LLM agents to synthesize feasible adversarial trajectories. To mitigate catastrophic forgetting and accelerate adaptation, we augment the framework with a dynamic memorization and retrieval bank of intent-planner pairs, automatically expanding its behavioral library when novel intents arise. Evaluations using the Waymo Open Motion Dataset demonstrate that our model reduces the mean minimum time-to-collision from 1.62 to 1.08 s and incurs a 75% collision rate, substantially outperforming baselines.

[Arxiv](https://arxiv.org/abs/2505.00972)