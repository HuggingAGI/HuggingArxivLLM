# ICCO: 学习一种指令条件化的协调器，用于语言引导任务对齐的多机器人控制

发布时间：2025年03月15日

`LLM应用` `机器人` `多智能体`

> ICCO: Learning an Instruction-conditioned Coordinator for Language-guided Task-aligned Multi-robot Control

# 摘要

> 大型语言模型（LLMs）的突破推动了语言引导多机器人系统的开发，使机器人能够根据自然语言指令执行任务。然而，在分布式多智能体环境中实现有效协调仍具挑战，主要源于两点：一是指令与任务需求的不匹配；二是机器人独立解释模糊指令时行为的不一致性。为解决这些问题，我们提出了指令条件协调器（ICCO），一个旨在提升语言引导多机器人系统协调能力的多智能体强化学习（MARL）框架。ICCO由协调器智能体和本地智能体组成，协调器通过整合语言指令与环境状态生成任务对齐且一致的指令（TACI），确保任务对齐和行为一致性。协调器与本地智能体协同训练，优化平衡任务效率和指令遵循的奖励函数。我们还加入了一致性增强项，最大化指令与机器人行为之间的互信息，进一步提升协调效果。仿真和真实世界实验验证了ICCO在实现语言引导任务对齐多机器人控制方面的有效性。演示内容可访问https://yanoyoshiki.github.io/ICCO/查看。

> Recent advances in Large Language Models (LLMs) have permitted the development of language-guided multi-robot systems, which allow robots to execute tasks based on natural language instructions. However, achieving effective coordination in distributed multi-agent environments remains challenging due to (1) misalignment between instructions and task requirements and (2) inconsistency in robot behaviors when they independently interpret ambiguous instructions. To address these challenges, we propose Instruction-Conditioned Coordinator (ICCO), a Multi-Agent Reinforcement Learning (MARL) framework designed to enhance coordination in language-guided multi-robot systems. ICCO consists of a Coordinator agent and multiple Local Agents, where the Coordinator generates Task-Aligned and Consistent Instructions (TACI) by integrating language instructions with environmental states, ensuring task alignment and behavioral consistency. The Coordinator and Local Agents are jointly trained to optimize a reward function that balances task efficiency and instruction following. A Consistency Enhancement Term is added to the learning objective to maximize mutual information between instructions and robot behaviors, further improving coordination. Simulation and real-world experiments validate the effectiveness of ICCO in achieving language-guided task-aligned multi-robot control. The demonstration can be found at https://yanoyoshiki.github.io/ICCO/.

[Arxiv](https://arxiv.org/abs/2503.12122)