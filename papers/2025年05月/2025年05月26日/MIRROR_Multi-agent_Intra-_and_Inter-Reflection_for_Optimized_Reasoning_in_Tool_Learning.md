# MIRROR：多智能体内外部反思优化工具学习推理

发布时间：2025年05月26日

`Agent` `多智能体` `人工智能`

> MIRROR: Multi-agent Intra- and Inter-Reflection for Optimized Reasoning in Tool Learning

# 摘要

> 涉及工具集成的复杂任务为大型语言模型 (LLMs) 带来显著挑战，促使多智能体工作流作为一种有前景的解决方案出现。反思作为一种有效策略，用于纠正智能体工作流中的错误轨迹。然而，现有方法仅在后行动阶段利用这种能力，即智能体观察执行结果。我们认为，与人类类似，LLMs 也可以在行动执行前进行反思：智能体能够预见自身决策可能导致的不良结果，这不仅为评估决策提供了必要补充视角，还能防止错误在整个轨迹中传播。本文提出 MIRROR 框架，包含在行动执行前批判性评估计划动作的内省，以及根据观察结果进一步调整轨迹的互省。此设计系统性利用 LLM 反思能力，消除并修正错误动作，作用范围更为全面。在 StableToolBench 和 TravelPlanner 基准上的评估表明，MIRROR 的性能优于现有方法，达到最新技术水平。


> Complex tasks involving tool integration pose significant challenges for Large Language Models (LLMs), leading to the emergence of multi-agent workflows as a promising solution. Reflection has emerged as an effective strategy for correcting erroneous trajectories in agentic workflows. However, existing approaches only exploit such capability in the post-action stage, where the agent observes the execution outcomes. We argue that, like humans, LLMs can also engage in reflection before action execution: the agent can anticipate undesirable outcomes from its own decisions, which not only provides a necessarily complementary perspective to evaluate the decision but also prevents the propagation of errors throughout the trajectory. In this paper, we propose MIRROR, a framework that consists of both intra-reflection, which critically assesses intended actions before execution, and inter-reflection, which further adjusts the trajectory based on observations. This design systematically leverages LLM reflection capabilities to eliminate and rectify erroneous actions on a more comprehensive scope. Evaluations on both the StableToolBench and TravelPlanner benchmarks demonstrate MIRROR's superior performance, achieving state-of-the-art results compared to existing approaches.

[Arxiv](https://arxiv.org/abs/2505.20670)