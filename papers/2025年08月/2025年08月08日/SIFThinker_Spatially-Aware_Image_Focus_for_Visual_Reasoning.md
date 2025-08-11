# SIFThinker：空间感知的图像焦点技术，专为视觉推理设计。

发布时间：2025年08月08日

`LLM应用` `计算机视觉` `多模态`

> SIFThinker: Spatially-Aware Image Focus for Visual Reasoning

# 摘要

> 当前的多模态大型语言模型 (MLLMs) 在复杂视觉任务（如空间理解、细粒度感知）中仍面临重大挑战。先前的方法尝试整合视觉推理，然而，它们未能有效利用空间线索进行注意力修正，以逐步聚焦于与提示相关的区域。本文介绍 SIFThinker，一个模拟人类视觉感知的空间感知“以图辅思”框架。具体而言，SIFThinker 通过深度增强的边界框与自然语言的交替使用，实现了注意力修正和图像区域聚焦。

我们的贡献包括两个方面：
- 首先，我们引入了一种逆向扩展-正向推理策略，该策略促进了交错图像-文本链式思维的生成，为过程级监督提供了支持，进而构建了 SIF-50K 数据集。
- 其次，我们提出了 GRPO-SIF，一种强化训练范式，将深度增强的视觉定位整合到统一的推理管道中，指导模型动态修正并聚焦于与提示相关的区域。

大量实验表明，SIFThinker 在空间理解和细粒度视觉感知方面超越了现有最优方法，同时保持了强大的通用能力，凸显了我们方法的有效性。


> Current multimodal large language models (MLLMs) still face significant challenges in complex visual tasks (e.g., spatial understanding, fine-grained perception). Prior methods have tried to incorporate visual reasoning, however, they fail to leverage attention correction with spatial cues to iteratively refine their focus on prompt-relevant regions. In this paper, we introduce SIFThinker, a spatially-aware "think-with-images" framework that mimics human visual perception. Specifically, SIFThinker enables attention correcting and image region focusing by interleaving depth-enhanced bounding boxes and natural language. Our contributions are twofold: First, we introduce a reverse-expansion-forward-inference strategy that facilitates the generation of interleaved image-text chains of thought for process-level supervision, which in turn leads to the construction of the SIF-50K dataset. Besides, we propose GRPO-SIF, a reinforced training paradigm that integrates depth-informed visual grounding into a unified reasoning pipeline, teaching the model to dynamically correct and focus on prompt-relevant regions. Extensive experiments demonstrate that SIFThinker outperforms state-of-the-art methods in spatial understanding and fine-grained visual perception, while maintaining strong general capabilities, highlighting the effectiveness of our method.

[Arxiv](https://arxiv.org/abs/2508.06259)