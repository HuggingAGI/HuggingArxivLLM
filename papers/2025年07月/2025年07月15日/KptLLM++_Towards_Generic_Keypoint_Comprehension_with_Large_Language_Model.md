# KptLLM++：通用关键点理解的大型语言模型

发布时间：2025年07月15日

`LLM应用` `计算机视觉` `图像处理`

> KptLLM++: Towards Generic Keypoint Comprehension with Large Language Model

# 摘要

> 多模态大型语言模型（MLLMs）的出现，通过连接文本与视觉模态，彻底改变了图像理解的方式。然而，这些模型在捕捉细粒度语义信息，特别是精确识别和分析物体关键点时，仍面临挑战。关键点作为结构感知、像素级且紧凑的对象表示，尤其在处理具关节结构的对象时，对细粒度图像分析、对象检索和行为识别等应用至关重要。

本文提出了一种新型多模态大型语言模型KptLLM++，该模型通过用户定义指令引导的多种输入模态融合，专门设计用于通用关键点理解。通过在不同上下文中统一关键点检测，KptLLM++建立了一个高级接口，促进更有效的人机协作。

该模型基于一种新型的“先识别再检测”范式，首先解释关键点语义，然后通过结构化的链式推理机制定位其精确位置。为了突破性能边界，我们将训练数据集扩展到超过50万样本，涵盖多样化的对象、关键点类别、图像风格以及复杂遮挡场景。这种大规模扩展使KptLLM++充分发挥其潜力，实现显著的准确性和泛化能力。

在多个关键点检测基准上的综合实验展示了其最先进的性能，凸显了其作为细粒度图像理解统一解决方案的潜力，以及对人机交互的变革性影响。

> The emergence of Multimodal Large Language Models (MLLMs) has revolutionized image understanding by bridging textual and visual modalities. However, these models often struggle with capturing fine-grained semantic information, such as the precise identification and analysis of object keypoints. Keypoints, as structure-aware, pixel-level, and compact representations of objects, particularly articulated ones, play a crucial role in applications such as fine-grained image analysis, object retrieval, and behavior recognition. In this paper, we propose KptLLM++, a novel multimodal large language model that specifically designed for generic keypoint comprehension through the integration of diverse input modalities guided by user-defined instructions. By unifying keypoint detection across varied contexts, KptLLM++ establishes itself as an advanced interface, fostering more effective human-AI collaboration. The model is built upon a novel identify-then-detect paradigm, which first interprets keypoint semantics and subsequently localizes their precise positions through a structured chain-of-thought reasoning mechanism. To push the boundaries of performance, we have scaled up the training dataset to over 500K samples, encompassing diverse objects, keypoint categories, image styles, and scenarios with complex occlusions. This extensive scaling enables KptLLM++ to unlock its potential, achieving remarkable accuracy and generalization. Comprehensive experiments on multiple keypoint detection benchmarks demonstrate its state-of-the-art performance, underscoring its potential as a unified solution for fine-grained image understanding and its transformative implications for human-AI interaction.

[Arxiv](https://arxiv.org/abs/2507.11102)