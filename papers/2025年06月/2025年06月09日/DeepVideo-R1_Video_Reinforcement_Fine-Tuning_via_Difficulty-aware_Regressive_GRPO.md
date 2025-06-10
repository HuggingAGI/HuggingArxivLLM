# DeepVideo-R1：基于难度感知的回归GRPO方法实现视频强化微调

发布时间：2025年06月09日

`LLM应用

理由：这篇论文探讨了如何将强化学习方法应用于视频大型语言模型，以提升其推理能力。具体来说，它提出了新的训练策略（Reg-GRPO）和数据增强方法，以解决在视频LLMs中应用组相对策略优化时遇到的问题。这些改进直接针对视频推理任务的性能提升，因此属于LLM应用领域。` `视频分析` `视频推理`

> DeepVideo-R1: Video Reinforcement Fine-Tuning via Difficulty-aware Regressive GRPO

# 摘要

> 近期研究表明，基于强化学习（RL）的后训练方法在提升大型语言模型（LLMs）的推理能力方面具有显著效果。其中，组相对策略优化（GRPO）通过采用基于组的标准化奖励和PPO风格的强化算法，取得了令人瞩目的成功。然而，将组相对策略优化（GRPO）应用于视频大型语言模型（Video LLMs）的研究较少。本文探讨了GRPO在视频LLMs中的应用，并发现阻碍其有效学习的两大主要问题：（1）对保护措施的依赖，以及（2）优势消失问题。为应对这些挑战，我们提出了DeepVideo-R1，这是一个通过我们提出的Reg-GRPO（回归式GRPO）和难度感知数据增强策略训练的视频大型语言模型。Reg-GRPO将GRPO目标重新表述为回归任务，直接预测GRPO中的优势值。这种设计消除了对剪裁和最小函数等保护措施的依赖，从而通过与优势值对齐，使模型能够获得更直接的策略指导。我们还设计了一种难度感知的数据增强策略，能够在可解决的难度水平上动态增强训练样本，从而促进多样且信息丰富的奖励信号的生成。我们的全面实验表明，DeepVideo-R1在多个视频推理基准测试中显著提升了视频推理性能。

> Recent works have demonstrated the effectiveness of reinforcement learning (RL)-based post-training in enhancing the reasoning capabilities of large language models (LLMs). In particular, Group Relative Policy Optimization (GRPO) has shown impressive success by employing a PPO-style reinforcement algorithm with group-based normalized rewards. However, the application of GRPO to Video Large Language Models (Video LLMs) has been less studied. In this paper, we explore GRPO for video LLMs and identify two primary issues that impede its effective learning: (1) reliance on safeguards, and (2) the vanishing advantage problem. To mitigate these challenges, we propose DeepVideo-R1, a video large language model trained with our proposed Reg-GRPO (Regressive GRPO) and difficulty-aware data augmentation strategy. Reg-GRPO reformulates the GRPO objective as a regression task, directly predicting the advantage in GRPO. This design eliminates the need for safeguards like clipping and min functions, thereby facilitating more direct policy guidance by aligning the model with the advantage values. We also design the difficulty-aware data augmentation strategy that dynamically augments training samples at solvable difficulty levels, fostering diverse and informative reward signals. Our comprehensive experiments show that DeepVideo-R1 significantly improves video reasoning performance across multiple video reasoning benchmarks.

[Arxiv](https://arxiv.org/abs/2506.07464)