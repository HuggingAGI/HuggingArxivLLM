# Think-RM：赋能生成式奖励模型的长时推理能力

发布时间：2025年05月22日

`LLM应用` `机器学习`

> Think-RM: Enabling Long-Horizon Reasoning in Generative Reward Models

# 摘要

> 基于人类反馈的强化学习 (RLHF) 已经成为一种强大的后训练范式，用于使大型语言模型与人类偏好对齐。然而，RLHF 中构建准确的奖励信号仍面临挑战。传统的布拉德利-特里奖励模型 (BT RMs) 易受数据规模和覆盖范围影响，且容易遭受奖励欺骗。为此，生成式奖励模型 (GenRMs) 提供了一种更强大的替代方案，通过生成思维链 (CoT) 推理并给出最终奖励。然而，现有的 GenRMs 依赖于浅层、垂直扩展的推理，限制了它们处理细微或复杂任务的能力。此外，它们的成对偏好输出与标准 RLHF 算法不兼容。

为了解决这些问题，我们提出了 Think-RM，一个通过建模内部思考过程实现长期推理的训练框架。与生成结构化、外部提供的推理不同，Think-RM 生成灵活的、自我引导的推理轨迹，支持自我反思、假设推理和发散推理等高级能力。为了激发这些推理能力，我们首先通过监督微调 (SFT) 对长 CoT 数据进行预热，然后通过基于规则的强化学习 (RL) 进一步提升模型的长期推理能力。此外，我们提出了一种新的成对 RLHF 管道，直接利用成对偏好奖励优化策略，无需进行点式奖励转换，从而更有效地利用 Think-RM 的输出。

实验结果表明，Think-RM 在 RM-Bench 上实现了最先进的性能，比 BT RM 和垂直扩展的 GenRM 高出 8%。当与我们的成对 RLHF 管道结合时，它在最终策略性能上显著优于传统方法。

> Reinforcement learning from human feedback (RLHF) has become a powerful post-training paradigm for aligning large language models with human preferences. A core challenge in RLHF is constructing accurate reward signals, where the conventional Bradley-Terry reward models (BT RMs) often suffer from sensitivity to data size and coverage, as well as vulnerability to reward hacking. Generative reward models (GenRMs) offer a more robust alternative by generating chain-of-thought (CoT) rationales followed by a final reward. However, existing GenRMs rely on shallow, vertically scaled reasoning, limiting their capacity to handle nuanced or complex (e.g., reasoning-intensive) tasks. Moreover, their pairwise preference outputs are incompatible with standard RLHF algorithms that require pointwise reward signals. In this work, we introduce Think-RM, a training framework that enables long-horizon reasoning in GenRMs by modeling an internal thinking process. Rather than producing structured, externally provided rationales, Think-RM generates flexible, self-guided reasoning traces that support advanced capabilities such as self-reflection, hypothetical reasoning, and divergent reasoning. To elicit these reasoning abilities, we first warm-up the models by supervised fine-tuning (SFT) over long CoT data. We then further improve the model's long-horizon abilities by rule-based reinforcement learning (RL). In addition, we propose a novel pairwise RLHF pipeline that directly optimizes policies using pairwise preference rewards, eliminating the need for pointwise reward conversion and enabling more effective use of Think-RM outputs. Experiments show that Think-RM achieves state-of-the-art results on RM-Bench, outperforming both BT RM and vertically scaled GenRM by 8%. When combined with our pairwise RLHF pipeline, it demonstrates superior end-policy performance compared to traditional approaches.

[Arxiv](https://arxiv.org/abs/2505.16265)