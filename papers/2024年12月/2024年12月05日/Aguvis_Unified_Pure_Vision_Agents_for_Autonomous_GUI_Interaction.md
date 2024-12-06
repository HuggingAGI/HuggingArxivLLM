# Aguvis：用于自主 GUI 交互的统一纯视觉代理

发布时间：2024年12月05日

`Agent` `人机交互` `图形用户界面`

> Aguvis: Unified Pure Vision Agents for Autonomous GUI Interaction

# 摘要

> 图形用户界面（GUIs）在人机交互中至关重要，然而，因视觉环境复杂多变，自动化 GUI 任务颇具挑战。现有的方法往往依赖于 GUI 的文本表述，这在泛化、效率和可扩展性上存在局限。本文中，我们推出了 Aguvis，这是一个适用于自治 GUI 代理、能在多种平台运行的统一纯视觉框架。我们的方法借助基于图像的观察，将自然语言中的指令与视觉元素相融合，并运用一致的动作空间来保障跨平台泛化。为克服以往工作的不足，我们在模型内融入了明确的规划和推理，增强其自主导航及与复杂数字环境交互的能力。我们构建了大规模的 GUI 代理轨迹数据集，涵盖了多模态推理和基础，并采用了两阶段训练流程，先是侧重于通用的 GUI 基础，接着是规划和推理。通过全面实验，我们表明 Aguvis 在离线和现实在线场景中均超越了以往的先进方法，据我们所知，它是首个能够独立执行任务、无需与外部闭源模型合作的完全自主的纯视觉 GUI 代理。我们在 https://aguvis-project.github.io/ 开源了所有数据集、模型和训练配方，以助力未来的研究。

> Graphical User Interfaces (GUIs) are critical to human-computer interaction, yet automating GUI tasks remains challenging due to the complexity and variability of visual environments. Existing approaches often rely on textual representations of GUIs, which introduce limitations in generalization, efficiency, and scalability. In this paper, we introduce Aguvis, a unified pure vision-based framework for autonomous GUI agents that operates across various platforms. Our approach leverages image-based observations, and grounding instructions in natural language to visual elements, and employs a consistent action space to ensure cross-platform generalization. To address the limitations of previous work, we integrate explicit planning and reasoning within the model, enhancing its ability to autonomously navigate and interact with complex digital environments. We construct a large-scale dataset of GUI agent trajectories, incorporating multimodal reasoning and grounding, and employ a two-stage training pipeline that first focuses on general GUI grounding, followed by planning and reasoning. Through comprehensive experiments, we demonstrate that Aguvis surpasses previous state-of-the-art methods in both offline and real-world online scenarios, achieving, to our knowledge, the first fully autonomous pure vision GUI agent capable of performing tasks independently without collaboration with external closed-source models. We open-sourced all datasets, models, and training recipes to facilitate future research at https://aguvis-project.github.io/.

[Arxiv](https://arxiv.org/abs/2412.04454)