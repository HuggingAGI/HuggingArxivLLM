# 统一智能体框架，用于评估条件图像生成

发布时间：2025年04月09日

`LLM应用` `计算机视觉`

> A Unified Agentic Framework for Evaluating Conditional Image Generation

# 摘要

> 条件图像生成因其个性化内容的能力而备受关注。然而，该领域在开发通用、可靠且可解释的评估指标方面仍面临挑战。本文引入了CIGEval，这是一个用于全面评估条件图像生成任务的统一智能框架。CIGEval以大型多模态模型（LMMs）为核心，集成了一个多功能工具箱，并建立了一个细粒度的评估框架。此外，我们还综合了评估轨迹用于微调，使较小规模的LMMs能够自主选择合适的工具，并根据工具输出进行细致的分析。在七项知名条件图像生成任务上的实验表明，CIGEval（GPT-4o版本）与人工评估结果达到了高度一致，相关系数为0.4625，与人工标注者之间的相关系数0.47非常接近。此外，仅使用2.3K训练轨迹，CIGEval在7B开源LMMs上的实现超越了之前基于GPT-4o的最佳方法。通过对GPT-4o图像生成的案例研究，CIGEval展现了识别主体一致性及遵循控制指导等细微问题的能力，表明其在自动化图像生成任务评估方面具有巨大的潜力，且可靠性可与人工评估相媲美。

> Conditional image generation has gained significant attention for its ability to personalize content. However, the field faces challenges in developing task-agnostic, reliable, and explainable evaluation metrics. This paper introduces CIGEval, a unified agentic framework for comprehensive evaluation of conditional image generation tasks. CIGEval utilizes large multimodal models (LMMs) as its core, integrating a multi-functional toolbox and establishing a fine-grained evaluation framework. Additionally, we synthesize evaluation trajectories for fine-tuning, empowering smaller LMMs to autonomously select appropriate tools and conduct nuanced analyses based on tool outputs. Experiments across seven prominent conditional image generation tasks demonstrate that CIGEval (GPT-4o version) achieves a high correlation of 0.4625 with human assessments, closely matching the inter-annotator correlation of 0.47. Moreover, when implemented with 7B open-source LMMs using only 2.3K training trajectories, CIGEval surpasses the previous GPT-4o-based state-of-the-art method. Case studies on GPT-4o image generation highlight CIGEval's capability in identifying subtle issues related to subject consistency and adherence to control guidance, indicating its great potential for automating evaluation of image generation tasks with human-level reliability.

[Arxiv](https://arxiv.org/abs/2504.07046)