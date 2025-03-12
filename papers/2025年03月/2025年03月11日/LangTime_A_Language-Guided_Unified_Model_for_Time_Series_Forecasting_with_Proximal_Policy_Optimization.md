# LangTime：基于近端策略优化的语言引导统一时间序列预测模型

发布时间：2025年03月11日

`LLM应用` `时间序列分析` `预测模型`

> LangTime: A Language-Guided Unified Model for Time Series Forecasting with Proximal Policy Optimization

# 摘要

> 近年来，将预训练的大型语言模型（LLMs）应用于时间序列分析的兴趣持续升温。然而，将LLMs用于时间序列预测时，我们面临三大核心挑战：跨域泛化、跨模态对齐以及自回归框架中的误差累积。为了解决这些问题，我们提出了LangTime——一种语言引导的统一时间序列预测模型，通过结合跨域预训练和强化学习微调来提升性能。具体来说，LangTime设计了时间理解提示（TCPs），包含数据集级和通道级指令，帮助模型更好地适应不同领域，并将复杂的时间序列简化为单个令牌，从而提升LLMs对时间数据的理解与对齐能力。为了进一步优化自回归预测效果，我们开发了TimePPO——一种基于强化学习的微调算法。通过采用专为时间序列设计的多维奖励函数和重复价值评估策略，TimePPO有效缓解了预测过程中的误差累积问题。实验结果表明，LangTime在跨域预测任务中达到了当前最优水平，而TimePPO的引入显著提升了自回归预测的稳定性和预测精度。

> Recent research has shown an increasing interest in utilizing pre-trained large language models (LLMs) for a variety of time series applications. However, there are three main challenges when using LLMs as foundational models for time series forecasting: (1) Cross-domain generalization. (2) Cross-modality alignment. (3) Error accumulation in autoregressive frameworks. To address these challenges, we proposed LangTime, a language-guided unified model for time series forecasting that incorporates cross-domain pre-training with reinforcement learning-based fine-tuning. Specifically, LangTime constructs Temporal Comprehension Prompts (TCPs), which include dataset-wise and channel-wise instructions, to facilitate domain adaptation and condense time series into a single token, enabling LLMs to understand better and align temporal data. To improve autoregressive forecasting, we introduce TimePPO, a reinforcement learning-based fine-tuning algorithm. TimePPO mitigates error accumulation by leveraging a multidimensional rewards function tailored for time series and a repeat-based value estimation strategy. Extensive experiments demonstrate that LangTime achieves state-of-the-art cross-domain forecasting performance, while TimePPO fine-tuning effectively enhances the stability and accuracy of autoregressive forecasting.

[Arxiv](https://arxiv.org/abs/2503.08271)