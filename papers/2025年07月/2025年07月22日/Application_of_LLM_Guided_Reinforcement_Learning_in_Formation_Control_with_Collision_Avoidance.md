# # 应用
LLM引导的强化学习在编队控制与碰撞避让中的应用

发布时间：2025年07月22日

`LLM应用` `智能体` `机器人`

> Application of LLM Guided Reinforcement Learning in Formation Control with Collision Avoidance

# 摘要

> 多智能体系统（MAS）擅长通过个体智能体的协作实现复杂目标。其中，多智能体强化学习（MARL）脱颖而出，成为最有效的算法之一。然而，当面对编队控制与避障（FCCA）这一复杂目标时，如何设计一个能够有效促进策略网络快速收敛到最优解的奖励函数，成为一大挑战。本文提出了一种新型框架，旨在克服这一挑战。通过赋予大型语言模型（LLMs）任务优先级和各智能体可观察信息的处理能力，我们的框架能够生成奖励函数，并基于更先进的评估指标而非奖励本身，根据评估结果动态在线调整这些函数。这一机制使MAS在动态环境中能够高效实现编队控制与障碍物规避，且迭代次数更少即可达到更优性能。我们在仿真和实际环境中进行的实证研究表明，所提方法具有良好的实用性和有效性。

> Multi-Agent Systems (MAS) excel at accomplishing complex objectives through the collaborative efforts of individual agents. Among the methodologies employed in MAS, Multi-Agent Reinforcement Learning (MARL) stands out as one of the most efficacious algorithms. However, when confronted with the complex objective of Formation Control with Collision Avoidance (FCCA): designing an effective reward function that facilitates swift convergence of the policy network to an optimal solution. In this paper, we introduce a novel framework that aims to overcome this challenge. By giving large language models (LLMs) on the prioritization of tasks and the observable information available to each agent, our framework generates reward functions that can be dynamically adjusted online based on evaluation outcomes by employing more advanced evaluation metrics rather than the rewards themselves. This mechanism enables the MAS to simultaneously achieve formation control and obstacle avoidance in dynamic environments with enhanced efficiency, requiring fewer iterations to reach superior performance levels. Our empirical studies, conducted in both simulation and real-world settings, validate the practicality and effectiveness of our proposed approach.

[Arxiv](https://arxiv.org/abs/2507.16382)