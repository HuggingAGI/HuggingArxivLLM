# 从像素与模式中发现世界：像人类一样感知

发布时间：2025年07月21日

`LLM应用` `人工智能` `计算机视觉`

> Pixels, Patterns, but No Poetry: To See The World like Humans

# 摘要

> 在多模态大型语言模型（MLLMs）中实现类人的感知与推理能力仍是人工智能领域的核心挑战。尽管近期研究主要集中在提升多模态大模型的推理能力，但一个根本性问题仍然存在：多模态大型语言模型是否能像人类一样感知世界？本文将研究重点从推理转向感知。我们没有专门构建用于推理的基准测试，而是引入了图灵视觉测试（TET），这是一个具有挑战性的感知导向基准测试，包含四个诊断任务，用于评估多模态大模型在处理人类直观处理的合成图像时的性能。我们的研究发现，当前最先进多模态大模型在我们的感知任务上表现灾难性失败，这些任务对于人类来说 trivial。无论是上下文学习还是对语言主干进行训练（这两种方法在之前的基准测试中有效），都无法提升我们在任务上的性能，而对视觉塔进行微调则能实现快速适应，这表明我们的基准测试对视觉塔的泛化能力提出了挑战，而不是对语言主干的知识和推理能力——这是当前多模态大模型与人类感知之间的重要差距。本文发布了图灵视觉测试（TET）任务的代表性子集，并将在未来工作中引入更多样化的任务和方法，以增强视觉泛化能力。

> Achieving human-like perception and reasoning in Multimodal Large Language Models (MLLMs) remains a central challenge in artificial intelligence. While recent research has primarily focused on enhancing reasoning capabilities in MLLMs, a fundamental question persists: Can Multimodal Large Language Models truly perceive the world as humans do? This paper shifts focus from reasoning to perception. Rather than constructing benchmarks specifically for reasoning, we introduce the Turing Eye Test (TET), a challenging perception-oriented benchmark comprising four diagnostic tasks that evaluate MLLMs' performance on synthetic images that humans process intuitively. Our findings reveal that state-of-the-art MLLMs exhibit catastrophic failures on our perceptual tasks trivial for humans. Both in-context learning and training on language backbone-effective for previous benchmarks-fail to improve performance on our tasks, while fine-tuning the vision tower enables rapid adaptation, suggesting that our benchmark poses challenges for vision tower generalization rather than for the knowledge and reasoning capabilities of the language backbone-a key gap between current MLLMs and human perception. We release a representative subset of TET tasks in this version, and will introduce more diverse tasks and methods to enhance visual generalization in future work.

[Arxiv](https://arxiv.org/abs/2507.16863)