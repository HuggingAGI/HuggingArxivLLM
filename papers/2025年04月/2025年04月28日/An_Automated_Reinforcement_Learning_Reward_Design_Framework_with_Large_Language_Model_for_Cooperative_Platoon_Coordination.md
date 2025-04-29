# 基于大型语言模型的自动化强化学习奖励设计框架，用于合作车队协调

发布时间：2025年04月28日

`LLM应用` `交通管理`

> An Automated Reinforcement Learning Reward Design Framework with Large Language Model for Cooperative Platoon Coordination

# 摘要

> 强化学习（RL）在车队协调问题中表现优异，但设计高性能奖励函数仍具挑战性。本文正式定义了车队协调奖励函数设计问题（PCRDP），并提出基于LLM的PCRD框架，通过系统性自动化发现和优化奖励函数，解决复杂车队协调难题。通过AIR模块和进化模块的协同工作，PCRD框架在长三角交通网络模拟中验证了其有效性，实验结果表明其性能优于传统方法，平均提升达10%。

> Reinforcement Learning (RL) has demonstrated excellent decision-making potential in platoon coordination problems. However, due to the variability of coordination goals, the complexity of the decision problem, and the time-consumption of trial-and-error in manual design, finding a well performance reward function to guide RL training to solve complex platoon coordination problems remains challenging. In this paper, we formally define the Platoon Coordination Reward Design Problem (PCRDP), extending the RL-based cooperative platoon coordination problem to incorporate automated reward function generation. To address PCRDP, we propose a Large Language Model (LLM)-based Platoon coordination Reward Design (PCRD) framework, which systematically automates reward function discovery through LLM-driven initialization and iterative optimization. In this method, LLM first initializes reward functions based on environment code and task requirements with an Analysis and Initial Reward (AIR) module, and then iteratively optimizes them based on training feedback with an evolutionary module. The AIR module guides LLM to deepen their understanding of code and tasks through a chain of thought, effectively mitigating hallucination risks in code generation. The evolutionary module fine-tunes and reconstructs the reward function, achieving a balance between exploration diversity and convergence stability for training. To validate our approach, we establish six challenging coordination scenarios with varying complexity levels within the Yangtze River Delta transportation network simulation. Comparative experimental results demonstrate that RL agents utilizing PCRD-generated reward functions consistently outperform human-engineered reward functions, achieving an average of 10\% higher performance metrics in all scenarios.

[Arxiv](https://arxiv.org/abs/2504.19480)