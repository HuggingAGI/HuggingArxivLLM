# Sora生成视频中简单视觉伪影检测

发布时间：2025年04月30日

`LLM应用

LLM应用` `视频合成` `视频质量评估`

> Simple Visual Artifact Detection in Sora-Generated Videos

# 摘要

> OpenAI于2024年12月发布的Sora视频生成模型，作为一款由自然语言驱动的强大工具，标志着生成模型与视频合成领域间正在形成一种新的融合趋势。随着多模态系统逐步演变为能够理解、生成并交互视觉内容的视频增强型LLMs（ VidLLMs），我们亟需深入理解其局限性并确保其安全可靠地投入使用。本研究聚焦于Sora生成视频中频繁出现且被广泛报告的视觉缺陷，这些缺陷可能影响视频质量、误导观众或传播虚假信息。我们提出了一种针对四种常见视觉缺陷的多标签分类框架：标签1：边界/边缘缺陷，标签2：纹理/噪声问题，标签3：运动/关节异常，标签4：物体错位/消失。基于从15个Sora生成视频中手动标注的300帧数据集，我们训练了多种2D卷积神经网络架构（ResNet-50、EfficientNet-B3/B4、ViT-Base）。其中，基于ResNet-50训练的最优模型在多标签分类任务中达到了94.14%的平均准确率。这项研究为 VidLLMs 的发展做出了贡献，具体体现在：(1) 创建用于视频质量评估的数据集，(2) 提供超越语言指标的可解释性缺陷分析，(3) 识别与事实性和安全性相关的视觉风险。

> The December 2024 release of OpenAI's Sora, a powerful video generation model driven by natural language prompts, highlights a growing convergence between large language models (LLMs) and video synthesis. As these multimodal systems evolve into video-enabled LLMs (VidLLMs), capable of interpreting, generating, and interacting with visual content, understanding their limitations and ensuring their safe deployment becomes essential. This study investigates visual artifacts frequently found and reported in Sora-generated videos, which can compromise quality, mislead viewers, or propagate disinformation. We propose a multi-label classification framework targeting four common artifact label types: label 1: boundary / edge defects, label 2: texture / noise issues, label 3: movement / joint anomalies, and label 4: object mismatches / disappearances. Using a dataset of 300 manually annotated frames extracted from 15 Sora-generated videos, we trained multiple 2D CNN architectures (ResNet-50, EfficientNet-B3 / B4, ViT-Base). The best-performing model trained by ResNet-50 achieved an average multi-label classification accuracy of 94.14%. This work supports the broader development of VidLLMs by contributing to (1) the creation of datasets for video quality evaluation, (2) interpretable artifact-based analysis beyond language metrics, and (3) the identification of visual risks relevant to factuality and safety.

[Arxiv](https://arxiv.org/abs/2504.21334)