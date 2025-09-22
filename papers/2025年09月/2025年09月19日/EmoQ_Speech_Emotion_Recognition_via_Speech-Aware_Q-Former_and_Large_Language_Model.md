# EmoQ：基于语音感知Q-Former和大型语言模型的语音情感识别

发布时间：2025年09月19日

`LLM应用` `媒体与娱乐`

> EmoQ: Speech Emotion Recognition via Speech-Aware Q-Former and Large Language Model

# 摘要

> 语音情感识别（SER）的性能一直受限于单模态系统情感信息不足和多模态系统特征对齐困难的问题。近年来，多模态大型语言模型（MLLMs）在SER领域崭露头角，取得了一定进展。但在复杂情感推理场景下，MLLMs仍难逃幻觉和分类错误的困扰。为此，我们提出了一个基于MLLM的框架EmoQ。该框架借助EmoQ-Former生成融合多模态信息的查询嵌入，并通过多目标情感学习（MAL）实现协同优化。此外，框架还设计了软提示注入策略，将多模态表示注入LLM。这种端到端架构在IEMOCAP和MELD数据集上均达到了当前最优性能，为SER开辟了全新的多模态融合范式。

> The performance of speech emotion recognition (SER) is limited by the insufficient emotion information in unimodal systems and the feature alignment difficulties in multimodal systems. Recently, multimodal large language models (MLLMs) have made progress in SER. However, MLLMs still suffer from hallucination and misclassification problems in complex emotion reasoning. To address these problems, we propose an MLLM-based framework called EmoQ, which generates query embeddings that fuse multimodal information through an EmoQ-Former and uses multi-objective affective learning (MAL) to achieve co-optimization. The framework also provides a soft-prompt injection strategy to inject multimodal representations into the LLM. This end-to-end architecture achieves state-of-the-art performance on the IEMOCAP and MELD datasets, providing a new multimodal fusion paradigm for SER.

[Arxiv](https://arxiv.org/abs/2509.15775)