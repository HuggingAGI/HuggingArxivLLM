# PeRL：排列强化的强化学习方法，专为交错视觉语言推理设计

发布时间：2025年06月17日

`LLM应用` `视觉语言模型` `多模态推理`

> PeRL: Permutation-Enhanced Reinforcement Learning for Interleaved Vision-Language Reasoning

# 摘要

> 受强化学习方法（如DeepSeek-R1）出色推理能力的启发，近期研究开始探索利用强化学习（RL）提升视觉语言模型（VLMs）在多模态推理任务中的表现。然而，现有方法大多局限于单图像空间推理，难以推广到多图像位置推理的复杂场景，而理解图像间关系至关重要。为应对这一挑战，我们提出专为交错式多模态任务设计的通用强化学习方法PeRL，以及优化探索与利用平衡的多阶段策略，提升学习效率和任务表现。具体而言，我们通过排列图像序列模拟多样位置关系，探索更多空间和位置多样性。此外，设计回放过滤机制专注于贡献最大轨迹，有效利用已学策略。我们在5个多图像基准和3个单图像基准上评估模型。实验显示，PeRL训练的模型在多图像基准中大幅超越现有基线，达最优性能，同时保持单图像任务的可比表现。

> Inspired by the impressive reasoning capabilities demonstrated by reinforcement learning approaches like DeepSeek-R1, recent emerging research has begun exploring the use of reinforcement learning (RL) to enhance vision-language models (VLMs) for multimodal reasoning tasks. However, most existing multimodal reinforcement learning approaches remain limited to spatial reasoning within single-image contexts, yet still struggle to generalize to more complex and real-world scenarios involving multi-image positional reasoning, where understanding the relationships across images is crucial. To address this challenge, we propose a general reinforcement learning approach PeRL tailored for interleaved multimodal tasks, and a multi-stage strategy designed to enhance the exploration-exploitation trade-off, thereby improving learning efficiency and task performance. Specifically, we introduce permutation of image sequences to simulate varied positional relationships to explore more spatial and positional diversity. Furthermore, we design a rollout filtering mechanism for resampling to focus on trajectories that contribute most to learning optimal behaviors to exploit learned policies effectively. We evaluate our model on 5 widely-used multi-image benchmarks and 3 single-image benchmarks. Our experiments confirm that PeRL trained model consistently surpasses R1-related and interleaved VLM baselines by a large margin, achieving state-of-the-art performance on multi-image benchmarks, while preserving comparable performance on single-image tasks.

[Arxiv](https://arxiv.org/abs/2506.14907)