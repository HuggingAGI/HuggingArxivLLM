# TGPO：树引导偏好优化助力鲁棒网络智能体强化学习

发布时间：2025年09月18日

`Agent` `零售与电商`

> TGPO: Tree-Guided Preference Optimization for Robust Web Agent Reinforcement Learning

# 摘要

> 随着大型语言模型与视觉-语言模型的飞速发展，将大型模型部署为Web智能体已成为实现自动化Web交互的核心需求。然而，采用强化学习训练Web智能体时，仍面临信用分配错位、标注成本过高及奖励稀疏等关键难题。为应对这些问题，我们提出树引导偏好优化（TGPO）——一种离线强化学习框架，其核心是树状轨迹表示：通过合并不同轨迹中语义相同的状态，消除标签冲突。该框架内置过程奖励模型，可通过子目标进展追踪、冗余检测与动作验证，自动生成细粒度奖励。此外，动态加权机制能在训练中对高影响决策点进行优先级排序。在Online-Mind2Web数据集及我们自建的C-WebShop数据集上的实验显示，TGPO显著优于现有方法，不仅成功率更高，冗余步骤也更少。

> With the rapid advancement of large language models and vision-language models, employing large models as Web Agents has become essential for automated web interaction. However, training Web Agents with reinforcement learning faces critical challenges including credit assignment misallocation, prohibitively high annotation costs, and reward sparsity. To address these issues, we propose Tree-Guided Preference Optimization (TGPO), an offline reinforcement learning framework that proposes a tree-structured trajectory representation merging semantically identical states across trajectories to eliminate label conflicts. Our framework incorporates a Process Reward Model that automatically generates fine-grained rewards through subgoal progress, redundancy detection, and action verification. Additionally, a dynamic weighting mechanism prioritizes high-impact decision points during training. Experiments on Online-Mind2Web and our self-constructed C-WebShop datasets demonstrate that TGPO significantly outperforms existing methods, achieving higher success rates with fewer redundant steps.

[Arxiv](https://arxiv.org/abs/2509.14172)