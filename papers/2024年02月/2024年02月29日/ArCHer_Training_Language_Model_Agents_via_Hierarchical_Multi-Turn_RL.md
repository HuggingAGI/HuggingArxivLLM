# ArCHer 是一种创新方法，通过运用分层多轮强化学习技术来训练语言模型智能体，使其在复杂对话场景中更具交互性和适应性。

发布时间：2024年02月29日

`Agent`

> ArCHer: Training Language Model Agents via Hierarchical Multi-Turn RL

# 摘要

> LLMs广泛应用于涉及多轮交互和智慧决策的“智能体”任务中，而强化学习（RL）为解决此类任务提供了通用方案。然而，目前针对LLMs的RL技术大多侧重于优化单次交互的奖励。实际上，大部分单次交互RL方法尚不能让LLMs具备在多轮交互中聪明地搜寻信息、合理分配功劳或反思过往行动的能力，而这对于完成智能体任务至关重要。那么，怎样才能设计出针对LLMs高效且有效的多轮RL算法呢？本文提出了一个专门面向LLMs微调的多轮RL算法构建框架，它不仅保持了现有单轮RL方法（如近端策略优化法）的灵活性，还能有效应对多轮交互、长远考虑及延迟奖励等问题。该框架采用分层RL策略，同时运行两个RL算法：一个是负责跨对话轮次累积奖励的高层离线价值型RL算法；另一个是基于高层价值函数，在每一轮对话或表述内训练令牌策略的低层RL算法。这一被称为ArCHer的分层Actor-Critic框架，还可启发其他的RL方法。实验表明，ArCHer在智能体任务上的表现显著优于现有方法，样本效率提高了大约100倍，并且随着模型容量增大至我们所测试的70亿级别，其性能也持续提升。

> A broad use case of large language models (LLMs) is in goal-directed decision-making tasks (or "agent" tasks), where an LLM needs to not just generate completions for a given prompt, but rather make intelligent decisions over a multi-turn interaction to accomplish a task (e.g., when interacting with the web, using tools, or providing customer support). Reinforcement learning (RL) provides a general paradigm to address such agent tasks, but current RL methods for LLMs largely focus on optimizing single-turn rewards. By construction, most single-turn RL methods cannot endow LLMs with the ability to intelligently seek information over multiple turns, perform credit assignment, or reason about their past actions -- all of which are critical in agent tasks. This raises the question: how can we design effective and efficient multi-turn RL algorithms for LLMs? In this paper, we develop a framework for building multi-turn RL algorithms for fine-tuning LLMs, that preserves the flexibility of existing single-turn RL methods for LLMs (e.g., proximal policy optimization), while accommodating multiple turns, long horizons, and delayed rewards effectively. To do this, our framework adopts a hierarchical RL approach and runs two RL algorithms in parallel: a high-level off-policy value-based RL algorithm to aggregate reward over utterances, and a low-level RL algorithm that utilizes this high-level value function to train a token policy within each utterance or turn. Our hierarchical framework, Actor-Critic Framework with a Hierarchical Structure (ArCHer), can also give rise to other RL methods. Empirically, we find that ArCHer significantly improves efficiency and performance on agent tasks, attaining a sample efficiency of about 100x over existing methods, while also improving with larger model capacity (upto the 7 billion scale that we tested on).

[Arxiv](https://arxiv.org/abs/2402.19446)