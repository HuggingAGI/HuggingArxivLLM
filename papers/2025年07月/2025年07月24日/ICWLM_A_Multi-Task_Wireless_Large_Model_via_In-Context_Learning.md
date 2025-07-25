# ICWLM：基于上下文学习的多任务无线大模型

发布时间：2025年07月24日

`LLM应用` `无线通信` `人工智能`

> ICWLM: A Multi-Task Wireless Large Model via In-Context Learning

# 摘要

> 无线通信技术的飞速发展，特别是大规模多输入多输出（mMIMO）和毫米波技术，给网络带来了巨大的复杂性和计算需求。尽管深度学习方法在提升物理层性能方面取得了显著进展，但这些方法通常具有任务特异性，难以应对数据稀缺和泛化问题。为了解决这些挑战，我们提出了一种新颖的上下文无线大模型（ICWLM），这是一种专为物理层多任务学习设计的原生无线基础模型。与传统方法将无线数据适配到预训练的大语言模型（LLMs）不同，ICWLM是从零开始直接在大规模混合无线数据集上进行训练。它能够同时解决多个经典的物理层问题，包括多用户预编码（总速率最大化和最大化最小SINR）以及信道预测。ICWLM的关键创新在于采用了上下文学习（ICL），使得模型仅需少量演示配对即可适应不同的系统配置和信道条件，从而避免了大规模重新训练的需要。此外，我们还采用了动态权重平均（DWA）算法，在多任务训练过程中动态平衡各个任务的损失函数，确保在不同目标下实现高效稳定的学习。大量仿真结果表明，与特定任务的方法相比，ICWLM不仅能够达到竞争性性能，还展现出对未知系统配置的卓越泛化能力。这项研究为未来无线网络中统一且自适应的AI模型开发提供了一个有前景的范式，有望降低部署复杂性并提升智能资源管理能力。

> The rapid evolution of wireless communication technologies, particularly massive multiple-input multiple-output (mMIMO) and millimeter-wave (mmWave), introduces significant network complexity and computational demands. Significant research efforts have been made to improve physical layer performance by resorting to deep learning (DL) methods, which, however, are usually task-specific and struggle with data scarcity and generalization. To address these challenges, we propose a novel In-Context Wireless Large Model (ICWLM), a wireless-native foundation model designed for simultaneous multi-task learning at the physical layer. Unlike conventional methods that adapt wireless data to pre-trained large language models (LLMs), ICWLM is trained directly on large-scale, mixed wireless datasets from scratch. It jointly solves multiple classical physical layer problems, including multi-user precoding (sum-rate maximization and max-min SINR) and channel prediction. A key innovation of ICWLM is its utilization of in-context learning (ICL), enabling the model to adapt to varying system configurations and channel conditions with minimal demonstration pairs, eliminating the need for extensive retraining. Furthermore, we employ the Dynamic Weight Averaging (DWA) algorithm to dynamically balance the individual task losses during multi-task training, ensuring efficient and stable learning across diverse objectives. Extensive simulation results demonstrate that ICWLM achieves competitive performance compared to task-specific methods while exhibiting remarkable generalization capabilities to unseen system configurations. This work offers a promising paradigm for developing unified and adaptive AI models for future wireless networks, potentially reducing deployment complexity and enhancing intelligent resource management.

[Arxiv](https://arxiv.org/abs/2507.18167)