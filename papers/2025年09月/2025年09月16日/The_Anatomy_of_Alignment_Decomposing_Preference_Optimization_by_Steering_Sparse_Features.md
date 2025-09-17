# 对齐的剖析：通过调控稀疏特征分解偏好优化

发布时间：2025年09月16日

`强化学习` `基础理论`

> The Anatomy of Alignment: Decomposing Preference Optimization by Steering Sparse Features

# 摘要

> 大型语言模型的对齐是其可用性与安全性的关键。但主流的基于人类反馈的强化学习（RLHF）方法会导致参数变化分散且不透明，难以判断模型究竟内化了什么。为此，我们提出基于强化学习的特征引导（FSRL）——一种透明的对齐框架，它通过训练轻量级适配器，调节稀疏自编码器（SAE）生成的可解释特征来引导模型行为。首先，我们证实FSRL是一种有效的偏好优化方法，性能与现有RLHF方法相当。接着，对训练后的适配器进行机制分析发现，其策略会系统性地优先强化风格特征而非显式对齐概念，这意味着偏好优化过程实则将风格化表达当作质量的“替身”来奖励。最终，我们希望FSRL能成为兼具可解释模型控制与对齐内部机制诊断功能的工具。

> Aligning large language models is critical for their usability and safety. However, the prevailing approach of Reinforcement Learning from Human Feedback (RLHF) induces diffuse, opaque parameter changes, making it difficult to discern what the model has internalized. Hence, we introduce Feature Steering with Reinforcement Learning (FSRL), a transparent alignment framework that trains a lightweight adapter to steer behavior by modulating interpretable features from a Sparse Autoencoder (SAE). First, we demonstrate that FSRL is an effective method for preference optimization and is comparable with current RLHF methods. We then perform mechanistic analysis on the trained adapter, and find that its policy systematically promotes style features over explicit alignment concepts, suggesting that the preference optimization process rewards stylistic presentation as a proxy for quality. Ultimately, we hope that FSRL provides a tool for both interpretable model control and diagnosing the internal mechanisms of alignment.

[Arxiv](https://arxiv.org/abs/2509.12934)