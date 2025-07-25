# # 基于线性记忆的 SE(2) 不变注意力机制

发布时间：2025年07月24日

`其他` `自动驾驶` `计算机视觉`

> Linear Memory SE(2) Invariant Attention

# 摘要

> 处理空间数据是自动驾驶中许多学习任务的关键，如运动预测、多智能体仿真和规划。先前研究证明了SE(2)不变性网络架构的价值，这些架构仅考虑物体间的相对姿态（例如其他智能体和车道等场景特征）。然而，这些方法显式计算所有物体对的相对姿态，导致二次内存需求。本研究提出了一种SE(2)不变的缩放点积注意力机制，其内存需求与场景物体数量成线性关系。我们的SE(2)不变性变换器架构享有与近年来使大型语言模型受益相同的扩展特性。实验表明，我们的方法易于实现，并且在性能上超越了非不变性架构。

> Processing spatial data is a key component in many learning tasks for autonomous driving such as motion forecasting, multi-agent simulation, and planning. Prior works have demonstrated the value in using SE(2) invariant network architectures that consider only the relative poses between objects (e.g. other agents, scene features such as traffic lanes). However, these methods compute the relative poses for all pairs of objects explicitly, requiring quadratic memory. In this work, we propose a mechanism for SE(2) invariant scaled dot-product attention that requires linear memory relative to the number of objects in the scene. Our SE(2) invariant transformer architecture enjoys the same scaling properties that have benefited large language models in recent years. We demonstrate experimentally that our approach is practical to implement and improves performance compared to comparable non-invariant architectures.

[Arxiv](https://arxiv.org/abs/2507.18597)