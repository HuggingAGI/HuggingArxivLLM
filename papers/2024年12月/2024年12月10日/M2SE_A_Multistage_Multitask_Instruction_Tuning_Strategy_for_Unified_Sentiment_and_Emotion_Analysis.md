# M2SE：一种用于统一情感和情绪分析的多阶段多任务指令调优策略

发布时间：2024年12月10日

`LLM应用` `情感分析` `抑郁症检测`

> M2SE: A Multistage Multitask Instruction Tuning Strategy for Unified Sentiment and Emotion Analysis

# 摘要

> 情感分析和情绪识别在人机交互、抑郁症检测等应用中至关重要。传统单模态方法常因不同模态的信号冲突，难以捕捉情感表达的复杂性。当下的多模态大型语言模型（MLLMs）在检测细微面部表情及处理各类情绪相关任务时也面临挑战。为应对这些问题，我们提出了 M2SE，一种面向通用 MLLMs 的多阶段多任务情感与情绪指令调优策略。它通过组合方式，在多模态情感分析、情绪识别、面部表情识别、情绪原因推理和情绪因果对提取等任务上训练模型。我们还引入了情感多任务数据集（EMT），这是一个支持上述五项任务的自定义数据集。我们的模型“情感宇宙”（EmoVerse）构建于未作修改的基本 MLLM 框架之上，但采用 M2SE 策略训练后，在这些任务上均有显著提升。大量实验表明，EmoVerse 优于现有方法，在情感和情绪任务中达到了领先水平。这些结果凸显了 M2SE 在增强多模态情绪感知方面的有效性。数据集和代码可在 https://github.com/xiaoyaoxinyi/M2SE 获取。

> Sentiment analysis and emotion recognition are crucial for applications such as human-computer interaction and depression detection. Traditional unimodal methods often fail to capture the complexity of emotional expressions due to conflicting signals from different modalities. Current Multimodal Large Language Models (MLLMs) also face challenges in detecting subtle facial expressions and addressing a wide range of emotion-related tasks. To tackle these issues, we propose M2SE, a Multistage Multitask Sentiment and Emotion Instruction Tuning Strategy for general-purpose MLLMs. It employs a combined approach to train models on tasks such as multimodal sentiment analysis, emotion recognition, facial expression recognition, emotion reason inference, and emotion cause-pair extraction. We also introduce the Emotion Multitask dataset (EMT), a custom dataset that supports these five tasks. Our model, Emotion Universe (EmoVerse), is built on a basic MLLM framework without modifications, yet it achieves substantial improvements across these tasks when trained with the M2SE strategy. Extensive experiments demonstrate that EmoVerse outperforms existing methods, achieving state-of-the-art results in sentiment and emotion tasks. These results highlight the effectiveness of M2SE in enhancing multimodal emotion perception. The dataset and code are available at https://github.com/xiaoyaoxinyi/M2SE.

[Arxiv](https://arxiv.org/abs/2412.08049)