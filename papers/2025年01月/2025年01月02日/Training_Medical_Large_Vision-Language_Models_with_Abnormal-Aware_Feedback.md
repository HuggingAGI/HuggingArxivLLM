# 训练医学大型视觉-语言模型：异常感知反馈的应用

发布时间：2025年01月02日

`LLM应用

理由：这篇论文主要讨论了如何利用大型视觉-语言模型（Med-LVLMs）在医学图像理解和基于图像的问答任务中的应用，特别是通过两阶段训练方法来增强医学异常检测和解释能力。虽然涉及了视觉定位和异常检测，但其核心是利用GPT-4V生成的提示和训练方法来提升模型在医学领域的应用效果，因此属于LLM应用范畴。` `医学图像分析`

> Training Medical Large Vision-Language Models with Abnormal-Aware Feedback

# 摘要

> 现有的医学大型视觉-语言模型（Med-LVLMs）集成了丰富的医学知识，在医学图像理解和基于图像的问答任务中表现出色。然而，医学图像中的视觉定位问题仍是挑战，这对异常检测和解释至关重要。为此，我们提出了UMed-LVLM，专注于揭示医学异常。我们收集了医学异常揭示（MAU）数据集，并设计了两阶段训练方法。通过GPT-4V生成的提示，我们基于医学图像中的异常区域生成诊断。两阶段训练包括异常感知指令微调和异常感知奖励（含异常定位奖励和视觉相关性奖励）。实验表明，UMed-LVLM在医学异常识别和理解上优于现有Med-LVLMs。此外，增强异常检测能力显著提升了Med-LVLMs的医学图像理解和泛化能力。

> Existing Medical Large Vision-Language Models (Med-LVLMs), which encapsulate extensive medical knowledge, demonstrate excellent capabilities in understanding medical images and responding to human queries based on these images. However, there remain challenges in visual localization in medical images, which is crucial for abnormality detection and interpretation. To address these issues, we propose a novel UMed-LVLM designed with Unveiling Medical abnormalities. Specifically, we collect a Medical Abnormalities Unveiling (MAU) dataset and propose a two-stage training method for UMed-LVLM training. To collect MAU dataset, we propose a prompt method utilizing the GPT-4V to generate diagnoses based on identified abnormal areas in medical images. Moreover, the two-stage training method includes Abnormal-Aware Instruction Tuning and Abnormal-Aware Rewarding, comprising Abnormal Localization Rewarding and Vision Relevance Rewarding. Experimental results demonstrate that our UMed-LVLM surpasses existing Med-LVLMs in identifying and understanding medical abnormality. In addition, this work shows that enhancing the abnormality detection capabilities of Med-LVLMs significantly improves their understanding of medical images and generalization capability.

[Arxiv](https://arxiv.org/abs/2501.01377)