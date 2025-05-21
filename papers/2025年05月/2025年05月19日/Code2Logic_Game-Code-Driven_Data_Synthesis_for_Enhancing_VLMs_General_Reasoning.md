# Code2Logic：基于游戏代码的数据合成，助力提升视觉语言模型的通用推理能力。

发布时间：2025年05月19日

`LLM应用

理由：这篇论文探讨了如何利用大型语言模型（LLMs）来生成和合成视觉语言推理数据，从而提升视觉语言模型（VLM）的推理能力。它具体提出了Code2Logic方法，并开发了GameQA数据集，展示了LLMs在实际应用中的潜力和效果，属于LLM应用的范畴。` `视觉语言模型`

> Code2Logic: Game-Code-Driven Data Synthesis for Enhancing VLMs General Reasoning

# 摘要

> 视觉语言链式思维（CoT）的数据资源相较于纯文本资源较为匮乏，这限制了视觉语言模型（VLM）推理能力的提升。高质量的视觉语言推理数据标注成本高昂且耗时耗力。为了解决这一问题，我们发现了一种极具潜力的资源——游戏代码，它天然包含逻辑结构和状态转换过程。因此，我们提出了Code2Logic，这是一种基于游戏代码驱动的多模态推理数据合成新方法。我们的方法借助大型语言模型（LLMs）对游戏代码进行适配，通过代码执行实现推理过程和结果的自动获取。借助Code2Logic方法，我们开发了GameQA数据集，用于训练和评估VLM。GameQA数据集制作成本低廉且可扩展，对当前最先进的模型具有挑战性，并包含30款游戏和158项任务，具有丰富的多样性。令人惊讶的是，尽管VLMs仅在游戏数据上进行训练，却展现了跨领域泛化能力。具体而言，Qwen2.5-VL-7B在7个多样化的视觉语言基准测试中性能提升了2.33%。我们的代码和数据集可在https://github.com/tongjingqi/Code2Logic获取。

> Visual-language Chain-of-Thought (CoT) data resources are relatively scarce compared to text-only counterparts, limiting the improvement of reasoning capabilities in Vision Language Models (VLMs). However, high-quality vision-language reasoning data is expensive and labor-intensive to annotate. To address this issue, we leverage a promising resource: game code, which naturally contains logical structures and state transition processes. Therefore, we propose Code2Logic, a novel game-code-driven approach for multimodal reasoning data synthesis. Our approach leverages Large Language Models (LLMs) to adapt game code, enabling automatic acquisition of reasoning processes and results through code execution. Using the Code2Logic approach, we developed the GameQA dataset to train and evaluate VLMs. GameQA is cost-effective and scalable to produce, challenging for state-of-the-art models, and diverse with 30 games and 158 tasks. Surprisingly, despite training solely on game data, VLMs demonstrated out of domain generalization, specifically Qwen2.5-VL-7B improving performance by 2.33\% across 7 diverse vision-language benchmarks. Our code and dataset are available at https://github.com/tongjingqi/Code2Logic.

[Arxiv](https://arxiv.org/abs/2505.13886)