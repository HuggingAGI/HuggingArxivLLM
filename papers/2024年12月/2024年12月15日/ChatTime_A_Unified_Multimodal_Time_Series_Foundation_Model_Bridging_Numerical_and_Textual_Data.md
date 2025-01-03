# ChatTime: 统一多模态时间序列基础模型，打通数值与文本数据

发布时间：2024年12月15日

`LLM应用

理由：这篇论文主要讨论了如何利用预训练的大型语言模型（LLM）来处理时间序列数据，并将其与文本信息结合，构建了一个名为ChatTime的多模态时间序列基础模型。该模型具备零-shot预测能力，能够处理时间序列和文本的双模态输入/输出。这属于将LLM应用于特定领域（时间序列分析）的实际应用场景，因此归类为“LLM应用”。` `时间序列分析` `多模态数据处理`

> ChatTime: A Unified Multimodal Time Series Foundation Model Bridging Numerical and Textual Data

# 摘要

> 人类专家通常结合数值和文本多模态信息来分析时间序列。然而，传统深度学习预测器大多仅依赖单模态数值数据，使用固定窗口在单一数据集上进行训练和预测，难以适应多样化场景。预训练大型语言模型的出现为时间序列分析带来了新机遇。但现有方法要么训练效率低，要么无法处理文本信息，或缺乏零-shot预测能力。本文创新性地将时间序列建模为“外语”，并构建了ChatTime——一个统一的时间序列与文本处理框架。作为开箱即用的多模态时间序列基础模型，ChatTime具备零-shot预测能力，支持时间序列和文本的双模态输入/输出。我们通过一系列实验验证了ChatTime在多种任务和场景中的卓越性能，并创建了四个多模态数据集填补数据空白。实验结果充分展示了ChatTime的潜力与实用性。

> Human experts typically integrate numerical and textual multimodal information to analyze time series. However, most traditional deep learning predictors rely solely on unimodal numerical data, using a fixed-length window for training and prediction on a single dataset, and cannot adapt to different scenarios. The powered pre-trained large language model has introduced new opportunities for time series analysis. Yet, existing methods are either inefficient in training, incapable of handling textual information, or lack zero-shot forecasting capability. In this paper, we innovatively model time series as a foreign language and construct ChatTime, a unified framework for time series and text processing. As an out-of-the-box multimodal time series foundation model, ChatTime provides zero-shot forecasting capability and supports bimodal input/output for both time series and text. We design a series of experiments to verify the superior performance of ChatTime across multiple tasks and scenarios, and create four multimodal datasets to address data gaps. The experimental results demonstrate the potential and utility of ChatTime.

[Arxiv](https://arxiv.org/abs/2412.11376)