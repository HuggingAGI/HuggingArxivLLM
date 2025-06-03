# 机器人-R1：强化学习助力增强机器人具身推理

发布时间：2025年05月29日

`LLM应用` `机器人技术` `人工智能`

> Robot-R1: Reinforcement Learning for Enhanced Embodied Reasoning in Robotics

# 摘要

> 大型视觉-语言模型（LVLMs）在结合具身推理与机器人控制方面展现出了巨大的潜力，为机器人技术的发展注入了新的活力。目前，研究者们常用监督微调（SFT）方法在与机器人控制相关的具身推理任务上进行训练。然而，SFT数据集通常基于启发式构建，并未针对机器人控制性能进行优化。此外，监督微调还常常导致灾难性遗忘和泛化性能下降等问题。

为了解决这些局限，我们提出了一个全新的框架——Robot-R1。该框架利用强化学习，专门针对机器人控制中的具身推理能力进行优化。具体来说，Robot-R1能够基于当前场景图像和从专家演示中提取的环境元数据，学习预测任务完成所需的下一个关键点状态。受DeepSeek-R1学习方法的启发，Robot-R1通过采样推理型响应，并强化那些能带来更准确预测的响应。

实验结果表明，使用Robot-R1训练的模型在具身推理任务上显著优于传统的SFT方法。令人惊喜的是，尽管仅有70亿参数，Robot-R1在与低级动作控制相关的推理任务（如空间和原始运动推理）上甚至超越了GPT-4o。


> Large Vision-Language Models (LVLMs) have recently shown great promise in advancing robotics by combining embodied reasoning with robot control. A common approach involves training on embodied reasoning tasks related to robot control using Supervised Fine-Tuning (SFT). However, SFT datasets are often heuristically constructed and not explicitly optimized for improving robot control. Furthermore, SFT often leads to issues such as catastrophic forgetting and reduced generalization performance. To address these limitations, we introduce Robot-R1, a novel framework that leverages reinforcement learning to enhance embodied reasoning specifically for robot control. Robot-R1 learns to predict the next keypoint state required for task completion, conditioned on the current scene image and environment metadata derived from expert demonstrations. Inspired by the DeepSeek-R1 learning approach, Robot-R1 samples reasoning-based responses and reinforces those that lead to more accurate predictions. Our experiments show that models trained with Robot-R1 outperform SFT methods on embodied reasoning tasks. Despite having only 7B parameters, Robot-R1 even surpasses GPT-4o on reasoning tasks related to low-level action control, such as spatial and primitive movement reasoning.

[Arxiv](https://arxiv.org/abs/2506.00070)