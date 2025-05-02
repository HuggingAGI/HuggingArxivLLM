# 触发大型语言模型的幻觉：一项关于提示引发幻觉的定量研究

发布时间：2025年05月01日

`LLM理论`

> Triggering Hallucinations in LLMs: A Quantitative Study of Prompt-Induced Hallucination in Large Language Models

# 摘要

> 大型语言模型（LLMs）中的幻觉现象在医疗、法律等领域带来了严峻挑战，这些领域对事实可靠性要求极高。尽管在对齐和指令微调方面取得了进展，LLMs仍可能生成流畅却失实的内容。理解导致这些幻觉的认知动态仍是未解之谜。

本研究提出了一种基于提示的框架，用于系统性地触发和量化幻觉。我们设计了幻觉诱导提示（HIP），它以误导性方式融合语义相距甚远的概念（如元素周期表与塔罗占卜），以及幻觉量化提示（HQP），用于评估输出的合理性、信心和连贯性。

实验结果表明，与无融合对照组相比，HIPs在多个LLMs上始终引发连贯性更低且幻觉更严重的回应。不同模型间效果差异显著，推理导向型LLMs与通用型LLMs表现各异。

我们的框架为研究幻觉漏洞提供了可重复的实验平台，为开发更安全、更具自省能力的LLMs奠定了基础，这些模型能够检测并自我调节概念不稳定性的发生。

> Hallucinations in large language models (LLMs) present a growing challenge across real-world applications, from healthcare to law, where factual reliability is essential. Despite advances in alignment and instruction tuning, LLMs can still generate outputs that are fluent yet fundamentally untrue. Understanding the cognitive dynamics that underlie these hallucinations remains an open problem. In this study, we propose a prompt-based framework to systematically trigger and quantify hallucination: a Hallucination-Inducing Prompt (HIP), which synthetically fuses semantically distant concepts (e.g., periodic table of elements and tarot divination) in a misleading way, and a Hallucination Quantifying Prompt (HQP), which scores the plausibility, confidence, and coherence of the output. Controlled experiments across multiple LLMs revealed that HIPs consistently produced less coherent and more hallucinated responses than their null-fusion controls. These effects varied across models, with reasoning-oriented LLMs showing distinct profiles from general-purpose ones. Our framework provides a reproducible testbed for studying hallucination vulnerability, and opens the door to developing safer, more introspective LLMs that can detect and self-regulate the onset of conceptual instability.

[Arxiv](https://arxiv.org/abs/2505.00557)