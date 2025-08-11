# PhysPatch：一种物理可实现且可迁移的对抗补丁攻击方法，针对基于多模态大型语言模型的自动驾驶系统。

发布时间：2025年08月07日

`LLM应用` `自动驾驶` `自动驾驶安全`

> PhysPatch: A Physically Realizable and Transferable Adversarial Patch Attack for Multimodal Large Language Models-based Autonomous Driving Systems

# 摘要

> 多模态大型语言模型（MLLMs）凭借其强大的视觉-语言推理能力，正在成为自动驾驶（AD）系统的重要组成部分。然而，MLLMs易受对抗攻击，尤其是对抗补丁攻击，在现实场景中可能带来严重威胁。现有基于补丁的攻击方法主要针对目标检测模型，应用于MLLMs时表现不佳，原因在于MLLMs复杂的架构和推理能力。为解决这一问题，我们提出了一种专为基于MLLMs的AD系统设计的对抗补丁框架——PhysPatch，具有可实现性和可迁移性。该框架通过优化补丁的位置、形状和内容，提升攻击效果和现实适用性。它引入了基于语义的掩码初始化策略，实现真实的补丁放置；基于SVD的局部对齐损失，结合补丁引导的裁剪-调整大小操作，以提升迁移能力；以及基于势场的掩码优化方法。在开源、商业和具有推理能力的MLLMs上的广泛实验表明，PhysPatch在引导MLLMs的AD系统实现目标对齐的感知和规划输出方面，显著优于现有方法。此外，PhysPatch始终将对抗补丁放置在AD场景中物理可行的区域，确保了其强大的现实适用性和可部署性。

> Multimodal Large Language Models (MLLMs) are becoming integral to autonomous driving (AD) systems due to their strong vision-language reasoning capabilities. However, MLLMs are vulnerable to adversarial attacks, particularly adversarial patch attacks, which can pose serious threats in real-world scenarios. Existing patch-based attack methods are primarily designed for object detection models and perform poorly when transferred to MLLM-based systems due to the latter's complex architectures and reasoning abilities. To address these limitations, we propose PhysPatch, a physically realizable and transferable adversarial patch framework tailored for MLLM-based AD systems. PhysPatch jointly optimizes patch location, shape, and content to enhance attack effectiveness and real-world applicability. It introduces a semantic-based mask initialization strategy for realistic placement, an SVD-based local alignment loss with patch-guided crop-resize to improve transferability, and a potential field-based mask refinement method. Extensive experiments across open-source, commercial, and reasoning-capable MLLMs demonstrate that PhysPatch significantly outperforms prior methods in steering MLLM-based AD systems toward target-aligned perception and planning outputs. Moreover, PhysPatch consistently places adversarial patches in physically feasible regions of AD scenes, ensuring strong real-world applicability and deployability.

[Arxiv](https://arxiv.org/abs/2508.05167)