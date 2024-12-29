# 重新审视 MLLMs：深入剖析其图像分类能力

发布时间：2024年12月20日

`LLM应用` `图像分类` `多模态语言模型`

> Revisiting MLLMs: An In-Depth Analysis of Image Classification Abilities

# 摘要

> 随着多模态大型语言模型（MLLMs）的迅猛发展，一系列基准被引入以评估其能力。然而，多数评估聚焦于科学理解和视觉推理这类复杂任务，对其基本图像分类能力的评估却关注寥寥。本文通过深入剖析图像分类，全面审视 MLLMs 以填补这一空白。具体来说，基于已有的数据集，我们考察了广泛的场景，涵盖从一般分类任务（如 ImageNet、ObjectNet）到更细分的类别，像鸟类和食物分类。我们的发现显示，最新的 MLLMs 在多个数据集上能够与甚至超越 CLIP 风格的视觉语言模型，打破了此前认为 MLLMs 不擅图像分类的假定 \cite{VLMClassifier}。为理解推动这一进步的因素，我们对公共 MLLMs 所用的网络架构、数据选择和训练方法进行了深入探究。我们的成果将此成功归功于语言模型的进步以及训练数据来源的多样性。基于这些观察，我们进一步分析并分别将潜在原因归结于概念知识的迁移和目标概念的增强曝光。期望我们的发现能为 MLLMs 的未来研究及其在图像分类任务中的评估提供宝贵的见解。

> With the rapid advancement of Multimodal Large Language Models (MLLMs), a variety of benchmarks have been introduced to evaluate their capabilities. While most evaluations have focused on complex tasks such as scientific comprehension and visual reasoning, little attention has been given to assessing their fundamental image classification abilities. In this paper, we address this gap by thoroughly revisiting the MLLMs with an in-depth analysis of image classification. Specifically, building on established datasets, we examine a broad spectrum of scenarios, from general classification tasks (e.g., ImageNet, ObjectNet) to more fine-grained categories such as bird and food classification. Our findings reveal that the most recent MLLMs can match or even outperform CLIP-style vision-language models on several datasets, challenging the previous assumption that MLLMs are bad at image classification \cite{VLMClassifier}. To understand the factors driving this improvement, we conduct an in-depth analysis of the network architecture, data selection, and training recipe used in public MLLMs. Our results attribute this success to advancements in language models and the diversity of training data sources. Based on these observations, we further analyze and attribute the potential reasons to conceptual knowledge transfer and enhanced exposure of target concepts, respectively. We hope our findings will offer valuable insights for future research on MLLMs and their evaluation in image classification tasks.

[Arxiv](https://arxiv.org/abs/2412.16418)