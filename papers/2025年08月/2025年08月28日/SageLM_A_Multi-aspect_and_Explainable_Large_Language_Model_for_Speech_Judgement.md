# SageLM：面向语音评判的多维度可解释大型语言模型

发布时间：2025年08月28日

`LLM应用` `基础理论`

> SageLM: A Multi-aspect and Explainable Large Language Model for Speech Judgement

# 摘要

> 语音到语音（S2S）大型语言模型（LLMs）是自然人机交互的核心基础，为人机端到端口语对话系统提供了支撑。但如何评估这类模型仍是一大核心难题。为此，我们提出	exttt{SageLM}——一种端到端、多维度、可解释的语音大模型，旨在全面评估S2S LLMs。首先，不同于忽视声学特征的级联方法，SageLM能同时对语义和声学维度进行联合评估。其次，它借助基于理据的监督机制提升模型的可解释性并引导其学习，与基于规则的强化学习方法相比，与评估结果的契合度显著更优。第三，我们构建了	extit{SpeechFeedback}这一合成偏好数据集，并采用两阶段训练范式来缓解语音偏好数据稀缺的问题。经过语义和声学双维度训练后，SageLM与人类评估结果的一致性达到82.79%，其性能分别比级联方法和基于SLM的基线模型高出至少7.42%和26.20%。

> Speech-to-Speech (S2S) Large Language Models (LLMs) are foundational to natural human-computer interaction, enabling end-to-end spoken dialogue systems. However, evaluating these models remains a fundamental challenge. We propose \texttt{SageLM}, an end-to-end, multi-aspect, and explainable speech LLM for comprehensive S2S LLMs evaluation. First, unlike cascaded approaches that disregard acoustic features, SageLM jointly assesses both semantic and acoustic dimensions. Second, it leverages rationale-based supervision to enhance explainability and guide model learning, achieving superior alignment with evaluation outcomes compared to rule-based reinforcement learning methods. Third, we introduce \textit{SpeechFeedback}, a synthetic preference dataset, and employ a two-stage training paradigm to mitigate the scarcity of speech preference data. Trained on both semantic and acoustic dimensions, SageLM achieves an 82.79\% agreement rate with human evaluators, outperforming cascaded and SLM-based baselines by at least 7.42\% and 26.20\%, respectively.

[Arxiv](https://arxiv.org/abs/2508.20916)