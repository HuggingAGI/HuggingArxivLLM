# 重新审视，审慎思考：增强视觉语言模型的视觉反思

发布时间：2025年09月15日

`LLM应用` `基础理论`

> Look Again, Think Slowly: Enhancing Visual Reflection in Vision-Language Models

# 摘要

> 仅文本领域“慢思考”推理的最新进展，推动了将这种能力迁移至视觉语言模型（VLMs）以训练视觉推理模型（VRMs）的研究。然而，这种迁移面临关键挑战：VRMs 要实现有效的“慢思考”，就需要具备视觉反思能力——即基于视觉信息检查推理过程的能力。通过定量分析我们发现，当前 VRMs 的视觉反思能力有限，其对视觉信息的关注度会随着生成的响应变长而迅速下降。为解决这一问题，我们提出了一种新的 VRM——Reflection-V，它通过冷启动阶段的推理数据构建和强化学习（RL）的奖励设计来增强视觉反思能力。首先，我们借助一个在 VLMs 和推理 LLMs 之间交互的智能体，构建以视觉为中心的推理数据，实现视觉反思模式的冷启动学习。其次，在 RL 阶段引入基于视觉注意力的奖励模型，激励模型基于视觉信息进行推理。因此，Reflection-V 在多个视觉推理基准测试中均取得了显著提升。此外，该模型在视觉推理过程中对视觉信息的依赖更强且更稳定，表明其视觉反思能力得到了有效增强。

> Recent advances in text-only "slow-thinking" reasoning have prompted efforts to transfer this capability to vision-language models (VLMs), for training visual reasoning models (\textbf{VRMs}). owever, such transfer faces critical challenges: Effective "slow thinking" in VRMs requires \textbf{visual reflection}, the ability to check the reasoning process based on visual information. Through quantitative analysis, we observe that current VRMs exhibit limited visual reflection, as their attention to visual information diminishes rapidly with longer generated responses. To address this challenge, we propose a new VRM \textbf{Reflection-V}, which enhances visual reflection based on reasoning data construction for cold-start and reward design for reinforcement learning (RL). Firstly, we construct vision-centered reasoning data by leveraging an agent that interacts between VLMs and reasoning LLMs, enabling cold-start learning of visual reflection patterns. Secondly, a visual attention based reward model is employed during RL to encourage reasoning based on visual information. Therefore, \textbf{Reflection-V} demonstrates significant improvements across multiple visual reasoning benchmarks. Furthermore, \textbf{Reflection-V} maintains a stronger and more consistent reliance on visual information during visual reasoning, indicating effective enhancement in visual reflection capabilities.

[Arxiv](https://arxiv.org/abs/2509.12132)