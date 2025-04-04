# ZClip：LLM预训练中的自适应尖峰缓解方案

发布时间：2025年04月03日

`LLM理论` `人工智能` `算法优化`

> ZClip: Adaptive Spike Mitigation for LLM Pre-Training

# 摘要

> 训练大型语言模型 (LLMs) 面临诸多挑战，如梯度不稳定和损失尖峰。这些问题可能导致模型发散，迫使我们耗费资源恢复检查点并跳过数据批次。传统的梯度裁剪方法，如固定阈值或范数裁剪，因依赖静态规则而难以有效应对这些挑战，导致训练效率低下且需要频繁人工干预。为解决这些问题，我们提出了一种名为 ZClip 的自适应梯度裁剪算法。与传统方法不同，ZClip 能根据梯度范数的时序统计特性动态调整裁剪阈值，无需任何先验假设。其核心基于 z 分数异常检测，主动识别并抑制有害的梯度尖峰，同时确保训练过程的正常收敛。我们的实现已开源，欢迎访问 https://github.com/bluorion-com/ZClip 查看。

> Training large language models (LLMs) presents numerous challenges, including gradient instability and loss spikes. These phenomena can lead to catastrophic divergence, requiring costly checkpoint restoration and data batch skipping. Traditional gradient clipping techniques, such as constant or norm-based methods, fail to address these issues effectively due to their reliance on fixed thresholds or heuristics, leading to inefficient learning and requiring frequent manual intervention. In this work, we propose ZClip, an adaptive gradient clipping algorithm that dynamically adjusts the clipping threshold based on statistical properties of gradient norms over time. Unlike prior reactive strategies, ZClip proactively adapts to training dynamics without making any prior assumptions on the scale and the temporal evolution of gradient norms. At its core, it leverages z-score-based anomaly detection to identify and mitigate large gradient spikes, preventing malignant loss spikes while not interfering with convergence otherwise. Our code is available at: https://github.com/bluorion-com/ZClip.

[Arxiv](https://arxiv.org/abs/2504.02507)