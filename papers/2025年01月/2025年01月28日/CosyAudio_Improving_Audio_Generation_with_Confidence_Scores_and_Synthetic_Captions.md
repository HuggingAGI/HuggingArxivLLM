# CosyAudio: 利用置信度评分与合成字幕提升音频生成质量

发布时间：2025年01月28日

`LLM应用

理由：这篇论文主要讨论了使用AI生成内容（AIGC）中的文本到音频（TTA）生成技术，特别是通过置信度分数和合成描述来提升音频生成质量。虽然论文中提到了使用合成描述和置信度分数来优化生成过程，但这些技术是基于现有的AI模型（如大型语言模型）的应用，而不是直接研究或改进LLM的理论或架构。因此，这篇论文更适合归类为“LLM应用”。` `音频生成`

> CosyAudio: Improving Audio Generation with Confidence Scores and Synthetic Captions

# 摘要

> # 摘要
文本到音频（TTA）生成是AI生成内容（AIGC）中的新兴领域，旨在从自然语言描述中生成音频。尽管备受关注，但由于缺乏高质量标记的数据集以及大规模弱标记语料库中普遍存在的噪声描述，开发稳健的TTA模型仍面临挑战。为此，我们提出了CosyAudio框架，通过置信度分数和合成描述提升音频生成质量。CosyAudio包含两个核心模块：AudioCapTeller和音频生成器。AudioCapTeller生成音频的合成描述并评估其准确性，音频生成器则利用这些描述和置信度分数实现质量感知的生成。此外，我们引入了一种自我进化的训练策略，在良好标记和弱标记数据集上迭代优化CosyAudio。AudioCapTeller首先在良好标记数据上训练，随后在弱标记数据上进行高质量过滤和强化学习，进一步提升性能。训练完成后，AudioCapTeller通过生成新描述和置信度分数优化语料库，用于音频生成器的训练。大量实验表明，CosyAudio在自动音频描述任务中表现优异，生成的音频更忠实，且在不同场景下展现出强大的泛化能力。

> Text-to-Audio (TTA) generation is an emerging area within AI-generated content (AIGC), where audio is created from natural language descriptions. Despite growing interest, developing robust TTA models remains challenging due to the scarcity of well-labeled datasets and the prevalence of noisy or inaccurate captions in large-scale, weakly labeled corpora. To address these challenges, we propose CosyAudio, a novel framework that utilizes confidence scores and synthetic captions to enhance the quality of audio generation. CosyAudio consists of two core components: AudioCapTeller and an audio generator. AudioCapTeller generates synthetic captions for audio and provides confidence scores to evaluate their accuracy. The audio generator uses these synthetic captions and confidence scores to enable quality-aware audio generation. Additionally, we introduce a self-evolving training strategy that iteratively optimizes CosyAudio across both well-labeled and weakly-labeled datasets. Initially trained with well-labeled data, AudioCapTeller leverages its assessment capabilities on weakly-labeled datasets for high-quality filtering and reinforcement learning, which further improves its performance. The well-trained AudioCapTeller refines corpora by generating new captions and confidence scores, serving for the audio generator training. Extensive experiments on open-source datasets demonstrate that CosyAudio outperforms existing models in automated audio captioning, generates more faithful audio, and exhibits strong generalization across diverse scenarios.

[Arxiv](https://arxiv.org/abs/2501.16761)