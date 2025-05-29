# 面向具身交互的通用视触觉视频理解

发布时间：2025年05月28日

`LLM应用` `触觉感知` `人机交互`

> Universal Visuo-Tactile Video Understanding for Embodied Interaction

# 摘要

> 触觉感知对具身智能体理解物体物理属性至关重要，仅凭视觉无法完全掌握这些属性。尽管现有方法在视觉和语言模态方面有所进展，但它们未能有效整合触觉信息，这对于现实世界的交互至关重要。本文中，我们提出了VTV-LLM，这是首个针对通用视觉-触觉视频（VTV）理解的多模态大型语言模型，填补了触觉感知与自然语言之间的鸿沟。为了解决跨传感器和跨模态整合的挑战，我们贡献了VTV150K，这是一个全面的数据集，包含来自100个不同物体的150,000个视频帧，这些物体通过三种不同的触觉传感器（GelSight Mini、DIGIT 和 Tac3D）捕获，并标注了四种基本触觉属性（硬度、凸起、弹性和摩擦力）。我们开发了一种创新的三阶段训练范式，包括VTV增强以实现鲁棒的视觉触觉表示、VTV-文本对齐以实现跨模态对应以及文本提示微调以实现自然语言生成。我们的框架实现了复杂的触觉推理能力，包括特征评估、比较分析、基于场景的决策等。实验评估表明，VTV-LLM在触觉视频理解任务中取得了卓越性能，为触觉领域中更直观的人机交互奠定了基础。

> Tactile perception is essential for embodied agents to understand physical attributes of objects that cannot be determined through visual inspection alone. While existing approaches have made progress in visual and language modalities for physical understanding, they fail to effectively incorporate tactile information that provides crucial haptic feedback for real-world interaction. In this paper, we present VTV-LLM, the first multi-modal large language model for universal Visuo-Tactile Video (VTV) understanding that bridges the gap between tactile perception and natural language. To address the challenges of cross-sensor and cross-modal integration, we contribute VTV150K, a comprehensive dataset comprising 150,000 video frames from 100 diverse objects captured across three different tactile sensors (GelSight Mini, DIGIT, and Tac3D), annotated with four fundamental tactile attributes (hardness, protrusion, elasticity, and friction). We develop a novel three-stage training paradigm that includes VTV enhancement for robust visuo-tactile representation, VTV-text alignment for cross-modal correspondence, and text prompt finetuning for natural language generation. Our framework enables sophisticated tactile reasoning capabilities including feature assessment, comparative analysis, scenario-based decision making and so on. Experimental evaluations demonstrate that VTV-LLM achieves superior performance in tactile video understanding tasks, establishing a foundation for more intuitive human-machine interaction in tactile domains.

[Arxiv](https://arxiv.org/abs/2505.22566)