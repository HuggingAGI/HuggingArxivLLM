# VCRL：面向大型语言模型的基于方差的课程式强化学习

发布时间：2025年09月24日

`强化学习` `基础理论`

> VCRL: Variance-based Curriculum Reinforcement Learning for Large Language Models

# 摘要

> 基于策略的强化学习如今在提升大型语言模型（LLMs）的数学推理能力方面扮演着关键角色。然而，现有的基于轨迹的强化学习方法（如GRPO、DAPO、GSPO等）未能充分考虑LLMs对不同难度样本的学习规律，这与人类数学推理中“由易到难”的认知逻辑相悖。我们直观地发现，RLVR中轨迹组奖励的方差在一定程度上反映了当前样本对LLMs的难度水平：过于简单或过难的样本方差较低，而中等难度的样本方差较高。基于这一发现，我们提出了VCRL——一种基于组奖励方差动态调控训练样本难度的课程强化学习框架。在五个数学基准数据集和两个模型上的实验结果表明，VCRL相较于现有的LLM强化学习基线具有显著优势。

> Policy-based reinforcement learning currently plays an important role in improving LLMs on mathematical reasoning tasks. However, existing rollout-based reinforcement learning methods (GRPO, DAPO, GSPO, etc.) fail to explicitly consider LLMs' learning ability for samples of different difficulty levels, which is contrary to the human cognitive process of mathematical reasoning tasks from easy to difficult. Intuitively, we find that the variance of the rollout group's reward in RLVR partly reflects the difficulty of the current sample for LLMs. Samples that are too easy or too difficult have a lower variance, while samples with moderate difficulty have a higher variance. Based on this, we propose VCRL, a curriculum reinforcement learning framework that dynamically controls the difficulty of training samples based on the variance of group rewards. Experiments on five mathematical benchmarks and two models reveal the advantages of VCRL over the current LLM RL baselines.

[Arxiv](https://arxiv.org/abs/2509.19803)