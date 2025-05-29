# 利用带有冷启动机制的强化学习提升多模态推理能力

发布时间：2025年05月28日

`LLM应用` `多模态推理`

> Advancing Multimodal Reasoning via Reinforcement Learning with Cold Start

# 摘要

> 大型语言模型 (LLMs) 在链式推理能力上的突破性进展令人瞩目，而强化学习 (RL) 在此过程中扮演了关键角色。尽管“顿悟时刻”模式——即模型通过反思自我修正——通常被认为是 RL 的涌现特性，但我们发现这些模式在强化学习训练之前就已经存在于多模态大型语言模型 (MLLMs) 中，但它们并不一定与推理性能的提升相关。基于这一发现，我们提出了一种通过两阶段方法提升多模态推理能力的全面研究：(1) 以结构化的链式推理模式进行监督微调 (SFT) 作为冷启动，随后 (2) 通过 GRPO 进行强化学习以进一步完善这些能力。我们的实验表明，这种结合方法在多模态推理基准测试中始终优于仅使用 SFT 和仅使用 RL 的方法。最终模型在开源 MLLMs 的 3B 和 7B 规模下均达到了目前最优的性能，其中我们的 7B 模型在多个基准测试中（例如 MathVista 从 66.3% 提升至 73.4%，We-Math 从 62.9% 提升至 70.4%）显示出显著改进，而我们的 3B 模型也实现了与多个 7B 模型相当的表现。总体而言，这项研究为构建先进的多模态推理模型提供了实用的指导。我们的代码可在 https://github.com/waltonfuture/RL-with-Cold-Start 获取。

> Recent advancements in large language models (LLMs) have demonstrated impressive chain-of-thought reasoning capabilities, with reinforcement learning (RL) playing a crucial role in this progress. While "aha moment" patterns--where models exhibit self-correction through reflection--are often attributed to emergent properties from RL, we first demonstrate that these patterns exist in multimodal LLMs (MLLMs) prior to RL training but may not necessarily correlate with improved reasoning performance. Building on these insights, we present a comprehensive study on enhancing multimodal reasoning through a two-stage approach: (1) supervised fine-tuning (SFT) as a cold start with structured chain-of-thought reasoning patterns, followed by (2) reinforcement learning via GRPO to further refine these capabilities. Our extensive experiments show that this combined approach consistently outperforms both SFT-only and RL-only methods across challenging multimodal reasoning benchmarks. The resulting models achieve state-of-the-art performance among open-source MLLMs at both 3B and 7B scales, with our 7B model showing substantial improvements over base models (e.g., 66.3 %$\rightarrow$73.4 % on MathVista, 62.9 %$\rightarrow$70.4 % on We-Math) and our 3B model achieving performance competitive with several 7B models. Overall, this work provides practical guidance for building advanced multimodal reasoning models. Our code is available at https://github.com/waltonfuture/RL-with-Cold-Start.

[Arxiv](https://arxiv.org/abs/2505.22334)