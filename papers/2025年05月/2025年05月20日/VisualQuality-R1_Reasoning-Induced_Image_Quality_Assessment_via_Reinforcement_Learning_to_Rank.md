# # VisualQuality-R1：视觉质量评估新标杆——基于推理的图像质量评估模型，通过强化学习实现精准排序

发布时间：2025年05月20日

`LLM应用` `计算机视觉` `图像处理`

> VisualQuality-R1: Reasoning-Induced Image Quality Assessment via Reinforcement Learning to Rank

# 摘要

> DeepSeek-R1 通过强化学习显著提升了大型语言模型的推理与泛化能力。然而，在图像质量评估这一依赖视觉推理的任务中，推理驱动的建模潜力尚未被充分挖掘。本文提出了一种基于推理的无参考图像质量评估模型 VisualQuality-R1，采用强化学习排序算法进行训练，该算法专为视觉质量的相对性设计。具体而言，我们为每张图像生成多个质量评分，并利用 Thurstone 模型计算图像间质量比较的概率。奖励机制采用连续保真度指标而非离散标签。实验结果表明，VisualQuality-R1 在多种图像处理任务中表现优异，能够生成与人类认知一致的质量描述，并支持多数据集训练。这些特性使其成为评估图像处理任务进展的理想工具。

> DeepSeek-R1 has demonstrated remarkable effectiveness in incentivizing reasoning and generalization capabilities of large language models (LLMs) through reinforcement learning. Nevertheless, the potential of reasoning-induced computational modeling has not been thoroughly explored in the context of image quality assessment (IQA), a task critically dependent on visual reasoning. In this paper, we introduce VisualQuality-R1, a reasoning-induced no-reference IQA (NR-IQA) model, and we train it with reinforcement learning to rank, a learning algorithm tailored to the intrinsically relative nature of visual quality. Specifically, for a pair of images, we employ group relative policy optimization to generate multiple quality scores for each image. These estimates are then used to compute comparative probabilities of one image having higher quality than the other under the Thurstone model. Rewards for each quality estimate are defined using continuous fidelity measures rather than discretized binary labels. Extensive experiments show that the proposed VisualQuality-R1 consistently outperforms discriminative deep learning-based NR-IQA models as well as a recent reasoning-induced quality regression method. Moreover, VisualQuality-R1 is capable of generating contextually rich, human-aligned quality descriptions, and supports multi-dataset training without requiring perceptual scale realignment. These features make VisualQuality-R1 especially well-suited for reliably measuring progress in a wide range of image processing tasks like super-resolution and image generation.

[Arxiv](https://arxiv.org/abs/2505.14460)