# # 量化友好型 LLM 激活函数转换
将 LLM 的激活函数转化为更友好的量化形式。

发布时间：2025年05月11日

`LLM理论

摘要讨论了量化技术在大型语言模型中的应用，探讨了异常值对量化误差的影响，并提出了一种新的指标和混合方法来优化模型性能。这属于对LLM的理论和技术优化，因此归类为LLM理论。` `量化技术`

> Turning LLM Activations Quantization-Friendly

# 摘要

> 量化技术通过压缩参数加速数据传输，并利用整数运算实现更快的操作，从而有效降低了大型语言模型（LLMs）的推理成本。然而，启用整数运算需要对权重和激活进行量化，这由于LLMs中存在的显著异常值而增加了量化误差，带来了挑战。本研究着重探讨了这些异常值及其对逐层量化误差的影响，随后分析了平滑和旋转如何改变观测值。我们的主要贡献包括引入了一种基于通道幅度衡量和可视化量化难度的新指标，以及提出了一种在旋转前应用通道级缩放的混合方法，并通过数学公式验证了其优势。

> Quantization effectively reduces the serving costs of Large Language Models (LLMs) by speeding up data movement through compressed parameters and enabling faster operations via integer arithmetic. However, activating integer arithmetic requires quantizing both weights and activations, which poses challenges due to the significant outliers in LLMs that increase quantization error. In this work, we investigate these outliers with an emphasis on their effect on layer-wise quantization error, then examine how smoothing and rotation transform the observed values. Our primary contributions include introducing a new metric to measure and visualize quantization difficulty based on channel magnitudes, as well as proposing a hybrid approach that applies channel-wise scaling before rotation, supported by a mathematical formulation of its benefits.

[Arxiv](https://arxiv.org/abs/2506.01967)