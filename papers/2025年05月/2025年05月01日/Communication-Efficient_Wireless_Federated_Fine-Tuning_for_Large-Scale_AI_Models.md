# 高效通信无线联邦微调大规模AI模型

发布时间：2025年05月01日

`LLM应用` `联邦学习` `无线通信`

> Communication-Efficient Wireless Federated Fine-Tuning for Large-Scale AI Models

# 摘要

> 基于Transformer的大语言模型（LLMs）在各项任务中表现卓越。然而，联邦学习（FL）环境下的模型微调面临资源限制和通信开销的双重挑战。低秩适配（LoRA）通过训练紧凑的低秩矩阵，而非完全微调大型模型，有效解决了这些问题。本文提出了一种无线联邦LoRA微调框架，兼顾优化学习性能与通信效率。我们进行了创新性的收敛性分析，揭示了LoRA秩和协方差效应对FL训练动态的影响。基于此，我们提出了稀疏正交微调（	extbf{SOFT}），一种无需昂贵矩阵运算和奇异值分解（SVD）的自适应稀疏化方法，可简化参数更新流程。此外，我们还开发了两阶段联邦算法（	extbf{TSFA}），通过离线预设关键参数，并在线动态调整带宽和稀疏化程度，在延迟约束下实现高效训练。在基准数据集上的实验结果表明，我们的方法不仅达到了理想场景模型的精度水平，还大幅降低了通信开销。因此，本框架为在现实世界的无线FL场景中实现大规模模型的可扩展、资源高效的部署提供了全新可能。

> Transformer-based large language models (LLMs) have achieved remarkable success across various tasks. Yet, fine-tuning such massive models in federated learning (FL) settings poses significant challenges due to resource constraints and communication overhead. Low-Rank Adaptation (LoRA) addresses these issues by training compact, low-rank matrices instead of fully fine-tuning large models. This paper introduces a wireless federated LoRA fine-tuning framework that optimizes both learning performance and communication efficiency. We provide a novel convergence analysis, revealing how LoRA rank and covariance effects influence FL training dynamics. Leveraging these insights, we propose Sparsified Orthogonal Fine-Tuning (\textbf{SOFT}), an adaptive sparsification method that streamlines parameter updates without expensive matrix multiplications and singular value decomposition (SVD) operations. Additionally, we present a Two Stage Federated Algorithm (\textbf{TSFA}) algorithm that pre-determines key parameters offline and dynamically adjusts bandwidth and sparsification online, ensuring efficient training under latency constraints. Experiments on benchmark datasets show that our approach achieves accuracy comparable to ideal scenario models while significantly reducing communication overhead. Our framework thus enables scalable, resource-efficient deployment of large models in real-world wireless FL scenarios.

[Arxiv](https://arxiv.org/abs/2505.00333)