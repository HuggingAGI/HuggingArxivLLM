# # 双流显式语义引导多变量时间序列预测框架：DualSG
DualSG: 一种双流显式语义引导的多变量时间序列预测框架

发布时间：2025年07月29日

`LLM应用` `时间序列预测` `预测模型`

> DualSG: A Dual-Stream Explicit Semantic-Guided Multivariate Time Series Forecasting Framework

# 摘要

> 多变量时间序列预测在诸多应用中至关重要。近期研究探索了利用大型语言模型（LLMs）进行多变量时间序列预测（MTSF），以发挥其推理优势。然而，现有方法往往将LLMs作为端到端预测器，这不仅导致数值精度的损失，还让模型处理超出其设计范围的模式。同时，试图在潜在空间中对齐文本与时间序列模态的方法常遇对齐难题。为此，我们提出将LLMs作为双流框架中的语义引导模块，而非独立预测器。我们提出DualSG框架，通过显式语义引导优化传统预测。框架中的时间序列描述以自然语言总结趋势模式，为LLMs提供可解释上下文。此外，我们设计了基于描述的融合模块，显式建模变量间关系，同时减少噪声和计算。实验证明，DualSG在15个基线模型上表现优异，凸显了数值预测与语义引导结合的价值。

> Multivariate Time Series Forecasting plays a key role in many applications. Recent works have explored using Large Language Models for MTSF to take advantage of their reasoning abilities. However, many methods treat LLMs as end-to-end forecasters, which often leads to a loss of numerical precision and forces LLMs to handle patterns beyond their intended design. Alternatively, methods that attempt to align textual and time series modalities within latent space frequently encounter alignment difficulty. In this paper, we propose to treat LLMs not as standalone forecasters, but as semantic guidance modules within a dual-stream framework. We propose DualSG, a dual-stream framework that provides explicit semantic guidance, where LLMs act as Semantic Guides to refine rather than replace traditional predictions. As part of DualSG, we introduce Time Series Caption, an explicit prompt format that summarizes trend patterns in natural language and provides interpretable context for LLMs, rather than relying on implicit alignment between text and time series in the latent space. We also design a caption-guided fusion module that explicitly models inter-variable relationships while reducing noise and computation. Experiments on real-world datasets from diverse domains show that DualSG consistently outperforms 15 state-of-the-art baselines, demonstrating the value of explicitly combining numerical forecasting with semantic guidance.

[Arxiv](https://arxiv.org/abs/2507.21830)