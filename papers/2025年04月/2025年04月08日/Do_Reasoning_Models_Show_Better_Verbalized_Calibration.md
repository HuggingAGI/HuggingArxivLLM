# 推理模型在语言表达上的校准能力是否更出色？

发布时间：2025年04月08日

`LLM理论` `推理模型` `模型训练`

> Do Reasoning Models Show Better Verbalized Calibration?

# 摘要

> 大型推理模型 (LRMs) 近期在复杂推理任务中表现出了令人瞩目的能力，其通过增加推理时的计算量和展现出类似人类深思熟虑的行为。尽管取得了这些进展，但目前仍不清楚 LRMs 在 calibration（特别是其表达的信心方面）是否优于经过指令微调的模型。本文中，我们研究了通过监督微调蒸馏（简称 SFT 推理模型）和基于结果的推理强化学习（简称 RL 推理模型）训练的 LRMs 在不同领域的 calibration 属性。我们的研究发现，与指令微调模型相比，LRMs 在复杂推理任务中无论是在准确性还是信心 calibration 方面都表现出了显著的优势。然而，在事实性领域，我们发现了一些令人惊讶的趋势。在事实性任务中，尽管 Deepseek-R1 展现出了强大的 calibration 行为，但较小的 QwQ-32B 模型并未显示出比指令模型更好的表现；此外，SFT 推理模型的 calibration 情况（过度自信）相比指令模型更为糟糕。我们的研究结果表明，以推理为导向的强化学习训练可能在提升 LLM 生成可信且具有自我意识输出的能力方面发挥着关键作用。

> Large reasoning models (LRMs) have recently shown impressive capabilities in complex reasoning by leveraging increased test-time computation and exhibiting behaviors akin to human-like deliberation. Despite these advances, it remains an open question whether LRMs are better calibrated - particularly in their verbalized confidence - compared to instruction-tuned counterparts. In this paper, we investigate the calibration properties of LRMs trained via supervised fine-tuning distillation on long reasoning traces (henceforth SFT reasoning models) and outcome-based reinforcement learning for reasoning (henceforth RL reasoning models) across diverse domains. Our findings reveal that LRMs significantly outperform instruction-tuned models on complex reasoning tasks in both accuracy and confidence calibration. In contrast, we find surprising trends in the domain of factuality in particular. On factuality tasks, while Deepseek-R1 shows strong calibration behavior, smaller QwQ-32B shows no improvement over instruct models; moreover, SFT reasoning models display worse calibration (greater overconfidence) compared to instruct models. Our results provide evidence for a potentially critical role of reasoning-oriented RL training in improving LLMs' capacity for generating trustworthy, self-aware outputs.

[Arxiv](https://arxiv.org/abs/2504.06564)