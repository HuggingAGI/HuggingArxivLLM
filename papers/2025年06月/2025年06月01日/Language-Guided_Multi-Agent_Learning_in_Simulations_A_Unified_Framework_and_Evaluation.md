# 语言引导的多智能体学习在模拟中的统一框架与评估

发布时间：2025年06月01日

`Agent` `多智能体系统`

> Language-Guided Multi-Agent Learning in Simulations: A Unified Framework and Evaluation

# 摘要

> 本文提出了一种名为LLM-MARL的统一框架，将大型语言模型（LLMs）与多智能体强化学习（MARL）相结合，旨在提升模拟游戏环境中的协调性、通信能力和泛化能力。该框架由三个模块化组件构成：协调器、通信器和记忆模块，分别负责动态生成子目标、促进智能体间的符号化通信以及支持 episodic 回忆功能。训练方法采用了结合PPO算法与语言条件损失的策略，并引入了LLM查询门控机制。在Google Research Football、MAgent Battle和StarCraft II等环境中进行的评估表明，LLM-MARL在胜率、协调得分和零样本泛化方面均显著优于MAPPO和QMIX。消融研究进一步证明，子目标生成和基于语言的通信机制对性能提升起到了关键作用。定性分析还揭示了角色专业化和通信驱动策略等涌现行为。通过将语言建模与策略学习相结合，这项研究为设计智能、协作的交互式模拟智能体提供了新思路，并为在训练、游戏和人机协作等多智能体系统中有效利用LLMs指明了方向。

> This paper introduces LLM-MARL, a unified framework that incorporates large language models (LLMs) into multi-agent reinforcement learning (MARL) to enhance coordination, communication, and generalization in simulated game environments. The framework features three modular components of Coordinator, Communicator, and Memory, which dynamically generate subgoals, facilitate symbolic inter-agent messaging, and support episodic recall. Training combines PPO with a language-conditioned loss and LLM query gating. LLM-MARL is evaluated in Google Research Football, MAgent Battle, and StarCraft II. Results show consistent improvements over MAPPO and QMIX in win rate, coordination score, and zero-shot generalization. Ablation studies demonstrate that subgoal generation and language-based messaging each contribute significantly to performance gains. Qualitative analysis reveals emergent behaviors such as role specialization and communication-driven tactics. By bridging language modeling and policy learning, this work contributes to the design of intelligent, cooperative agents in interactive simulations. It offers a path forward for leveraging LLMs in multi-agent systems used for training, games, and human-AI collaboration.

[Arxiv](https://arxiv.org/abs/2506.04251)