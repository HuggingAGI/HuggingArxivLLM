# # 回溯：多模态大语言模型推理中的隐式视觉重聚焦

发布时间：2025年07月02日

`LLM应用` `多模态推理` `视觉信息整合`

> Look-Back: Implicit Visual Re-focusing in MLLM Reasoning

# 摘要

> 多模态大语言模型 (MLLMs) 在多模态推理领域取得了显著进展。然而，这些模型在推理后期往往过度依赖文本信息，忽视了对视觉输入的关键整合。针对这一问题，现有方法通常通过显式注入视觉信息来引导推理过程。在本研究中，通过对 MLLM 注意力模式的深入分析，我们发现了一个有趣的现象：在适当引导下，MLLMs 可以在推理后期自发重新将注意力集中在视觉输入上，即使没有显式注入视觉信息。这一现象表明，MLLMs 本质上具备进行视觉融合推理的能力。基于这一发现，我们提出了 Look-Back 方法，这是一种隐式引导策略，旨在让 MLLMs 在推理过程中自主地“回顾”视觉信息。Look-Back 赋予模型自主决定何时、何地以及如何重新关注视觉输入的能力，无需显式模型结构约束或额外输入。通过在多个多模态基准上的广泛实证评估，我们证明 Look-Back 显著提升了模型的推理和感知能力。

> Multimodal Large Language Models (MLLMs) have achieved remarkable progress in multimodal reasoning. However, they often excessively rely on textual information during the later stages of inference, neglecting the crucial integration of visual input. Current methods typically address this by explicitly injecting visual information to guide the reasoning process. In this work, through an analysis of MLLM attention patterns, we made an intriguing observation: with appropriate guidance, MLLMs can spontaneously re-focus their attention on visual inputs during the later stages of reasoning, even without explicit visual information injection. This spontaneous shift in focus suggests that MLLMs are intrinsically capable of performing visual fusion reasoning. Building on this insight, we introduce Look-Back, an implicit approach designed to guide MLLMs to ``look back" at visual information in a self-directed manner during reasoning. Look-Back empowers the model to autonomously determine when, where, and how to re-focus on visual inputs, eliminating the need for explicit model-structure constraints or additional input. We demonstrate that Look-Back significantly enhances the model's reasoning and perception capabilities, as evidenced by extensive empirical evaluations on multiple multimodal benchmarks.

[Arxiv](https://arxiv.org/abs/2507.03019)