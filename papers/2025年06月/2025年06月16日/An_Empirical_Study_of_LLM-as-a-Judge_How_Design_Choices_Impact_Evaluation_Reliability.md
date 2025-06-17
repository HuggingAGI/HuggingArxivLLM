# # LLM作为裁判的实证研究：设计决策如何影响评估的可靠性

发布时间：2025年06月16日

`LLM理论` `人工智能`

> An Empirical Study of LLM-as-a-Judge: How Design Choices Impact Evaluation Reliability

# 摘要

> 大型语言模型（LLMs）的持续进步使可靠评估方法的需求日益迫切，尤其是在开放性、遵循指令的任务中。LLM作为裁判，能够自动评估模型，但其可靠性仍存疑。本研究聚焦于影响其可信度的关键因素，特别是与人工判断的对齐度和评估一致性。通过BIGGENBench和EvalBiasBench，我们深入研究了评估设计、解码策略以及链式推理（CoT）在评估中的作用。研究结果表明，评估标准是可靠性的重要决定因素，非确定性采样相较于确定性评估更能与人类偏好对齐，而链式推理在明确评估标准下仅能带来微小提升。

> As large language models (LLMs) continue to advance, reliable evaluation methods are essential particularly for open-ended, instruction-following tasks. LLM-as-a-Judge enables automatic evaluation using LLMs as evaluators, but its reliability remains uncertain. In this work, we analyze key factors affecting its trustworthiness, focusing on alignment with human judgments and evaluation consistency. Using BIGGENBench and EvalBiasBench, we study the effects of evaluation design, decoding strategies, and Chain-of-Tought (CoT) reasoning in evaluation. Our results show that evaluation criteria are critical for reliability, non-deterministic sampling improves alignment with human preferences over deterministic evaluation, and CoT reasoning offers minimal gains when clear evaluation criteria are present.

[Arxiv](https://arxiv.org/abs/2506.13639)