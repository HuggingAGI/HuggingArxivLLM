# # LVM4CSI：无线信道任务中预训练大视觉模型的直接应用

发布时间：2025年07月07日

`其他

理由：这篇论文探讨了大规模视觉模型（LVMs）在无线通信中的应用，特别是将CSI任务映射到类似计算机视觉任务，以提高无线通信系统的性能。虽然涉及到了AI和模型的应用，但它并不专注于大型语言模型（LLM）的理论或应用，而是聚焦于视觉模型在通信领域的应用，因此归类为其他。` `无线通信` `计算机视觉`

> LVM4CSI: Enabling Direct Application of Pre-Trained Large Vision Models for Wireless Channel Tasks

# 摘要

> 信道状态信息（CSI）的准确性对无线通信系统至关重要，尤其是在5G和6G技术带来的复杂性日益增加的背景下。人工智能（AI）为CSI的获取和利用提供了新思路，但现有方法主要依赖于任务特定的神经网络（NN），这些网络需要专家设计和大量数据支持，限制了其通用性和实用性。为此，我们提出了LVM4CSI框架，该框架利用CSI与计算机视觉（CV）数据的结构相似性，直接将大规模视觉模型（LVMs）应用于无线任务，无需微调，这与通常需要微调的基于大语言模型的方法不同。LVM4CSI通过将CSI任务映射到类似CV任务、将复数CSI转换为视觉格式，并整合轻量级可训练层，使其能够适应特定通信目标。我们通过信道估计、人类活动识别和用户定位三个案例验证了LVM4CSI的效能。实验结果表明，LVM4CSI在性能上与任务特定的NN相当或更优，其中信道估计改善超过9.61 dB，定位误差减少约40%。此外，LVM4CSI显著减少了可训练参数数量，无需任务特定的网络设计，展现了其高效性和通用性。

> Accurate channel state information (CSI) is critical to the performance of wireless communication systems, especially with the increasing scale and complexity introduced by 5G and future 6G technologies. While artificial intelligence (AI) offers a promising approach to CSI acquisition and utilization, existing methods largely depend on task-specific neural networks (NNs) that require expert-driven design and large training datasets, limiting their generalizability and practicality. To address these challenges, we propose LVM4CSI, a general and efficient framework that leverages the structural similarity between CSI and computer vision (CV) data to directly apply large vision models (LVMs) pre-trained on extensive CV datasets to wireless tasks without any fine-tuning, in contrast to large language model-based methods that generally necessitate fine-tuning. LVM4CSI maps CSI tasks to analogous CV tasks, transforms complex-valued CSI into visual formats compatible with LVMs, and integrates lightweight trainable layers to adapt extracted features to specific communication objectives. We validate LVM4CSI through three representative case studies, including channel estimation, human activity recognition, and user localization. Results demonstrate that LVM4CSI achieves comparable or superior performance to task-specific NNs, including an improvement exceeding 9.61 dB in channel estimation and approximately 40% reduction in localization error. Furthermore, it significantly reduces the number of trainable parameters and eliminates the need for task-specific NN design.

[Arxiv](https://arxiv.org/abs/2507.05121)