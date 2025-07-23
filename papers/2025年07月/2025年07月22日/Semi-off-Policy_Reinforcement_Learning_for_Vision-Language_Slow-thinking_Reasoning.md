# 半离策略强化学习在视觉-语言深度推理中的应用

发布时间：2025年07月22日

`LLM应用` `人工智能`

> Semi-off-Policy Reinforcement Learning for Vision-Language Slow-thinking Reasoning

# 摘要

> 提升视觉-语言大模型的视觉慢思考推理能力对于解决复杂的多模态任务至关重要。然而，由于 LVLMs 主要通过视觉-语言对齐进行训练，因此难以采用 on-policy 强化学习来培养慢思考能力，因为 rollout 空间受限于其初始能力。Off-policy RL 提供了一种超越当前策略的方法，但直接从外部模型中蒸馏轨迹可能导致视觉幻觉，因为不同模型之间的视觉感知能力存在不匹配。为了解决这些问题，本文提出了 SOPHIA，一种简单且可扩展的 Semi-Off-Policy RL 方法，用于视觉-语言慢思考推理。SOPHIA 通过结合可训练 LVLM 的 on-policy 视觉理解和语言模型的 off-policy 慢思考推理，构建了一个半离线策略行为模型，并根据推理结果分配奖励，并将视觉奖励向后传播。然后，LVLM 使用通过 off-policy RL 算法传播的奖励，从获得的推理轨迹中学习慢思考推理能力。与 InternVL2.5 和 38B 规模的 InternVL3.0 进行的大量实验表明了 SOPHIA 的有效性。值得注意的是，SOPHIA 将 InternVL3.0-38B 的平均性能提升了 8.50%，在开源 LVLM 的多个多模态推理基准测试中达到了最先进水平，甚至在具有挑战性的 MathVision 和 OlympiadBench 上超越了一些闭源模型（例如 GPT-4.1），分别达到了 49.08% 和 49.95% 的 pass@1 准确率。分析表明，SOPHIA 在监督微调和直接 on-policy RL 方法上表现更优，为进一步的 on-policy 训练提供了更好的策略初始化。

> Enhancing large vision-language models (LVLMs) with visual slow-thinking reasoning is crucial for solving complex multimodal tasks. However, since LVLMs are mainly trained with vision-language alignment, it is difficult to adopt on-policy reinforcement learning (RL) to develop the slow thinking ability because the rollout space is restricted by its initial abilities. Off-policy RL offers a way to go beyond the current policy, but directly distilling trajectories from external models may cause visual hallucinations due to mismatched visual perception abilities across models. To address these issues, this paper proposes SOPHIA, a simple and scalable Semi-Off-Policy RL for vision-language slow-tHInking reAsoning. SOPHIA builds a semi-off-policy behavior model by combining on-policy visual understanding from a trainable LVLM with off-policy slow-thinking reasoning from a language model, assigns outcome-based rewards to reasoning, and propagates visual rewards backward. Then LVLM learns slow-thinking reasoning ability from the obtained reasoning trajectories using propagated rewards via off-policy RL algorithms. Extensive experiments with InternVL2.5 and InternVL3.0 with 8B and 38B sizes show the effectiveness of SOPHIA. Notably, SOPHIA improves InternVL3.0-38B by 8.50% in average, reaching state-of-the-art performance among open-source LVLMs on multiple multimodal reasoning benchmarks, and even outperforms some closed-source models (e.g., GPT-4.1) on the challenging MathVision and OlympiadBench, achieving 49.08% and 49.95% pass@1 accuracy, respectively. Analysis shows SOPHIA outperforms supervised fine-tuning and direct on-policy RL methods, offering a better policy initialization for further on-policy training.

[Arxiv](https://arxiv.org/abs/2507.16814)