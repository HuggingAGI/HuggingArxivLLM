# 基于文本的实时动作检测

发布时间：2025年01月23日

`LLM应用

理由：这篇论文主要讨论了利用视觉-语言模型（VLMs）和CLIP文本嵌入来实现实时动作检测，特别是在零-shot和少-shot学习场景下的应用。虽然论文中提到了Transformer架构和视觉-语言模型，但其核心是应用这些技术来解决实际问题（如视频监控、自动驾驶等），因此应归类为LLM应用。` `视频监控` `自动驾驶`

> Text-driven Online Action Detection

# 摘要

> 实时检测动作在视频监控、自动驾驶和人机交互等领域至关重要。在线动作检测任务要求对流媒体视频中的动作进行分类，处理背景噪声，并应对不完整的动作。尽管Transformer架构是目前的最优选择，但计算机视觉领域的最新进展，尤其是视觉-语言模型（VLMs），在这一问题上的潜力尚未充分挖掘，部分原因是计算成本较高。本文提出TOAD：一种支持零-shot和少-shot学习的文本驱动在线动作检测架构。TOAD利用CLIP文本嵌入，在不显著增加计算开销的情况下高效使用VLMs。我们的模型在THUMOS14数据集上取得了82.46%的mAP，超越了现有方法，并为THUMOS14和TVSeries数据集上的零-shot和少-shot性能设定了新的基准。

> Detecting actions as they occur is essential for applications like video surveillance, autonomous driving, and human-robot interaction. Known as online action detection, this task requires classifying actions in streaming videos, handling background noise, and coping with incomplete actions. Transformer architectures are the current state-of-the-art, yet the potential of recent advancements in computer vision, particularly vision-language models (VLMs), remains largely untapped for this problem, partly due to high computational costs. In this paper, we introduce TOAD: a Text-driven Online Action Detection architecture that supports zero-shot and few-shot learning. TOAD leverages CLIP (Contrastive Language-Image Pretraining) textual embeddings, enabling efficient use of VLMs without significant computational overhead. Our model achieves 82.46% mAP on the THUMOS14 dataset, outperforming existing methods, and sets new baselines for zero-shot and few-shot performance on the THUMOS14 and TVSeries datasets.

[Arxiv](https://arxiv.org/abs/2501.13518)