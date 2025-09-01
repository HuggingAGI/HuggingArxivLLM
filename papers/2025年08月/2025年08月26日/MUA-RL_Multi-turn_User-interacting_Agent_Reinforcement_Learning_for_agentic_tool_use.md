# MUA-RL：面向智能体工具使用的多轮用户交互智能体强化学习（Multi-turn User-interacting Agent Reinforcement Learning）

发布时间：2025年08月26日

`Agent` `零售与电商` `交通运输`

> MUA-RL: Multi-turn User-interacting Agent Reinforcement Learning for agentic tool use

# 摘要

> 近年来智能体智能（Agentic Intelligence）飞速发展，大型语言模型（LLMs）的智能体工具使用也愈发关键。在智能体与用户的多轮交互中，用户需求的动态、不确定与随机性，对智能体的工具调用能力构成了严峻挑战。智能体不再是简单调用工具输出结果，而是需要通过沟通不断深化对用户需求的理解，同时调用工具解决用户问题。现有的工具使用强化学习（RL）方法在训练阶段，未能融入真实的动态用户交互。为此，我们提出了MUA-RL（智能体工具使用的多轮用户交互强化学习，Multi-turn User-interacting Agent Reinforcement Learning for agentic tool use）——这是首个在智能体工具使用领域，将大型语言模型模拟用户（LLM-simulated users）融入强化学习循环的新型框架。MUA-RL的目标是让模型自主学习，在动态多轮交互中高效与用户沟通，并调用各类工具解决实际问题。我们在多个多轮工具使用基准上开展了评估（见图1）。具体来看，MUA-RL-32B在TAU2 Retail、TAU2 Airline、TAU2 Telecom、BFCL-V3 Multi Turn和ACEBench Agent上的得分分别为67.3、45.4、28.3、28.4和82.5，在非思考模式下，其性能优于或媲美DeepSeek-V3-0324、Qwen3-235B-A22B等更大规模的开源模型。

> With the recent rapid advancement of Agentic Intelligence, agentic tool use in LLMs has become increasingly important. During multi-turn interactions between agents and users, the dynamic, uncertain, and stochastic nature of user demands poses significant challenges to the agent's tool invocation capabilities. Agents are no longer expected to simply call tools to deliver a result; rather, they must iteratively refine their understanding of user needs through communication while simultaneously invoking tools to resolve user queries. Existing reinforcement learning (RL) approaches for tool use lack the integration of genuinely dynamic users during the RL training process. To bridge this gap, we introduce MUA-RL (Multi-turn User-interacting Agent Reinforcement Learning for agentic tool use), a novel reinforcement learning framework that, for the first time in the field of agentic tool use, integrates LLM-simulated users into the reinforcement learning loop. MUA-RL aims to enable autonomous learning of models to communicate with users efficiently and use various tools to solve practical problems in dynamic multi-turn interactions. Evaluations are done on several multi-turn tool-using benchmarks (see Figure 1). Specifically, MUA-RL-32B achieves 67.3 on TAU2 Retail, 45.4 on TAU2 Airline, 28.3 on TAU2 Telecom, 28.4 on BFCL-V3 Multi Turn, and 82.5 on ACEBench Agent -- outperforming or matching the performance of larger open-source models such as DeepSeek-V3-0324 and Qwen3-235B-A22B in non-thinking settings.

[Arxiv](https://arxiv.org/abs/2508.18669)