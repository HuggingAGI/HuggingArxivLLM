# MoMuSE：用于视觉线索受损的实时场景的动量多模态目标说话人提取技术

发布时间：2024年12月11日

`其他` `音频处理` `语音提取`

> MoMuSE: Momentum Multi-modal Target Speaker Extraction for Real-time Scenarios with Impaired Visual Cues

# 摘要

> 音频-视觉目标说话人提取（AV-TSE）旨在借助时间同步的视觉线索，从音频混合中分离出特定目标说话人的语音。在实际场景中，由于种种干扰，视觉线索并非总能获取，这影响了 AV-TSE 的稳定性。即便如此，人类能够随时间保持注意力的动量，哪怕目标说话人不可见。在本文中，我们推出了动量多模态目标说话人提取（MoMuSE）技术，它能在内存中留存说话人的身份动量，让模型持续追踪目标说话人。专为实时推理而设计，MoMuSE 在视觉线索和动态更新的说话人动量的引导下提取当前语音窗口。实验结果显示，MoMuSE 有显著提升，在视觉线索严重受损的场景中尤为突出。

> Audio-visual Target Speaker Extraction (AV-TSE) aims to isolate the speech of a specific target speaker from an audio mixture using time-synchronized visual cues. In real-world scenarios, visual cues are not always available due to various impairments, which undermines the stability of AV-TSE. Despite this challenge, humans can maintain attentional momentum over time, even when the target speaker is not visible. In this paper, we introduce the Momentum Multi-modal target Speaker Extraction (MoMuSE), which retains a speaker identity momentum in memory, enabling the model to continuously track the target speaker. Designed for real-time inference, MoMuSE extracts the current speech window with guidance from both visual cues and dynamically updated speaker momentum. Experimental results demonstrate that MoMuSE exhibits significant improvement, particularly in scenarios with severe impairment of visual cues.

[Arxiv](https://arxiv.org/abs/2412.08247)