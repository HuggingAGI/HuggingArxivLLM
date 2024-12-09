# 以最小反馈实现最大对齐：高效学习视觉运动机器人策略对齐的奖励

发布时间：2024年12月06日

`LLM应用` `机器人`

> Maximizing Alignment with Minimal Feedback: Efficiently Learning Rewards for Visuomotor Robot Policy Alignment

# 摘要

> Visuomotor 机器人策略在大规模数据集上的预训练愈发频繁，有望在机器人领域实现重大突破。然而，让这些策略契合终端用户的偏好仍是难题，尤其是在偏好难以明确表述时。尽管基于人类反馈的强化学习（RLHF）已成为诸如大型语言模型等非实体领域中的主流对齐机制，但由于学习视觉奖励函数需要大量人类反馈，它在 visuomotor 策略的对齐方面尚未取得同样成效。为应对这一局限，我们提出了基于表示对齐偏好的学习（RAPL），这是一种仅依靠观察、从极少的人类偏好反馈中学习视觉奖励的方法。与传统的 RLHF 不同，RAPL 把人类反馈集中用于微调预训练的视觉编码器，使之与终端用户的视觉表示相契合，然后在这一契合的表示空间中通过特征匹配构建密集的视觉奖励。我们先是通过 X-Magical 基准和 Franka Panda 机器人操作中的模拟实验对 RAPL 进行了验证，结果表明它能够习得与人类偏好相符的奖励，更高效地利用偏好数据，并在不同机器人实体中实现泛化。最后，我们的硬件实验为三个对象操作任务对齐了预训练的扩散策略。我们发现 RAPL 能够用少 5 倍的真实人类偏好数据对这些策略进行微调，在最大程度减少人类反馈的同时最大程度实现 visuomotor 机器人策略对齐方面迈出了第一步。

> Visuomotor robot policies, increasingly pre-trained on large-scale datasets, promise significant advancements across robotics domains. However, aligning these policies with end-user preferences remains a challenge, particularly when the preferences are hard to specify. While reinforcement learning from human feedback (RLHF) has become the predominant mechanism for alignment in non-embodied domains like large language models, it has not seen the same success in aligning visuomotor policies due to the prohibitive amount of human feedback required to learn visual reward functions. To address this limitation, we propose Representation-Aligned Preference-based Learning (RAPL), an observation-only method for learning visual rewards from significantly less human preference feedback. Unlike traditional RLHF, RAPL focuses human feedback on fine-tuning pre-trained vision encoders to align with the end-user's visual representation and then constructs a dense visual reward via feature matching in this aligned representation space. We first validate RAPL through simulation experiments in the X-Magical benchmark and Franka Panda robotic manipulation, demonstrating that it can learn rewards aligned with human preferences, more efficiently uses preference data, and generalizes across robot embodiments. Finally, our hardware experiments align pre-trained Diffusion Policies for three object manipulation tasks. We find that RAPL can fine-tune these policies with 5x less real human preference data, taking the first step towards minimizing human feedback while maximizing visuomotor robot policy alignment.

[Arxiv](https://arxiv.org/abs/2412.04835)