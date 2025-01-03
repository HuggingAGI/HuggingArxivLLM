# # 多步骤灵巧操作的模态驱动设计：神经科学的启示

发布时间：2024年12月15日

`Agent

理由：这篇论文描述了一种模块化方案，通过基于有效模态输入的专用策略来解决多步骤灵巧操作问题。这种方法涉及多个子技能的实现，包括经典控制器、视觉-语言-动作模型和带力反馈的强化学习策略。这些子技能的组合和协调体现了智能体（Agent）的概念，即通过不同的模块和策略来完成复杂任务。因此，这篇论文更适合归类为Agent。` `机器人` `家庭服务`

> Modality-Driven Design for Multi-Step Dexterous Manipulation: Insights from Neuroscience

# 摘要

> # 摘要
多步骤灵巧操作是家庭场景中的核心技能，但在机器人领域仍是一片待开发的蓝海。本文提出了一种模块化方案，通过基于有效模态输入的专用策略，分步解决操作问题，而非依赖单一的端到端模型。我们以灵巧机械手执行拾取和旋转盒子的任务为例，展示了这一方法的可行性。受神经科学的启发，我们将任务分解为三个子技能：1）接近，2）抓取与提升，以及3）手内旋转，这些子技能分别对应人类大脑中的主要感觉模态。每个子技能采用不同的方法实现：经典控制器、视觉-语言-动作模型和带力反馈的强化学习策略。我们在真实机器人上验证了该流程，证明了其可行性。本研究的核心贡献在于提出了一种受神经科学启发、模态驱动的多步骤灵巧操作方法论。

> Multi-step dexterous manipulation is a fundamental skill in household scenarios, yet remains an underexplored area in robotics. This paper proposes a modular approach, where each step of the manipulation process is addressed with dedicated policies based on effective modality input, rather than relying on a single end-to-end model. To demonstrate this, a dexterous robotic hand performs a manipulation task involving picking up and rotating a box. Guided by insights from neuroscience, the task is decomposed into three sub-skills, 1)reaching, 2)grasping and lifting, and 3)in-hand rotation, based on the dominant sensory modalities employed in the human brain. Each sub-skill is addressed using distinct methods from a practical perspective: a classical controller, a Vision-Language-Action model, and a reinforcement learning policy with force feedback, respectively. We tested the pipeline on a real robot to demonstrate the feasibility of our approach. The key contribution of this study lies in presenting a neuroscience-inspired, modality-driven methodology for multi-step dexterous manipulation.

[Arxiv](https://arxiv.org/abs/2412.11337)