# 通过大型语言模型实现自动化混合奖励调度，用于机器人技能学习

发布时间：2025年05月05日

`LLM应用` `机器人` `人工智能`

> Automated Hybrid Reward Scheduling via Large Language Models for Robotic Skill Learning

# 摘要

> 高自由度机器人学习特定技能充满挑战，这主要源于机器人动力学的复杂性。强化学习（RL）作为一项有前景的技术应运而生，但解决这类问题需要设计多个奖励函数来应对机器人运动中的各种约束。现有方法通常不加选择地将所有奖励组件相加来优化RL价值函数和策略。我们认为，这种在策略优化中对所有奖励组件一概而论的做法效率低下，限制了机器人的学习效果。为此，我们提出了一种基于大型语言模型（LLMs）的自动化混合奖励调度（AHRS）框架。该框架通过动态调整各奖励组件的学习强度，使机器人能够以循序渐进的方式掌握技能。具体而言，我们设计了一个多分支价值网络，每个分支对应不同的奖励组件。在策略优化过程中，每个分支都会被赋予一个反映其重要性的权重，这些权重由LLM设计的规则自动计算得出。LLM会根据任务描述提前生成一套规则，在训练时，它会根据评估各分支性能的语言提示，从规则库中选择合适的权重计算规则。实验结果表明，AHRS方法在多个高自由度机器人任务中实现了平均6.48%的性能提升。

> Enabling a high-degree-of-freedom robot to learn specific skills is a challenging task due to the complexity of robotic dynamics. Reinforcement learning (RL) has emerged as a promising solution; however, addressing such problems requires the design of multiple reward functions to account for various constraints in robotic motion. Existing approaches typically sum all reward components indiscriminately to optimize the RL value function and policy. We argue that this uniform inclusion of all reward components in policy optimization is inefficient and limits the robot's learning performance. To address this, we propose an Automated Hybrid Reward Scheduling (AHRS) framework based on Large Language Models (LLMs). This paradigm dynamically adjusts the learning intensity of each reward component throughout the policy optimization process, enabling robots to acquire skills in a gradual and structured manner. Specifically, we design a multi-branch value network, where each branch corresponds to a distinct reward component. During policy optimization, each branch is assigned a weight that reflects its importance, and these weights are automatically computed based on rules designed by LLMs. The LLM generates a rule set in advance, derived from the task description, and during training, it selects a weight calculation rule from the library based on language prompts that evaluate the performance of each branch. Experimental results demonstrate that the AHRS method achieves an average 6.48% performance improvement across multiple high-degree-of-freedom robotic tasks.

[Arxiv](https://arxiv.org/abs/2505.02483)