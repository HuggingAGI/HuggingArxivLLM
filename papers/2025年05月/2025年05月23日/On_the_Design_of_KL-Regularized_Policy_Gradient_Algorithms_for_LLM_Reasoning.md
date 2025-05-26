# 研究用于LLM推理的KL散度正则化策略梯度算法

发布时间：2025年05月23日

`LLM理论` `人工智能` `机器学习`

> On the Design of KL-Regularized Policy Gradient Algorithms for LLM Reasoning

# 摘要

> 策略梯度算法在提升大型语言模型（LLMs）推理能力方面取得了显著成效。尽管KL正则化在策略梯度算法中被广泛用于稳定训练，但如何系统性地探索不同KL散度形式的估计与整合，特别是在在线强化学习（RL）中的代理损失函数设计，仍是一个值得深入研究的复杂问题。为此，我们提出了一种系统性框架——正则化策略梯度（RPG），旨在推导和分析在线强化学习环境中KL正则化的策略梯度方法。我们针对前向和反向KL散度正则化目标，分别推导了策略梯度及其代理损失函数，并考虑了标准化与非标准化的策略分布。此外，我们还提供了完全可微分的损失函数以及REINFORCE风格的梯度估计器，以满足多样化的算法需求。实验结果表明，与GRPO、REINFORCE++和DAPO等强基线方法相比，我们的方法在LLM推理的强化学习任务中展现出更优的训练稳定性和性能。代码已开源，地址为https://github.com/complex-reasoning/RPG。

> Policy gradient algorithms have been successfully applied to enhance the reasoning capabilities of large language models (LLMs). Despite the widespread use of Kullback-Leibler (KL) regularization in policy gradient algorithms to stabilize training, the systematic exploration of how different KL divergence formulations can be estimated and integrated into surrogate loss functions for online reinforcement learning (RL) presents a nuanced and systematically explorable design space. In this paper, we propose regularized policy gradient (RPG), a systematic framework for deriving and analyzing KL-regularized policy gradient methods in the online RL setting. We derive policy gradients and corresponding surrogate loss functions for objectives regularized by both forward and reverse KL divergences, considering both normalized and unnormalized policy distributions. Furthermore, we present derivations for fully differentiable loss functions as well as REINFORCE-style gradient estimators, accommodating diverse algorithmic needs. We conduct extensive experiments on RL for LLM reasoning using these methods, showing improved or competitive results in terms of training stability and performance compared to strong baselines such as GRPO, REINFORCE++, and DAPO. The code is available at https://github.com/complex-reasoning/RPG.

[Arxiv](https://arxiv.org/abs/2505.17508)