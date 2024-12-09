# LeMoLE：用于时间序列预测的 LLM 增强型线性专家混合体

发布时间：2024年11月24日

`LLM应用` `时间序列预测`

> LeMoLE: LLM-Enhanced Mixture of Linear Experts for Time Series Forecasting

# 摘要

> 近期研究显示，凭借强大的自然语言理解能力，大型语言模型（LLMs）能有效应用于现实世界的时间序列预测。但将时间序列与LLMs的语义空间对齐，会产生高额的计算成本和复杂的推理过程，在长程时间序列生成方面尤其如此。基于使用线性模型处理时间序列的最新进展，本文推出一种用于精准高效时间序列预测的LLM增强型线性专家混合模型。该方法包括开发具有多种回溯长度的线性专家混合模型以及全新的多模态融合机制。线性专家混合模型因简单而高效，多模态融合机制则依据从预训练的大型语言模型中学到的文本模态特征，自适应组合多个线性专家。在实验中，我们重新审视了现有时间序列大型语言模型将时间序列对齐到LLMs的必要性，并进一步探讨了它们在时间序列预测中的效率和效果。我们的实验结果表明，所提出的LeMoLE模型相比现有LLM模型，预测误差更低，计算效率更高。

> Recent research has shown that large language models (LLMs) can be effectively used for real-world time series forecasting due to their strong natural language understanding capabilities. However, aligning time series into semantic spaces of LLMs comes with high computational costs and inference complexity, particularly for long-range time series generation. Building on recent advancements in using linear models for time series, this paper introduces an LLM-enhanced mixture of linear experts for precise and efficient time series forecasting. This approach involves developing a mixture of linear experts with multiple lookback lengths and a new multimodal fusion mechanism. The use of a mixture of linear experts is efficient due to its simplicity, while the multimodal fusion mechanism adaptively combines multiple linear experts based on the learned features of the text modality from pre-trained large language models. In experiments, we rethink the need to align time series to LLMs by existing time-series large language models and further discuss their efficiency and effectiveness in time series forecasting. Our experimental results show that the proposed LeMoLE model presents lower prediction errors and higher computational efficiency than existing LLM models.

[Arxiv](https://arxiv.org/abs/2412.00053)