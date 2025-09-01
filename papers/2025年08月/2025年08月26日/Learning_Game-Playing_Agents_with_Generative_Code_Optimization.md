# 基于生成式代码优化的游戏博弈智能体学习

发布时间：2025年08月26日

`Agent` `媒体与娱乐`

> Learning Game-Playing Agents with Generative Code Optimization

# 摘要

> 我们提出了一种生成式优化方法来训练游戏代理，该方法将策略表示为Python程序，并借助大型语言模型（LLMs）对其进行优化。该方法将决策策略视作自进化代码，以当前观测为输入、游戏内动作为输出，让代理能借助执行轨迹和自然语言反馈实现自我提升，且几乎无需人工干预。将其应用于雅达利（Atari）游戏时，我们的游戏Python程序性能可与深度强化学习（RL）基线相媲美，同时训练时间大幅缩短，环境交互次数也显著减少。这项研究表明，程序化策略表示在构建高效、适应性强且能进行复杂长程推理的代理方面极具潜力。

> We present a generative optimization approach for learning game-playing agents, where policies are represented as Python programs and refined using large language models (LLMs). Our method treats decision-making policies as self-evolving code, with current observation as input and an in-game action as output, enabling agents to self-improve through execution traces and natural language feedback with minimal human intervention. Applied to Atari games, our game-playing Python program achieves performance competitive with deep reinforcement learning (RL) baselines while using significantly less training time and much fewer environment interactions. This work highlights the promise of programmatic policy representations for building efficient, adaptable agents capable of complex, long-horizon reasoning.

[Arxiv](https://arxiv.org/abs/2508.19506)