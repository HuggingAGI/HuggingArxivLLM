# 推进多模态推理：从优化冷启动到分阶段强化学习

发布时间：2025年06月04日

`LLM应用` `数学推理`

> Advancing Multimodal Reasoning: From Optimized Cold Start to Staged Reinforcement Learning

# 摘要

> 受 Deepseek-R1 在复杂文本任务中卓越推理能力的启发，许多研究尝试通过直接应用强化学习 (RL) 来激发多模态大语言模型 (MLLM) 的类似推理能力。然而，这些方法仍难以激发复杂的推理能力。本文并未孤立研究多模态 RL，而是深入探索了当前训练流程，发现了三个关键现象：首先，有效的冷启动初始化对提升 MLLM 推理能力至关重要。令人惊讶的是，仅使用精心挑选的文本数据进行初始化，便能在多模态 RL 之前超越许多近期多模态推理模型的性能。其次，标准的 GRPO 在多模态 RL 中应用时会遭遇梯度停滞，导致训练不稳定且性能下降。最后，多模态 RL 阶段后进行的文本-only RL 训练，能够进一步提升多模态推理能力。这种分阶段训练方法巧妙平衡了感知基础与认知推理的发展。通过结合上述见解并解决多模态 RL 的问题，我们推出了 ReVisual-R1。在 MathVerse、MathVision、WeMath、LogicVista、DynaMath 以及具有挑战性的 AIME2024 和 AIME2025 等基准测试中，ReVisual-R1 达到了开源 7B MLLMs 的新 state-of-the-art 水平。

> Inspired by the remarkable reasoning capabilities of Deepseek-R1 in complex textual tasks, many works attempt to incentivize similar capabilities in Multimodal Large Language Models (MLLMs) by directly applying reinforcement learning (RL). However, they still struggle to activate complex reasoning. In this paper, rather than examining multimodal RL in isolation, we delve into current training pipelines and identify three crucial phenomena: 1) Effective cold start initialization is critical for enhancing MLLM reasoning. Intriguingly, we find that initializing with carefully selected text data alone can lead to performance surpassing many recent multimodal reasoning models, even before multimodal RL. 2) Standard GRPO applied to multimodal RL suffers from gradient stagnation, which degrades training stability and performance. 3) Subsequent text-only RL training, following the multimodal RL phase, further enhances multimodal reasoning. This staged training approach effectively balances perceptual grounding and cognitive reasoning development. By incorporating the above insights and addressing multimodal RL issues, we introduce ReVisual-R1, achieving a new state-of-the-art among open-source 7B MLLMs on challenging benchmarks including MathVerse, MathVision, WeMath, LogicVista, DynaMath, and challenging AIME2024 and AIME2025.

[Arxiv](https://arxiv.org/abs/2506.04207)