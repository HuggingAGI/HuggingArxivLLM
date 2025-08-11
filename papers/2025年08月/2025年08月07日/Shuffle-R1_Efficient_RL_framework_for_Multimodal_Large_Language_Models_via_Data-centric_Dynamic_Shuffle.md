# Shuffle-R1：基于数据驱动动态混洗的多模态大型语言模型高效强化学习框架

发布时间：2025年08月07日

`LLM应用` `人工智能`

> Shuffle-R1: Efficient RL framework for Multimodal Large Language Models via Data-centric Dynamic Shuffle

# 摘要

> 强化学习（RL）作为提升多模态大型语言模型（MLLM）推理能力的有效后训练范式，却常常面临训练效率低下的挑战。这一现象主要源于两个尚未充分探索的问题：优势坍塌（Advantage Collapsing），即批次中的大部分优势集中在零附近，以及轨迹沉默（Rollout Silencing），即随时间推移，贡献非零梯度的轨迹比例逐渐减少。这些问题导致次优的梯度更新，阻碍了长期学习效率。

为了解决这些问题，我们提出了Shuffle-R1框架。这一框架通过动态重构轨迹采样和批次组成，显著提升了RL微调效率。具体而言，Shuffle-R1引入了两个关键创新：成对轨迹采样（Pairwise Trajectory Sampling），通过选择具有较大优势的高对比度轨迹来提升梯度信号质量；以及基于优势的轨迹洗牌（Advantage-based Trajectory Shuffle），通过有信息的批次重新排列增加有价值轨迹的暴露。

实验结果表明，在多个推理基准上，Shuffle-R1在仅增加极小开销的情况下，始终优于强大的RL基线。这些结果凸显了数据为中心的适应方法在MLLM中实现更高效RL训练的重要性。


> Reinforcement learning (RL) has emerged as an effective post-training paradigm for enhancing the reasoning capabilities of multimodal large language model (MLLM). However, current RL pipelines often suffer from training inefficiencies caused by two underexplored issues: Advantage Collapsing, where most advantages in a batch concentrate near zero, and Rollout Silencing, where the proportion of rollouts contributing non-zero gradients diminishes over time. These issues lead to suboptimal gradient updates and hinder long-term learning efficiency. To address these issues, we propose Shuffle-R1, a simple yet principled framework that improves RL fine-tuning efficiency by dynamically restructuring trajectory sampling and batch composition. It introduces (1) Pairwise Trajectory Sampling, which selects high-contrast trajectories with large advantages to improve gradient signal quality, and (2) Advantage-based Trajectory Shuffle, which increases exposure of valuable rollouts through informed batch reshuffling. Experiments across multiple reasoning benchmarks show that our framework consistently outperforms strong RL baselines with minimal overhead. These results highlight the importance of data-centric adaptations for more efficient RL training in MLLM.

[Arxiv](https://arxiv.org/abs/2508.05612)