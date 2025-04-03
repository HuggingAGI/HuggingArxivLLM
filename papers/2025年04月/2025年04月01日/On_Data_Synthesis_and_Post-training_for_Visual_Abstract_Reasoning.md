# 数据合成与后训练在视觉抽象推理中的应用探索

发布时间：2025年04月01日

`LLM应用` `人工智能` `计算机视觉`

> On Data Synthesis and Post-training for Visual Abstract Reasoning

# 摘要

> 本文是一项开创性研究，旨在探索大型视觉-语言模型（VLMs）在抽象视觉推理（AVR）问题上的潜力。我们通过LLaVA-NeXT 7B模型实现了对特定AVR问题的感知与推理，并在性能上显著超越开源模型（如Qwen-2-VL-72B）和闭源的强大VLMs（如GPT-4o）。这一突破尤为可贵，因为几乎所有之前的VLMs在具有代表性的AVR基准测试中表现欠佳或接近随机。我们的成功归功于创新的数据合成和后训练流程，通过逐步降低任务难度，引导模型有效学习。值得注意的是，我们的7B模型在保持通用多模态理解能力的同时，在AVR任务上也表现出色。我们希望本文能为此领域早期研究贡献力量，并激发更多关于抽象视觉推理的深入研究。

> This paper is a pioneering work attempting to address abstract visual reasoning (AVR) problems for large vision-language models (VLMs). We make a common LLaVA-NeXT 7B model capable of perceiving and reasoning about specific AVR problems, surpassing both open-sourced (e.g., Qwen-2-VL-72B) and closed-sourced powerful VLMs (e.g., GPT-4o) with significant margin. This is a great breakthrough since almost all previous VLMs fail or show nearly random performance on representative AVR benchmarks. Our key success is our innovative data synthesis and post-training process, aiming to fully relieve the task difficulty and elicit the model to learn, step by step. Our 7B model is also shown to be behave well on AVR without sacrificing common multimodal comprehension abilities. We hope our paper could serve as an early effort in this area and would inspire further research in abstract visual reasoning.

[Arxiv](https://arxiv.org/abs/2504.01324)