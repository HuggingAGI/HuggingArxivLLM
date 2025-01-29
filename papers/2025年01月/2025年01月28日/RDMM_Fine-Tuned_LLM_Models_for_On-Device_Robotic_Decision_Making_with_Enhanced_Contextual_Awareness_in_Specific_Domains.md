# RDMM：特定领域增强上下文感知的设备端机器人决策微调LLM模型

发布时间：2025年01月28日

`Agent

理由：这篇论文描述了一个名为RDMM（机器人决策模型）的框架，该框架旨在提升机器人在实际场景中的自主决策能力。它集成了视觉感知模型和实时语音识别，专注于实时、设备端的解决方案，并且能够在资源受限的硬件上运行。这些特征表明该研究属于Agent领域，因为它涉及智能体（机器人）在复杂环境中的自主决策和行为优化。` `机器人` `人工智能`

> RDMM: Fine-Tuned LLM Models for On-Device Robotic Decision Making with Enhanced Contextual Awareness in Specific Domains

# 摘要

> 大型语言模型（LLMs）在物理机器人与AI系统的融合中迈出了重要一步。我们在家庭竞赛的实际场景中展示了框架的强大功能。本研究提出的RDMM（机器人决策模型）框架，不仅能在特定领域内做出决策，还能自我认知其知识与能力。该框架通过信息利用，提升了系统的自主决策能力。与现有方法不同，我们专注于实时、设备端的解决方案，成功在仅8GB内存的硬件上运行。框架集成了视觉感知模型，赋予机器人环境理解能力，并配备了实时语音识别，优化了人机交互体验。实验数据显示，RDMM框架的规划准确率高达93%。我们还发布了一个包含27k规划实例和1.3k文本-图像注释样本的新数据集。所有框架、基准、数据集和模型均已开源，详见GitHub仓库：https://github.com/shadynasrat/RDMM。

> Large language models (LLMs) represent a significant advancement in integrating physical robots with AI-driven systems. We showcase the capabilities of our framework within the context of the real-world household competition. This research introduces a framework that utilizes RDMM (Robotics Decision-Making Models), which possess the capacity for decision-making within domain-specific contexts, as well as an awareness of their personal knowledge and capabilities. The framework leverages information to enhance the autonomous decision-making of the system. In contrast to other approaches, our focus is on real-time, on-device solutions, successfully operating on hardware with as little as 8GB of memory. Our framework incorporates visual perception models equipping robots with understanding of their environment. Additionally, the framework has integrated real-time speech recognition capabilities, thus enhancing the human-robot interaction experience. Experimental results demonstrate that the RDMM framework can plan with an 93\% accuracy. Furthermore, we introduce a new dataset consisting of 27k planning instances, as well as 1.3k text-image annotated samples derived from the competition. The framework, benchmarks, datasets, and models developed in this work are publicly available on our GitHub repository at https://github.com/shadynasrat/RDMM.

[Arxiv](https://arxiv.org/abs/2501.16899)