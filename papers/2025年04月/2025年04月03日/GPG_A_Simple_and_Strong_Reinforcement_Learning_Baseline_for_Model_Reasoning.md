# GPG：简单而强效的强化学习基线，助力模型推理

发布时间：2025年04月03日

`LLM理论`

> GPG: A Simple and Strong Reinforcement Learning Baseline for Model Reasoning

# 摘要

> 强化学习（RL）能够直接提升大型语言模型的推理能力，而无需过多依赖监督微调（SFT）。在本研究中，我们重新审视了传统的策略梯度（PG）机制，并提出了一种极简的强化学习方法——组策略梯度（GPG）。与传统方法不同，GPG直接优化原始的强化学习目标，从而无需使用替代损失函数。通过摒弃评论家和参考模型，并避免KL散度约束，我们的方法使训练过程相较于组相对策略优化（GRPO）显著简化。我们的方法在不依赖任何辅助技术或调整的情况下实现了卓越的性能。大量实验表明，我们的方法不仅降低了计算成本，而且在各种单模态和多模态任务中均优于GRPO。我们的代码可在GitHub上获取：https://github.com/AMAP-ML/GPG。

> Reinforcement Learning (RL) can directly enhance the reasoning capabilities of large language models without extensive reliance on Supervised Fine-Tuning (SFT). In this work, we revisit the traditional Policy Gradient (PG) mechanism and propose a minimalist RL approach termed Group Policy Gradient (GPG). Unlike conventional methods, GPG directly optimize the original RL objective, thus obviating the need for surrogate loss functions. As illustrated in our paper, by eliminating both the critic and reference models, and avoiding KL divergence constraints, our approach significantly simplifies the training process when compared to Group Relative Policy Optimization (GRPO). Our approach achieves superior performance without relying on auxiliary techniques or adjustments. Extensive experiments demonstrate that our method not only reduces computational costs but also consistently outperforms GRPO across various unimodal and multimodal tasks. Our code is available at https://github.com/AMAP-ML/GPG.

[Arxiv](https://arxiv.org/abs/2504.02546)