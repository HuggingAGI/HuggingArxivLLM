# 听懂，对齐：音频-视觉大模型的优化之道

发布时间：2025年04月02日

`LLM应用` `视频理解` `视听结合`

> Aligned Better, Listen Better for Audio-Visual Large Language Models

# 摘要

> 音频在多模态视频理解中扮演着关键角色。一方面，视频本身就包含了音频，为视觉信息提供了重要的补充。此外，视频大型语言模型（Video-LLMs）在实际应用中常常会遇到以音频为中心的场景。然而，现有的Video-LLMs和视听大型语言模型（AV-LLMs）在利用音频信息方面存在明显不足，导致视频理解能力较弱，并容易产生幻觉现象。为了解决这些问题，我们从模型架构和数据集两个维度展开了深入研究。

首先，从模型架构的角度，我们提出了一种细粒度的AV-LLM——Dolphin。通过在时间和空间两个维度上对音频和视觉模态进行同步对齐，Dolphin能够实现对视频内容的全面理解和精准把握。具体而言，我们在空间对齐方面设计了一种视听多尺度适配器，用于多尺度信息的聚合。在时间对齐方面，我们创新性地提出了视听交错合并方法。

其次，从数据集的角度，我们整理了一个名为AVU的视听字幕和指令微调数据集。该数据集包含520万个多样化、开放式的数据元组（视频，音频，问题，答案），并引入了一种全新的数据划分策略。通过大量实验验证，我们的模型不仅在视听理解任务中表现出色，还有效缓解了潜在的幻觉问题，展现了强大的实际应用价值。

> Audio is essential for multimodal video understanding. On the one hand, video inherently contains audio, which supplies complementary information to vision. Besides, video large language models (Video-LLMs) can encounter many audio-centric settings. However, existing Video-LLMs and Audio-Visual Large Language Models (AV-LLMs) exhibit deficiencies in exploiting audio information, leading to weak understanding and hallucinations. To solve the issues, we delve into the model architecture and dataset. (1) From the architectural perspective, we propose a fine-grained AV-LLM, namely Dolphin. The concurrent alignment of audio and visual modalities in both temporal and spatial dimensions ensures a comprehensive and accurate understanding of videos. Specifically, we devise an audio-visual multi-scale adapter for multi-scale information aggregation, which achieves spatial alignment. For temporal alignment, we propose audio-visual interleaved merging. (2) From the dataset perspective, we curate an audio-visual caption and instruction-tuning dataset, called AVU. It comprises 5.2 million diverse, open-ended data tuples (video, audio, question, answer) and introduces a novel data partitioning strategy. Extensive experiments show our model not only achieves remarkable performance in audio-visual understanding, but also mitigates potential hallucinations.

[Arxiv](https://arxiv.org/abs/2504.02061)