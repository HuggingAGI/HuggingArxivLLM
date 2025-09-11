# # RewardDance：视觉生成中的奖励缩放

发布时间：2025年09月10日

`强化学习` `媒体与娱乐`

> RewardDance: Reward Scaling in Visual Generation

# 摘要

> 奖励模型（RMs）是通过强化学习（RL）提升生成模型性能的核心，但视觉生成领域的RM缩放范式却一直未被充分探索。这主要源于现有方法的固有局限：基于CLIP的RM受限于架构和输入模态，而主流的Bradley-Terry损失则与视觉语言模型（VLM）的下token预测机制存在本质错位，严重阻碍了有效缩放。更严重的是，RLHF优化过程长期受“奖励黑客”问题困扰——模型会利用奖励信号的漏洞，却不提升真实质量。

为应对这些挑战，我们提出了RewardDance——一个可扩展的奖励建模框架，它通过全新的生成式奖励范式突破了这些瓶颈。RewardDance将奖励分数重构为模型预测“是”token的概率（即生成图像按特定标准优于参考图像），从而使奖励目标与VLM架构实现内在对齐。这种对齐解锁了双重缩放能力：（1）模型缩放——将RM系统性扩展至260亿参数；（2）上下文缩放——融入任务专属指令、参考示例及思维链（CoT）推理。

大量实验证实，RewardDance在文本到图像、文本到视频及图像到视频生成任务上均显著超越现有最优方法。更重要的是，我们攻克了“奖励黑客”这一顽疾：大规模RM在RL微调中展现并维持高奖励方差，不仅能抵抗黑客攻击，还能生成多样化的高质量输出，有效缓解了小型模型普遍面临的模式崩溃问题。

> Reward Models (RMs) are critical for improving generation models via Reinforcement Learning (RL), yet the RM scaling paradigm in visual generation remains largely unexplored. It primarily due to fundamental limitations in existing approaches: CLIP-based RMs suffer from architectural and input modality constraints, while prevalent Bradley-Terry losses are fundamentally misaligned with the next-token prediction mechanism of Vision-Language Models (VLMs), hindering effective scaling. More critically, the RLHF optimization process is plagued by Reward Hacking issue, where models exploit flaws in the reward signal without improving true quality. To address these challenges, we introduce RewardDance, a scalable reward modeling framework that overcomes these barriers through a novel generative reward paradigm. By reformulating the reward score as the model's probability of predicting a "yes" token, indicating that the generated image outperforms a reference image according to specific criteria, RewardDance intrinsically aligns reward objectives with VLM architectures. This alignment unlocks scaling across two dimensions: (1) Model Scaling: Systematic scaling of RMs up to 26 billion parameters; (2) Context Scaling: Integration of task-specific instructions, reference examples, and chain-of-thought (CoT) reasoning. Extensive experiments demonstrate that RewardDance significantly surpasses state-of-the-art methods in text-to-image, text-to-video, and image-to-video generation. Crucially, we resolve the persistent challenge of "reward hacking": Our large-scale RMs exhibit and maintain high reward variance during RL fine-tuning, proving their resistance to hacking and ability to produce diverse, high-quality outputs. It greatly relieves the mode collapse problem that plagues smaller models.

[Arxiv](https://arxiv.org/abs/2509.08826)