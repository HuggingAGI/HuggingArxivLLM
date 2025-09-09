# PolicyEvolve：基于种群训练的LLMs多人游戏程序化策略进化

发布时间：2025年09月07日

`强化学习` `媒体与娱乐`

> PolicyEvolve: Evolving Programmatic Policies by LLMs for multi-player games via Population-Based Training

# 摘要

> 多智能体强化学习（MARL）借助自对弈，在攻克复杂多人游戏难题上成效显著。但训练高效的对抗策略不仅需要数百万经验样本，还得消耗海量计算资源。更关键的是，这些策略缺乏可解释性，严重制约了实际落地。近来，研究人员借助大型语言模型（LLMs）成功为单智能体任务生成程序化策略，将神经网络策略转化为可解释的规则式代码，执行效率也大幅提升。受此启发，我们提出通用框架PolicyEvolve，专门用于生成多人游戏中的程序化策略。该框架大幅降低了对手工编写策略代码的依赖，仅需极少的环境交互就能生成高性能策略。

PolicyEvolve包含四个核心模块：Global Pool（全局池）、Local Pool（局部池）、Policy Planner（策略规划器）和Trajectory Critic（轨迹评论家）。其中，Global Pool负责存储迭代训练中积累的精英策略；Local Pool则存放当前迭代的临时策略，只有性能达标的策略才会被选入Global Pool。作为核心生成模块，Policy Planner从Global Pool中选取排名前三的策略，结合环境信息生成初始策略，再根据Trajectory Critic的反馈进行优化，优化后的策略随即存入Local Pool。这一迭代过程不断循环，直至策略对Global Pool的平均胜率达标，随即被纳入Global Pool。而Trajectory Critic的作用是分析当前策略的交互数据，找出薄弱环节并提出改进方向，为Policy Planner提供精准指导。

> Multi-agent reinforcement learning (MARL) has achieved significant progress in solving complex multi-player games through self-play. However, training effective adversarial policies requires millions of experience samples and substantial computational resources. Moreover, these policies lack interpretability, hindering their practical deployment. Recently, researchers have successfully leveraged Large Language Models (LLMs) to generate programmatic policies for single-agent tasks, transforming neural network-based policies into interpretable rule-based code with high execution efficiency. Inspired by this, we propose PolicyEvolve, a general framework for generating programmatic policies in multi-player games. PolicyEvolve significantly reduces reliance on manually crafted policy code, achieving high-performance policies with minimal environmental interactions. The framework comprises four modules: Global Pool, Local Pool, Policy Planner, and Trajectory Critic. The Global Pool preserves elite policies accumulated during iterative training. The Local Pool stores temporary policies for the current iteration; only sufficiently high-performing policies from this pool are promoted to the Global Pool. The Policy Planner serves as the core policy generation module. It samples the top three policies from the Global Pool, generates an initial policy for the current iteration based on environmental information, and refines this policy using feedback from the Trajectory Critic. Refined policies are then deposited into the Local Pool. This iterative process continues until the policy achieves a sufficiently high average win rate against the Global Pool, at which point it is integrated into the Global Pool. The Trajectory Critic analyzes interaction data from the current policy, identifies vulnerabilities, and proposes directional improvements to guide the Policy Planner

[Arxiv](https://arxiv.org/abs/2509.06053)