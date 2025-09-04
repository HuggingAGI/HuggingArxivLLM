# AR-KAN：自回归权重增强型科尔莫戈罗夫-阿诺德网络——面向时间序列预测

发布时间：2025年09月02日

`其他` `基础理论`

> AR-KAN: Autoregressive-Weight-Enhanced Kolmogorov-Arnold Network for Time Series Forecasting

# 摘要

> 传统神经网络在信号频谱分析中常遇难题。为应对这一挑战，傅里叶神经网络（FNNs）等方法将傅里叶级数组件融入神经网络结构。然而，一个关键问题常被忽略：周期信号叠加后未必仍是周期信号。例如，在预测由频率不可公度信号构成的概周期函数时，自回归积分移动平均（ARIMA）等传统模型的表现往往优于包括大型语言模型（LLMs）在内的多数神经网络。为此，我们提出自回归权重增强型AR-KAN——一种融合了两种方法优势的混合模型。借助通用短视映射定理，我们将科尔莫戈罗夫-阿诺德网络（KAN）用于静态非线性部分，并通过预训练的AR组件引入记忆机制，该机制能够保留关键信息并剔除冗余。实验数据显示，AR-KAN在【数学公式】的真实世界数据集上表现更优。

> Conventional neural networks frequently face challenges in spectral analysis of signals. To address this challenge, Fourier neural networks (FNNs) and similar approaches integrate components of Fourier series into the structure of neural networks. Nonetheless, a significant hurdle is often overlooked: the superposition of periodic signals does not necessarily result in a periodic signal. For example, when forecasting almost periodic functions composed of signals with incommensurate frequencies, traditional models such as Autoregressive Integrated Moving Average (ARIMA) frequently outperform most neural networks including large language models (LLMs). To tackle this goal, we propose Autoregressive-Weight-Enhanced AR-KAN, a hybrid model that combines the benefits of both methods. Using the Universal Myopic Mapping Theorem, we apply a Kolmogorov-Arnold Network (KAN) for the static nonlinear part and include memory through a pre-trained AR component, which can be explained to retain the most useful information while eliminating redundancy. Experimental data indicates that AR-KAN delivers superior results on $72\%$ of real-world datasets.

[Arxiv](https://arxiv.org/abs/2509.02967)