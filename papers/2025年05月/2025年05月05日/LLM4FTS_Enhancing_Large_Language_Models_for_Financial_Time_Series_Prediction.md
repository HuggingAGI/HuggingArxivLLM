# # LLM4FTS：助力金融时间序列预测的大型语言模型增强方案

发布时间：2025年05月05日

`LLM应用` `时间序列预测`

> LLM4FTS: Enhancing Large Language Models for Financial Time Series Prediction

# 摘要

> 金融时间序列预测因其固有的低信噪比和复杂的时间模式而充满挑战。传统机器学习模型受限于模型容量，在此预测任务中表现不足。然而，大型语言模型（LLMs）凭借其扩展的参数空间，展现出在建模时间序列复杂依赖关系方面的巨大潜力。然而，现有基于LLMs的方法通常受限于Transformer架构，专注于固定长度的补丁分析，忽视了市场数据的多尺度模式特性。本研究提出【数学公式】，一种通过可学习的补丁分割和动态小波卷积模块增强LLMs时间序列建模能力的新框架。

具体而言，我们首先基于DTW距离运用K-means++聚类方法，识别市场数据中的尺度不变模式。在此基础上，我们引入自适应补丁分割，将时间序列划分为保持最大模式完整性的片段。为适应时变频率特征，我们设计了一种动态小波卷积模块，模拟离散小波变换，同时增强对时频特征的捕捉能力。这三个模块协同工作，提升大型语言模型处理金融时间序列中尺度不变模式的能力。

在真实金融数据集上的广泛实验验证了该框架的有效性，展示了其在捕捉复杂市场模式和股票收益预测方面达到业界领先水平。该框架在实际交易系统中的成功部署证实了其现实应用价值，标志着LLMs在金融预测领域应用的重要进展。

> Predicting financial time series presents significant challenges due to inherent low signal-to-noise ratios and intricate temporal patterns. Traditional machine learning models exhibit limitations in this forecasting task constrained by their restricted model capacity. Recent advances in large language models (LLMs), with their greatly expanded parameter spaces, demonstrate promising potential for modeling complex dependencies in temporal sequences. However, existing LLM-based approaches typically focus on fixed-length patch analysis due to the Transformer architecture, ignoring market data's multi-scale pattern characteristics. In this study, we propose $LLM4FTS$, a novel framework that enhances LLM capabilities for temporal sequence modeling through learnable patch segmentation and dynamic wavelet convolution modules. Specifically,we first employ K-means++ clustering based on DTW distance to identify scale-invariant patterns in market data. Building upon pattern recognition results, we introduce adaptive patch segmentation that partitions temporal sequences while preserving maximal pattern integrity. To accommodate time-varying frequency characteristics, we devise a dynamic wavelet convolution module that emulates discrete wavelet transformation with enhanced flexibility in capturing time-frequency features. These three modules work together to improve large language model's ability to handle scale-invariant patterns in financial time series. Extensive experiments on real-world financial datasets substantiate the framework's efficacy, demonstrating superior performance in capturing complex market patterns and achieving state-of-the-art results in stock return prediction. The successful deployment in practical trading systems confirms its real-world applicability, representing a significant advancement in LLM applications for financial forecasting.

[Arxiv](https://arxiv.org/abs/2505.02880)