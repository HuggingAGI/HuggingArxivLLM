# LMM4Gen3DHF：基于LMMs的多模态三维人臉生成基准测试与评估

发布时间：2025年04月29日

`其他` `虚拟现实`

> LMM4Gen3DHF: Benchmarking and Evaluating Multimodal 3D Human Face Generation with LMMs

# 摘要

> 生成式人工智能的飞速发展为媒体制作、虚拟现实、安全、医疗保健和游戏开发等领域带来了革命性的变化，使得生成3D人面成为可能。然而，由于人类感知的主观性和对面部特征的固有敏感性，评估这些AI生成的3D人面的质量和真实感仍然是一项重大挑战。为此，我们对AI生成的3D人面的质量评估进行了全面研究。

首先，我们介绍了Gen3DHF，这是一个包含2000条AI生成的3D人面视频的大型基准数据集，其中包括在两个维度（即质量和真实性）上收集的4000个平均意见评分（MOS）、2000个失真感知显著性图和失真描述。基于Gen3DHF，我们提出了LMME3DHF，这是一种基于大型多模态模型（LMM）的3DHF评估指标，能够进行质量评分和真实感评分预测、失真感知视觉问答以及失真感知显著性预测。

实验结果表明，LMME3DHF实现了最先进的性能，不仅在准确预测AI生成的3D人面的质量评分方面超越了现有方法，而且在有效识别失真感知显著区域和失真类型方面也表现出色，同时与人类感知判断保持高度一致。Gen3DHF数据库和LMME3DHF将在论文发表时公开发布。

> The rapid advancement in generative artificial intelligence have enabled the creation of 3D human faces (HFs) for applications including media production, virtual reality, security, healthcare, and game development, etc. However, assessing the quality and realism of these AI-generated 3D human faces remains a significant challenge due to the subjective nature of human perception and innate perceptual sensitivity to facial features. To this end, we conduct a comprehensive study on the quality assessment of AI-generated 3D human faces. We first introduce Gen3DHF, a large-scale benchmark comprising 2,000 videos of AI-Generated 3D Human Faces along with 4,000 Mean Opinion Scores (MOS) collected across two dimensions, i.e., quality and authenticity, 2,000 distortion-aware saliency maps and distortion descriptions. Based on Gen3DHF, we propose LMME3DHF, a Large Multimodal Model (LMM)-based metric for Evaluating 3DHF capable of quality and authenticity score prediction, distortion-aware visual question answering, and distortion-aware saliency prediction. Experimental results show that LMME3DHF achieves state-of-the-art performance, surpassing existing methods in both accurately predicting quality scores for AI-generated 3D human faces and effectively identifying distortion-aware salient regions and distortion types, while maintaining strong alignment with human perceptual judgments. Both the Gen3DHF database and the LMME3DHF will be released upon the publication.

[Arxiv](https://arxiv.org/abs/2504.20466)