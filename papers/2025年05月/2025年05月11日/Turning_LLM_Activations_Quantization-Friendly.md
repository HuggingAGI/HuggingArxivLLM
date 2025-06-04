# # 将 LLM 激活转化为量化友好型
将 LLM 的激活转化为量化友好型是提升模型效率的关键任务。通过优化模型的内部表示，使其更易于量化处理，可以在保持性能的同时显著减少计算资源的消耗，为实际应用提供更高效的解决方案。

发布时间：2025年05月11日

`LLM理论` `机器学习`

> Turning LLM Activations Quantization-Friendly

# 摘要

> 量化技术通过压缩参数加速数据传输，并借助整数运算实现更快的操作，从而有效降低大型语言模型（LLMs）的服务成本。然而，启动整数运算需要对权重和激活进行量化，这带来了挑战，因为LLMs中显著的异常值会增加量化误差。在本研究中，我们重点分析这些异常值对分层量化误差的影响，并探讨平滑和旋转如何改变观测值。我们的主要贡献包括引入一种基于通道幅度的新指标来衡量和可视化量化难度，以及提出一种混合方法，该方法在旋转前应用通道缩放，并通过数学公式证明其优势。

> Quantization effectively reduces the serving costs of Large Language Models (LLMs) by speeding up data movement through compressed parameters and enabling faster operations via integer arithmetic. However, activating integer arithmetic requires quantizing both weights and activations, which poses challenges due to the significant outliers in LLMs that increase quantization error. In this work, we investigate these outliers with an emphasis on their effect on layer-wise quantization error, then examine how smoothing and rotation transform the observed values. Our primary contributions include introducing a new metric to measure and visualize quantization difficulty based on channel magnitudes, as well as proposing a hybrid approach that applies channel-wise scaling before rotation, supported by a mathematical formulation of its benefits.

[Arxiv](https://arxiv.org/abs/2506.01967)