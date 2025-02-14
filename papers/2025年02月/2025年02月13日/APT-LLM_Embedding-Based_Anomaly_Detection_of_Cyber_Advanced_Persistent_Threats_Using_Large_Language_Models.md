# APT-LLM: 基于嵌入的网络高级持续性威胁异常检测，采用大型语言模型

发布时间：2025年02月13日

`LLM应用

理由：这篇论文将大型语言模型（LLMs）应用于网络安全领域，具体用于检测高级持续性威胁（APTs）。通过整合LLMs与自编码器架构，提出了一种新型的异常检测框架，展示了LLMs在特征提取方面的有效性。因此，它属于LLM应用类别。` `网络安全` `网络威胁检测`

> APT-LLM: Embedding-Based Anomaly Detection of Cyber Advanced Persistent Threats Using Large Language Models

# 摘要

> 高级持续性威胁（APTs）因其隐蔽性和模拟正常系统行为的能力，给网络安全带来了重大挑战，尤其在高度不平衡的数据集中，检测难度极大。传统异常检测方法在区分APT相关活动与良性进程方面效果不佳，限制了其在实际场景中的应用。本文介绍了APT-LLM，一种基于嵌入的新型异常检测框架，整合了大型语言模型（LLMs）——BERT、ALBERT、DistilBERT和RoBERTa——与自编码器架构，用于检测APTs。与依赖手动设计特征或传统异常检测模型的先前方法不同，APT-LLM利用LLMs将进程-动作血缘轨迹编码为语义丰富的嵌入，捕捉细微的行为模式。这些嵌入通过三种自编码器架构——基线自编码器（AE）、变分自编码器（VAE）和去噪自编码器（DAE）——进行分析，以建模正常进程行为并识别异常。选择性能最佳的模型与传统方法进行比较。该框架在 DARPA 透明计算计划提供的真实世界、高度不平衡的血缘轨迹数据集上进行评估，其中APT类攻击在多个操作系统（Android、Linux、BSD 和 Windows）和攻击场景下的数据占比低至0.004%。实验结果表明，APT-LLM在极端不平衡条件下显著提升了检测性能，超越现有异常检测方法，凸显了基于LLM的特征提取在网络安全中的有效性。

> Advanced Persistent Threats (APTs) pose a major cybersecurity challenge due to their stealth and ability to mimic normal system behavior, making detection particularly difficult in highly imbalanced datasets. Traditional anomaly detection methods struggle to effectively differentiate APT-related activities from benign processes, limiting their applicability in real-world scenarios. This paper introduces APT-LLM, a novel embedding-based anomaly detection framework that integrates large language models (LLMs) -- BERT, ALBERT, DistilBERT, and RoBERTa -- with autoencoder architectures to detect APTs. Unlike prior approaches, which rely on manually engineered features or conventional anomaly detection models, APT-LLM leverages LLMs to encode process-action provenance traces into semantically rich embeddings, capturing nuanced behavioral patterns. These embeddings are analyzed using three autoencoder architectures -- Baseline Autoencoder (AE), Variational Autoencoder (VAE), and Denoising Autoencoder (DAE) -- to model normal process behavior and identify anomalies. The best-performing model is selected for comparison against traditional methods. The framework is evaluated on real-world, highly imbalanced provenance trace datasets from the DARPA Transparent Computing program, where APT-like attacks constitute as little as 0.004\% of the data across multiple operating systems (Android, Linux, BSD, and Windows) and attack scenarios. Results demonstrate that APT-LLM significantly improves detection performance under extreme imbalance conditions, outperforming existing anomaly detection methods and highlighting the effectiveness of LLM-based feature extraction in cybersecurity.

[Arxiv](https://arxiv.org/abs/2502.09385)