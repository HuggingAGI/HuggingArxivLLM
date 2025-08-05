# AffectGPT-R1：通过强化学习实现开放词汇情感识别

发布时间：2025年08月02日

`LLM应用` `情感识别`

> AffectGPT-R1: Leveraging Reinforcement Learning for Open-Vocabulary Emotion Recognition

# 摘要

> 开放词汇多模态情感识别（OV-MER）突破了传统情感预测的标签限制，实现了细致入微、类人化的情感理解。与传统判别方法不同，OV-MER采用生成模型（如拥有庞大词汇量的大型语言模型LLMs）来全方位捕捉情感。先前方法（如AffectGPT）主要依赖基于token的损失函数进行训练，但这一目标与OV-MER中基于情感轮（EW）的评估指标并不匹配。更遗憾的是，基于EW的指标无法通过梯度反向传播直接优化。为此，我们提出了AffectGPT-R1，一个直接优化基于EW指标性能的强化学习框架。具体而言，我们将这些指标作为奖励函数，并采用组相对策略优化（GRPO）来最大化奖励。实验结果表明，AffectGPT-R1在OV-MER方面取得了显著改进。我们希望这项工作能够推动多模态情感识别领域的发展。我们的代码将在以下地址公开发布：https://github.com/zeroQiaoba/AffectGPT。

> Open-Vocabulary Multimodal Emotion Recognition (OV-MER) aims to predict emotions without being constrained by predefined label spaces, enabling fine-grained and human-like emotion understanding. Unlike traditional discriminative methods, OV-MER leverages generative models, such as large language models (LLMs) with extensive vocabularies, to capture the full spectrum of emotions. Previous approaches (like AffectGPT) primarily rely on token-level loss for training. However, this objective does not align with the emotion wheel (EW)-based evaluation metrics used in OV-MER. Unfortunately, EW-based metrics cannot be directly optimized via gradient backpropagation. In this paper, we propose AffectGPT-R1, a reinforcement learning framework that directly optimizes performance on EW-based metrics. Specifically, we treat these metrics as the reward function and employ Group Relative Policy Optimization (GRPO) to maximize rewards. Experimental results demonstrate that AffectGPT-R1 achieves significant improvements on OV-MER. We hope this work advances the field of multimodal emotion recognition. Our code will be publicly available at:https://github.com/zeroQiaoba/AffectGPT.

[Arxiv](https://arxiv.org/abs/2508.01318)