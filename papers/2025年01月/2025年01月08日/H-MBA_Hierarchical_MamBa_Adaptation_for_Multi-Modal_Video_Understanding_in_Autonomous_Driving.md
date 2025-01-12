# H-MBA: 分层 MamBa 适应方法在自动驾驶多模态视频理解中的应用

发布时间：2025年01月08日

`LLM应用

**理由**：这篇论文主要讨论了多模态大型语言模型（MLLMs）在自动驾驶领域的应用，特别是通过提出的H-MBA框架来提升视频理解能力。论文的核心是应用MLLMs来解决实际问题，因此属于LLM应用类别。` `自动驾驶` `视频理解`

> H-MBA: Hierarchical MamBa Adaptation for Multi-Modal Video Understanding in Autonomous Driving

# 摘要

> 随着多模态大型语言模型（MLLMs）的广泛应用，自动驾驶领域迎来了新的机遇与挑战。其中，多模态视频理解对于实时分析自动驾驶过程中的潜在事件至关重要。然而，动态场景中的视频往往包含复杂的时空运动，这限制了现有MLLMs在该领域的泛化能力。为此，我们提出了一种创新的分层Mamba适应（H-MBA）框架，以应对自动驾驶视频中的复杂运动变化。H-MBA由两个核心模块组成：上下文Mamba（C-Mamba）和查询Mamba（Q-Mamba）。C-Mamba通过多种结构状态空间模型，有效捕捉不同时间分辨率下的多粒度视频上下文；Q-Mamba则灵活地将当前帧转化为可学习的查询，并智能选择多粒度视频上下文进行整合。通过自适应融合多尺度时间分辨率的视频上下文，H-MBA显著提升了视频理解能力。在MLLMs的即插即用模式下，H-MBA在自动驾驶的多模态视频任务中表现卓越，例如在风险物体检测任务中，其mIoU比现有SOTA方法提升了5.5%。

> With the prevalence of Multimodal Large Language Models(MLLMs), autonomous driving has encountered new opportunities and challenges. In particular, multi-modal video understanding is critical to interactively analyze what will happen in the procedure of autonomous driving. However, videos in such a dynamical scene that often contains complex spatial-temporal movements, which restricts the generalization capacity of the existing MLLMs in this field. To bridge the gap, we propose a novel Hierarchical Mamba Adaptation (H-MBA) framework to fit the complicated motion changes in autonomous driving videos. Specifically, our H-MBA consists of two distinct modules, including Context Mamba (C-Mamba) and Query Mamba (Q-Mamba). First, C-Mamba contains various types of structure state space models, which can effectively capture multi-granularity video context for different temporal resolutions. Second, Q-Mamba flexibly transforms the current frame as the learnable query, and attentively selects multi-granularity video context into query. Consequently, it can adaptively integrate all the video contexts of multi-scale temporal resolutions to enhance video understanding. Via a plug-and-play paradigm in MLLMs, our H-MBA shows the remarkable performance on multi-modal video tasks in autonomous driving, e.g., for risk object detection, it outperforms the previous SOTA method with 5.5% mIoU improvement.

[Arxiv](https://arxiv.org/abs/2501.04302)