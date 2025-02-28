# 检索增强异常检测（RAAD）：无需再训练的敏捷模型微调

发布时间：2025年02月26日

`LLM应用` `网络安全` `信息安全`

> Retrieval Augmented Anomaly Detection (RAAD): Nimble Model Adjustment Without Retraining

# 摘要

> 我们提出了一种专注于减少误报的实时反馈新机制，旨在提升异常检测模型的性能。该机制专为行为网络异常检测模型的轻量化部署而设计。此方法论易于集成到类似领域，在保持高精度的同时，特别注重吞吐量的优化。在本文中，我们介绍了检索增强异常检测（Retrieval Augmented Anomaly Detection），这是一种从检索增强生成中汲取灵感的创新方法。人类标注的示例会被发送到向量数据库中，该数据库能够在处理下一个批次时实时修改模型输出，从而优化模型推理效果。为了验证这一技术的通用性，我们对多种不同的模型架构以及包括图像、文本和基于图的数据等多种数据模式进行了基准测试。

> We propose a novel mechanism for real-time (human-in-the-loop) feedback focused on false positive reduction to enhance anomaly detection models. It was designed for the lightweight deployment of a behavioral network anomaly detection model. This methodology is easily integrable to similar domains that require a premium on throughput while maintaining high precision. In this paper, we introduce Retrieval Augmented Anomaly Detection, a novel method taking inspiration from Retrieval Augmented Generation. Human annotated examples are sent to a vector store, which can modify model outputs on the very next processed batch for model inference. To demonstrate the generalization of this technique, we benchmarked several different model architectures and multiple data modalities, including images, text, and graph-based data.

[Arxiv](https://arxiv.org/abs/2502.19534)