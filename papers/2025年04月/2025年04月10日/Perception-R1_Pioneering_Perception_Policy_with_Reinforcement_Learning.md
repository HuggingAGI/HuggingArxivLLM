# Perception-R1：引领强化学习驱动的感知策略新方向

发布时间：2025年04月10日

`LLM应用` `视觉感知` `计算机视觉`

> Perception-R1: Pioneering Perception Policy with Reinforcement Learning

# 摘要

> 受 DeepSeek-R1 成功的启发，我们探索了基于规则的强化学习 (RL) 在 MLLM 后训练中对感知策略学习的潜力。尽管有潜力，但我们的初步实验发现，通过强化学习融入思考过程，并不能在所有视觉感知任务中一致地带来性能提升。这促使我们深入研究强化学习在视觉感知背景下的核心作用。在本研究中，我们回归基础，探索强化学习对不同感知任务的影响。我们发现，感知复杂性是决定强化学习有效性的重要因素。同时，我们观察到奖励设计在进一步逼近模型感知上限方面起着关键作用。为了利用这些发现，我们提出了 Perception-R1，这是一个在 MLLM 后训练中使用 GRPO 的可扩展强化学习框架。使用标准的 Qwen2.5-VL-3B-Instruct，Perception-R1 在 RefCOCO+ 上提升了 +4.2%，在 PixMo-Count 上提升了 +17.9%，在 PageOCR 上提升了 +4.2%，并且在 COCO2017 验证集上首次达到了 31.9% 的 AP，为感知策略学习奠定了强大的基线。

> Inspired by the success of DeepSeek-R1, we explore the potential of rule-based reinforcement learning (RL) in MLLM post-training for perception policy learning. While promising, our initial experiments reveal that incorporating a thinking process through RL does not consistently lead to performance gains across all visual perception tasks. This leads us to delve into the essential role of RL in the context of visual perception. In this work, we return to the fundamentals and explore the effects of RL on different perception tasks. We observe that the perceptual complexity is a major factor in determining the effectiveness of RL. We also observe that reward design plays a crucial role in further approching the upper limit of model perception. To leverage these findings, we propose Perception-R1, a scalable RL framework using GRPO during MLLM post-training. With a standard Qwen2.5-VL-3B-Instruct, Perception-R1 achieves +4.2% on RefCOCO+, +17.9% on PixMo-Count, +4.2% on PageOCR, and notably, 31.9% AP on COCO2017 val for the first time, establishing a strong baseline for perception policy learning.

[Arxiv](https://arxiv.org/abs/2504.07954)