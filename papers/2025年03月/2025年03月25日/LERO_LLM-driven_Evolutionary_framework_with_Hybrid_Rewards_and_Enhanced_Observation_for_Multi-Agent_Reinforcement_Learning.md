# LERO：面向多智能体强化学习的LLM驱动演化框架，融合混合奖励与增强观测

发布时间：2025年03月25日

`Agent` `智能系统` `多智能体`

> LERO: LLM-driven Evolutionary framework with Hybrid Rewards and Enhanced Observation for Multi-Agent Reinforcement Learning

# 摘要

> 多智能体强化学习（MARL）在合作任务中的信用分配和环境状态的部分可观察性方面面临两大关键挑战。我们提出了一种整合大型语言模型（LLMs）与进化优化的框架——LERO，专为解决这些MARL难题而设计。该框架的核心是两个由LLM生成的创新组件：通过奖励分解动态分配个体信用的混合奖励函数，以及通过推断环境上下文增强部分观察的观察增强函数。进化算法通过迭代的MARL训练周期不断优化这些组件，其中表现最佳的候选方案为后续的LLM生成提供指导。在多智能体粒子环境（MPE）中的实证研究证实，LERO在任务性能和训练效率方面均显著超越基线方法。

> Multi-agent reinforcement learning (MARL) faces two critical bottlenecks distinct from single-agent RL: credit assignment in cooperative tasks and partial observability of environmental states. We propose LERO, a framework integrating Large language models (LLMs) with evolutionary optimization to address these MARL-specific challenges. The solution centers on two LLM-generated components: a hybrid reward function that dynamically allocates individual credit through reward decomposition, and an observation enhancement function that augments partial observations with inferred environmental context. An evolutionary algorithm optimizes these components through iterative MARL training cycles, where top-performing candidates guide subsequent LLM generations. Evaluations in Multi-Agent Particle Environments (MPE) demonstrate LERO's superiority over baseline methods, with improved task performance and training efficiency.

[Arxiv](https://arxiv.org/abs/2503.21807)