# # 量化感知训练的缩放定律

发布时间：2025年05月20日

`LLM理论` `人工智能` `模型优化`

> Scaling Law for Quantization-Aware Training

# 摘要

> 大型语言模型（LLMs）对计算和内存资源的需求带来了部署挑战。量化感知训练（QAT）通过降低模型精度同时保持性能，为解决这些挑战提供了有效途径。然而，QAT的扩展行为，特别是在4位精度（W4A4）下，尚未被充分理解。现有QAT扩展定律通常忽略了关键因素，如训练令牌数量和量化粒度，这限制了它们的应用范围。本文提出了一种统一的QAT扩展定律，将量化误差建模为模型大小、训练数据量和量化组大小的函数。通过268个QAT实验，我们发现量化误差随着模型规模的增加而减少，但随着训练令牌数量的增加和量化粒度的变粗而上升。为了识别W4A4量化误差的来源，我们将误差分解为权重和激活两部分。两部分都遵循W4A4量化误差的整体趋势，但敏感度不同。具体而言，权重量化误差随着训练令牌数量的增加而更快上升。进一步分析表明，由异常值引起的FC2层激活量化误差是W4A4 QAT量化误差的主要瓶颈。通过应用混合精度量化来解决这一瓶颈，我们证明权重和激活量化误差可以收敛到相似水平。此外，随着训练数据的增加，权重量化误差最终超过激活量化误差，这表明在这种情况下减少权重量化误差也很重要。这些发现为改进QAT的研究和开发提供了关键见解。

> Large language models (LLMs) demand substantial computational and memory resources, creating deployment challenges. Quantization-aware training (QAT) addresses these challenges by reducing model precision while maintaining performance. However, the scaling behavior of QAT, especially at 4-bit precision (W4A4), is not well understood. Existing QAT scaling laws often ignore key factors such as the number of training tokens and quantization granularity, which limits their applicability. This paper proposes a unified scaling law for QAT that models quantization error as a function of model size, training data volume, and quantization group size. Through 268 QAT experiments, we show that quantization error decreases as model size increases, but rises with more training tokens and coarser quantization granularity. To identify the sources of W4A4 quantization error, we decompose it into weight and activation components. Both components follow the overall trend of W4A4 quantization error, but with different sensitivities. Specifically, weight quantization error increases more rapidly with more training tokens. Further analysis shows that the activation quantization error in the FC2 layer, caused by outliers, is the primary bottleneck of W4A4 QAT quantization error. By applying mixed-precision quantization to address this bottleneck, we demonstrate that weight and activation quantization errors can converge to similar levels. Additionally, with more training data, weight quantization error eventually exceeds activation quantization error, suggesting that reducing weight quantization error is also important in such scenarios. These findings offer key insights for improving QAT research and development.

[Arxiv](https://arxiv.org/abs/2505.14302)