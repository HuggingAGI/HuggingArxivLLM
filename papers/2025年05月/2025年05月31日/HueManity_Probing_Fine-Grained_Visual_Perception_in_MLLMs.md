# HueManity：深入探究多模态大型语言模型的细粒度视觉感知能力

发布时间：2025年05月31日

`LLM应用` `计算机视觉` `人工智能`

> HueManity: Probing Fine-Grained Visual Perception in MLLMs

# 摘要

> 多模态大型语言模型（MLLMs）在高级视觉推理方面表现优异，但在细微的感知任务上仍显不足。我们推出HueManity基准测试，专为评估多模态大型语言模型的视觉感知能力而设计。该数据集包含83,850张图像，每张图像中嵌入了由两个字符组成的字母数字字符串，采用色觉测试风格的点阵图案，挑战模型的精确模式识别能力。我们对九个先进多模态大型语言模型在HueManity上的评估显示，它们的表现远逊于人类和传统计算机视觉基线。在数字“简单”任务中，最佳模型的准确率为33.6%；而在字母数字“困难”任务中，准确率仅为3%。相比之下，人类参与者在两项任务中分别达到了100%和95.6%的高准确率，而微调后的ResNet50模型则分别达到了96.5%和94.5%的准确率。这些结果凸显了当前多模态大型语言模型在视觉能力上的显著缺口。我们进一步分析了可能影响多模态大型语言模型感知差距的架构和训练范式因素。为促进提升多模态大型语言模型感知鲁棒性的研究，我们开源了HueManity数据集和代码。

> Multimodal Large Language Models (MLLMs) excel at high-level visual reasoning, but their performance on nuanced perceptual tasks remains surprisingly limited. We present HueManity, a benchmark designed to assess visual perception in MLLMs. The dataset comprises 83,850 images featuring two-character alphanumeric strings embedded in Ishihara test style dot patterns, challenging models on precise pattern recognition. Our evaluation of nine state-of-the-art MLLMs on HueManity demonstrates a significant performance deficit compared to human and traditional computer vision baselines. The best-performing MLLM achieved a 33.6% accuracy on the numeric `easy' task and a striking 3% on the alphanumeric `hard' task. In contrast, human participants achieved near-perfect scores (100% and 95.6%), and a fine-tuned ResNet50 model reached accuracies of 96.5% and 94.5%. These results highlight a critical gap in the visual capabilities of current MLLMs. Our analysis further explores potential architectural and training-paradigm factors contributing to this perceptual gap in MLLMs. We open-source HueManity dataset and code to foster further research in improving perceptual robustness of MLLMs.

[Arxiv](https://arxiv.org/abs/2506.03194)