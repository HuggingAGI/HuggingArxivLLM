# CLONE：定制 LLM 实现高效延迟感知推理，赋能边缘端

发布时间：2025年06月03日

`LLM应用` `边缘计算` `物联网`

> CLONE: Customizing LLMs for Efficient Latency-Aware Inference at the Edge

# 摘要

> 在边缘设备上部署大型语言模型（LLMs）对于实现快速响应和保障数据隐私至关重要。然而，边缘设备的存储空间、功耗和计算能力有限，使得部署基于LLMs的应用程序变得困难。这些设备需要在延迟需求、能耗和模型精度之间取得平衡。本文首先量化了在现成边缘设备上部署LLMs所面临的挑战，然后我们提出了CLONE，这是一种从模型到系统层面的深入算法-硬件协同设计方法，能够在保持强大通用性的同时，智能地实现实时能量优化。为了在始终在线和中间边缘计算环境中最大化这些算法的协同效益，我们专注于一个28nm可扩展硬件加速器系统。我们在两个现成的边缘平台上实现了CLONE并进行了广泛评估。实验结果表明，CLONE能够将推理速度提升高达11.92倍，同时节省7.36倍的能耗，同时保持生成质量。

> Deploying large language models (LLMs) on edge devices is crucial for delivering fast responses and ensuring data privacy. However, the limited storage, weight, and power of edge devices make it difficult to deploy LLM-powered applications. These devices must balance latency requirements with energy consumption and model accuracy. In this paper, we first quantify the challenges of deploying LLMs on off-the-shelf edge devices and then we present CLONE, an in-depth algorithm-hardware co-design at both the model- and system-level that intelligently integrates real-time, energy optimization while maintaining robust generality. In order to maximize the synergistic benefits of these algorithms in always-on and intermediate edge computing settings, we specialize in a 28nm scalable hardware accelerator system. We implement and extensively evaluate CLONE on two off-the-shelf edge platforms. Experiments show that CLONE effectively accelerates the inference process up to 11.92x, and saves energy up to 7.36x, while maintaining high-generation.

[Arxiv](https://arxiv.org/abs/2506.02847)