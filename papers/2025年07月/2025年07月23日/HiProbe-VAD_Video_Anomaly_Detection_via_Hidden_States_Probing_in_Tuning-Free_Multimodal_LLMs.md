# HiProbe-VAD：无需调优的多模态大语言模型中的隐藏状态探测用于视频异常检测

发布时间：2025年07月23日

`LLM应用` `视频分析` `计算机视觉`

> HiProbe-VAD: Video Anomaly Detection via Hidden States Probing in Tuning-Free Multimodal LLMs

# 摘要

> 视频异常检测（VAD）旨在识别并定位视频序列中的异常现象。然而，传统方法往往面临计算需求高、依赖大量标注数据的挑战，限制了其实际应用。为了解决这些问题，我们提出了HiProbe-VAD，这是一个无需微调、基于预训练多模态大语言模型（MLLMs）的全新框架。研究发现，MLLMs的中间隐藏状态包含了信息丰富的表征，相较于输出层，这些表征在异常检测中表现出更高的敏感性和线性可分性。为此，我们提出了一种动态层重要性探测（DLSP）机制，能够智能地识别并提取MLLMs推理过程中最优中间层的最具信息量的隐藏状态。随后，通过轻量级异常评分器和时序定位模块，利用提取的隐藏状态高效地检测异常并生成解释。实验结果表明，在UCF-Crime和XD-Violence数据集上，HiProbe-VAD在无训练模式下优于现有方法，并且在大多数传统方法中也表现出色。此外，我们的框架在不同MLLMs上展现出显著的跨模型泛化能力，无需任何调优，为预训练MLLMs在视频异常检测中的应用开辟了新可能，并为更实际、可扩展的解决方案铺平了道路。

> Video Anomaly Detection (VAD) aims to identify and locate deviations from normal patterns in video sequences. Traditional methods often struggle with substantial computational demands and a reliance on extensive labeled datasets, thereby restricting their practical applicability. To address these constraints, we propose HiProbe-VAD, a novel framework that leverages pre-trained Multimodal Large Language Models (MLLMs) for VAD without requiring fine-tuning. In this paper, we discover that the intermediate hidden states of MLLMs contain information-rich representations, exhibiting higher sensitivity and linear separability for anomalies compared to the output layer. To capitalize on this, we propose a Dynamic Layer Saliency Probing (DLSP) mechanism that intelligently identifies and extracts the most informative hidden states from the optimal intermediate layer during the MLLMs reasoning. Then a lightweight anomaly scorer and temporal localization module efficiently detects anomalies using these extracted hidden states and finally generate explanations. Experiments on the UCF-Crime and XD-Violence datasets demonstrate that HiProbe-VAD outperforms existing training-free and most traditional approaches. Furthermore, our framework exhibits remarkable cross-model generalization capabilities in different MLLMs without any tuning, unlocking the potential of pre-trained MLLMs for video anomaly detection and paving the way for more practical and scalable solutions.

[Arxiv](https://arxiv.org/abs/2507.17394)