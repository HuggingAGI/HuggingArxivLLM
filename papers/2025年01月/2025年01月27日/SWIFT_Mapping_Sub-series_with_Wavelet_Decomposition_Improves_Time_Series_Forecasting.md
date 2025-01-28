# SWIFT: 通过小波分解映射子序列，提升时间序列预测效果

发布时间：2025年01月27日

`其他

**理由**：这篇论文主要讨论的是时间序列预测模型 $	extit{SWIFT}$ 的设计和性能，虽然提到了大型语言模型（LLM）的背景，但核心内容并不涉及LLM的应用、理论、Agent或RAG（Retrieval-Augmented Generation）相关的内容。因此，将其归类为“其他”更为合适。` `时间序列预测` `边缘计算`

> SWIFT: Mapping Sub-series with Wavelet Decomposition Improves Time Series Forecasting

# 摘要

> 在近期的时间序列预测研究中，Transformer 和大型语言模型因其强大的序列建模能力而备受瞩目。然而，实际部署中，时间序列预测往往需要在资源受限的环境（如边缘设备）中运行，这些设备难以承受大型模型的计算负担。为此，一些轻量级模型应运而生，但它们在非平稳序列上的表现却不尽如人意。本文提出的 $	extit{SWIFT}$ 模型，不仅功能强大，而且在长期时间序列预测（LTSF）中部署和推理效率极高。我们的模型基于三大核心设计：（i）利用小波变换对时间序列进行无损下采样；（ii）通过可学习滤波器实现跨频带信息融合；（iii）仅使用一个共享线性层或浅层 MLP 进行子序列映射。实验结果表明，$	extit{SWIFT}$ 在多个数据集上达到了最先进的（SOTA）性能，为边缘计算和部署提供了极具潜力的解决方案。值得一提的是，$	extit{SWIFT-Linear}$ 的参数数量仅为时域预测单层线性模型的 25\%。代码已开源：https://github.com/LancelotXWX/SWIFT。

> In recent work on time-series prediction, Transformers and even large language models have garnered significant attention due to their strong capabilities in sequence modeling. However, in practical deployments, time-series prediction often requires operation in resource-constrained environments, such as edge devices, which are unable to handle the computational overhead of large models. To address such scenarios, some lightweight models have been proposed, but they exhibit poor performance on non-stationary sequences. In this paper, we propose $\textit{SWIFT}$, a lightweight model that is not only powerful, but also efficient in deployment and inference for Long-term Time Series Forecasting (LTSF). Our model is based on three key points: (i) Utilizing wavelet transform to perform lossless downsampling of time series. (ii) Achieving cross-band information fusion with a learnable filter. (iii) Using only one shared linear layer or one shallow MLP for sub-series' mapping. We conduct comprehensive experiments, and the results show that $\textit{SWIFT}$ achieves state-of-the-art (SOTA) performance on multiple datasets, offering a promising method for edge computing and deployment in this task. Moreover, it is noteworthy that the number of parameters in $\textit{SWIFT-Linear}$ is only 25\% of what it would be with a single-layer linear model for time-domain prediction. Our code is available at https://github.com/LancelotXWX/SWIFT.

[Arxiv](https://arxiv.org/abs/2501.16178)