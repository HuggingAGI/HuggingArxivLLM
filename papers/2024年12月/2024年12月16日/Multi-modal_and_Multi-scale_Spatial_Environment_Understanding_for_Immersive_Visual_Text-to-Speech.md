# 沉浸式视觉文本到语音的多模态与多尺度空间环境理解

发布时间：2024年12月16日

`其他

**理由**：这篇论文主要讨论的是视觉文本转语音（VTTS）技术，特别是通过多模态多尺度空间环境理解方案（M2SE-VTTS）来生成带有混响的语音内容。虽然论文中提到了使用Gemini生成环境描述，但整体内容并不直接涉及大型语言模型（LLM）的应用、理论、Agent或RAG（Retrieval-Augmented Generation）技术。因此，将其分类为“其他”更为合适。` `语音合成` `计算机视觉`

> Multi-modal and Multi-scale Spatial Environment Understanding for Immersive Visual Text-to-Speech

# 摘要

> # 视觉文本转语音（VTTS）
视觉文本转语音（VTTS）旨在通过环境图像生成带有混响的语音内容。其核心挑战在于从图像中准确理解空间环境。尽管已有研究尝试从RGB图像中提取全局空间信息，但局部和深度信息同样关键，却常被忽视。为此，我们提出了一种创新的多模态多尺度空间环境理解方案——M2SE-VTTS，以实现沉浸式语音合成。该方案通过结合RGB和深度图像，全面捕捉空间信息，并同时建模局部与全局空间特征。具体实现中，我们首先将RGB和深度图像分割为小块，并利用Gemini生成的环境描述指导局部空间理解。随后，通过局部感知的全局空间理解整合多模态和多尺度特征。M2SE-VTTS成功建模了多模态空间环境中局部与全局上下文的交互。实验表明，该模型在环境语音生成任务中表现优异，超越了现有基线。代码和音频样本已开源：https://github.com/AI-S2-Lab/M2SE-VTTS。

> Visual Text-to-Speech (VTTS) aims to take the environmental image as the prompt to synthesize the reverberant speech for the spoken content. The challenge of this task lies in understanding the spatial environment from the image. Many attempts have been made to extract global spatial visual information from the RGB space of an spatial image. However, local and depth image information are crucial for understanding the spatial environment, which previous works have ignored. To address the issues, we propose a novel multi-modal and multi-scale spatial environment understanding scheme to achieve immersive VTTS, termed M2SE-VTTS. The multi-modal aims to take both the RGB and Depth spaces of the spatial image to learn more comprehensive spatial information, and the multi-scale seeks to model the local and global spatial knowledge simultaneously. Specifically, we first split the RGB and Depth images into patches and adopt the Gemini-generated environment captions to guide the local spatial understanding. After that, the multi-modal and multi-scale features are integrated by the local-aware global spatial understanding. In this way, M2SE-VTTS effectively models the interactions between local and global spatial contexts in the multi-modal spatial environment. Objective and subjective evaluations suggest that our model outperforms the advanced baselines in environmental speech generation. The code and audio samples are available at: https://github.com/AI-S2-Lab/M2SE-VTTS.

[Arxiv](https://arxiv.org/abs/2412.11409)