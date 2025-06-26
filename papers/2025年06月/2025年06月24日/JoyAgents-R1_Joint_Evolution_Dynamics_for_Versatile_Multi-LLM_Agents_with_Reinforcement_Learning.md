# JoyAgents-R1: 研究多LLM智能体的协同进化机制及其多样化能力，结合强化学习进行优化

发布时间：2025年06月24日

`Agent` `人工智能`

> JoyAgents-R1: Joint Evolution Dynamics for Versatile Multi-LLM Agents with Reinforcement Learning

# 摘要

> 多智能体强化学习（MARL）已成为处理日益复杂任务的重要方法。然而，在异质智能体中实现联合进化仍然具有挑战性，主要源于协作效率低下和训练不稳定的问题。本文提出了一种名为JoyAgents-R1的联合进化动力学方法，首次将组相对策略优化（GRPO）应用于异质多智能体的联合训练。通过迭代优化智能体的大语言模型（LLMs）和记忆，该方法实现了整体平衡，具备最优决策能力和记忆功能。具体而言，JoyAgents-R1首先在每个智能体的整个推理轨迹上实施基于节点的蒙特卡罗采样，以提高GRPO采样效率，同时保持策略多样性。然后，我们的边际效益驱动选择策略识别具有最大奖励波动的前$K$个采样组，从而实现针对性的智能体模型更新，通过成本有效的参数调整提高训练稳定性并最大化联合效益。同时，JoyAgents-R1引入了一种自适应记忆进化机制，将GRPO奖励重新用作无成本的监督信号，以消除重复推理并加速收敛。在通用和特定领域场景下的实验表明，JoyAgents-R1在性能上可与更大的LLMs相媲美，而其构建基于更小型的开源模型。

> Multi-agent reinforcement learning (MARL) has emerged as a prominent paradigm for increasingly complex tasks. However, joint evolution across heterogeneous agents remains challenging due to cooperative inefficiency and training instability. In this paper, we propose the joint evolution dynamics for MARL called JoyAgents-R1, which first applies Group Relative Policy Optimization (GRPO) to the joint training of heterogeneous multi-agents. By iteratively refining agents' large language models (LLMs) and memories, the method achieves holistic equilibrium with optimal decision-making and memory capabilities. Specifically, JoyAgents-R1 first implements node-wise Monte Carlo sampling on the behavior of each agent across entire reasoning trajectories to enhance GRPO sampling efficiency while maintaining policy diversity. Then, our marginal benefit-driven selection strategy identifies top-$K$ sampling groups with maximal reward fluctuations, enabling targeted agent model updates that improve training stability and maximize joint benefits through cost-effective parameter adjustments. Meanwhile, JoyAgents-R1 introduces an adaptive memory evolution mechanism that repurposes GRPO rewards as cost-free supervisory signals to eliminate repetitive reasoning and accelerate convergence. Experiments across general and domain-specific scenarios demonstrate that JoyAgents-R1 achieves performance comparable to that of larger LLMs while built on smaller open-source models.

[Arxiv](https://arxiv.org/abs/2506.19846)