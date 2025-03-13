# Cockatiel：用于详细视频字幕的合成与人类偏好训练集成

发布时间：2025年03月12日

`LLM应用` `视频处理` `自然语言生成`

> Cockatiel: Ensembling Synthetic and Human Preferenced Training for Detailed Video Caption

# 摘要

> 视频详细字幕生成（VDC）是连接视觉与语言的重要任务，能够实现对复杂视频内容的精细描述。本文中，我们对当前最先进的方法进行了全面基准测试，识别出两个关键限制：对特定字幕方面的偏颇能力和与人类偏好不一致。为此，我们提出了Cockatiel，一种三阶段训练流水线，结合合成数据和符合人类偏好的训练数据，以提升VDC性能。在第一阶段，我们从精心标注的数据集中构建了一个评分器，用于筛选在细粒度视频-字幕对齐和人类偏好上表现优异的合成字幕。接着，我们使用筛选后的数据集训练Cockatiel-13B模型，使其融合多种模型优势和人类偏好。最后，我们从Cockatiel-13B中蒸馏出Cockatiel-8B，以方便使用。实验结果表明，我们的方法不仅在VDCSCORE上以多维度平衡的方式达到了新的最先进性能，还在人工偏好方面大幅超越了现有领先方案，人工评估结果也充分体现了这一点。

> Video Detailed Captioning (VDC) is a crucial task for vision-language bridging, enabling fine-grained descriptions of complex video content. In this paper, we first comprehensively benchmark current state-of-the-art approaches and systematically identified two critical limitations: biased capability towards specific captioning aspect and misalignment with human preferences. To address these deficiencies, we propose Cockatiel, a novel three-stage training pipeline that ensembles synthetic and human-aligned training for improving VDC performance. In the first stage, we derive a scorer from a meticulously annotated dataset to select synthetic captions high-performing on certain fine-grained video-caption alignment and human-preferred while disregarding others. Then, we train Cockatiel-13B, using this curated dataset to infuse it with assembled model strengths and human preferences. Finally, we further distill Cockatiel-8B from Cockatiel-13B for the ease of usage. Extensive quantitative and qualitative experiments reflect the effectiveness of our method, as we not only set new state-of-the-art performance on VDCSCORE in a dimension-balanced way but also surpass leading alternatives on human preference by a large margin as depicted by the human evaluation results.

[Arxiv](https://arxiv.org/abs/2503.09279)