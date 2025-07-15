# ViDove：一个结合多模态上下文与增强记忆推理的翻译代理系统

发布时间：2025年07月09日

`LLM应用

理由：这篇论文主要讨论的是基于大语言模型（LLM）的翻译系统，特别是其在多模态输入方面的应用。ViDove系统结合了视觉和上下文信息，提升翻译质量，并且在实验中展示了显著的效果。这属于LLM的应用层面，因为它展示了如何将LLM用于实际任务（翻译）并进行了系统设计和优化。` `字幕生成`

> ViDove: A Translation Agent System with Multimodal Context and Memory-Augmented Reasoning

# 摘要

> 基于大语言模型的翻译系统不仅实现了高度拟人化的翻译效果，还能够更高效地处理长篇和复杂上下文。然而，这类系统通常仅支持纯文本输入。本文中，我们推出ViDove——一个专为多模态输入设计的翻译代理系统。受人类译者工作流程启发，ViDove巧妙结合视觉与上下文背景信息，显著提升翻译质量。系统还配备了增强型多模态记忆模块和领域知识强化的长短期记忆组件，使其在真实场景中表现得更加精准与灵活。实验结果表明，ViDove在字幕生成和通用翻译任务中均大幅超越现有最优基线，BLEU评分提升28%，SubER提升15%。此外，我们还发布了DoveBench——首个专注于长篇自动视频字幕与翻译的基准测试集，包含17小时高质量人工标注数据。ViDove的开源代码已上线：https://github.com/pigeonai-org/ViDove

> LLM-based translation agents have achieved highly human-like translation results and are capable of handling longer and more complex contexts with greater efficiency. However, they are typically limited to text-only inputs. In this paper, we introduce ViDove, a translation agent system designed for multimodal input. Inspired by the workflow of human translators, ViDove leverages visual and contextual background information to enhance the translation process. Additionally, we integrate a multimodal memory system and long-short term memory modules enriched with domain-specific knowledge, enabling the agent to perform more accurately and adaptively in real-world scenarios. As a result, ViDove achieves significantly higher translation quality in both subtitle generation and general translation tasks, with a 28% improvement in BLEU scores and a 15% improvement in SubER compared to previous state-of-the-art baselines. Moreover, we introduce DoveBench, a new benchmark for long-form automatic video subtitling and translation, featuring 17 hours of high-quality, human-annotated data. Our code is available here: https://github.com/pigeonai-org/ViDove

[Arxiv](https://arxiv.org/abs/2507.07306)