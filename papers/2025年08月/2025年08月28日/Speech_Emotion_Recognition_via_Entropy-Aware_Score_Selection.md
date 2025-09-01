# 基于熵感知分数选择的语音情感识别

发布时间：2025年08月28日

`其他` `媒体与娱乐`

> Speech Emotion Recognition via Entropy-Aware Score Selection

# 摘要

> 本文提出了一种用于语音情感识别的多模态框架，该框架通过熵感知分数选择融合语音与文本预测。该方法整合了主、次两条处理管道：主管道采用基于wav2vec2.0的声学模型，次管道则使用RoBERTa-XLM情感分析模型（语音转录由Whisper-large-v3完成）。为解决主管道预测的置信度局限，我们设计了基于熵和变熵阈值的后期分数融合策略。同时，情感映射策略将三类情感转换为四个目标情感类别，确保了多模态预测的连贯融合。在IEMOCAP与MSP-IMPROV数据集上的实验结果显示，该方法显著优于传统单模态系统，具备实用价值与可靠性。

> In this paper, we propose a multimodal framework for speech emotion recognition that leverages entropy-aware score selection to combine speech and textual predictions. The proposed method integrates a primary pipeline that consists of an acoustic model based on wav2vec2.0 and a secondary pipeline that consists of a sentiment analysis model using RoBERTa-XLM, with transcriptions generated via Whisper-large-v3. We propose a late score fusion approach based on entropy and varentropy thresholds to overcome the confidence constraints of primary pipeline predictions. A sentiment mapping strategy translates three sentiment categories into four target emotion classes, enabling coherent integration of multimodal predictions. The results on the IEMOCAP and MSP-IMPROV datasets show that the proposed method offers a practical and reliable enhancement over traditional single-modality systems.

[Arxiv](https://arxiv.org/abs/2508.20796)