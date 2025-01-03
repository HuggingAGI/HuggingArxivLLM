# AVHBench: 音频-视觉大语言模型的跨模态幻觉评测基准

发布时间：2024年10月23日

`LLM应用

**理由**：这篇论文主要讨论了将大型语言模型（LLMs）扩展到多模态（音频-视觉）领域的应用，并提出了一个新的基准测试（AVHBench）来评估这些模型的性能。论文的核心在于如何应用LLMs来处理和理解多模态数据，并解决其中的挑战（如幻觉现象）。因此，它属于LLM应用类别。` `人工智能` `多模态学习`

> AVHBench: A Cross-Modal Hallucination Benchmark for Audio-Visual Large Language Models

# 摘要

> 随着大型语言模型（LLMs）的成功，将其应用扩展到新的模态标志着多模态理解领域的一次重大变革。人类的感知本质上是多模态的，不仅依赖文本，还需借助听觉和视觉线索来全面理解世界。基于这一认识，音频-视觉LLMs应运而生。尽管进展喜人，但缺乏专门的基准测试给模型的理解和评估带来了挑战。本文展示了音频-视觉LLMs在辨别音频和视觉信号之间微妙关系时的困难，导致幻觉现象，这凸显了建立可靠基准测试的必要性。为此，我们推出了AVHBench，这是首个专门用于评估音频-视觉LLMs感知和理解能力的综合基准测试。该基准测试包括评估幻觉、跨模态匹配和推理能力的测试。结果显示，现有的大多数音频-视觉LLMs由于感知复杂多模态信号及其关系的能力有限，难以应对由模态间交叉互动引发的幻觉。此外，我们通过实验证明，使用AVHBench进行简单训练即可显著提升音频-视觉LLMs对幻觉的鲁棒性。

> Following the success of Large Language Models (LLMs), expanding their boundaries to new modalities represents a significant paradigm shift in multimodal understanding. Human perception is inherently multimodal, relying not only on text but also on auditory and visual cues for a complete understanding of the world. In recognition of this fact, audio-visual LLMs have recently emerged. Despite promising developments, the lack of dedicated benchmarks poses challenges for understanding and evaluating models. In this work, we show that audio-visual LLMs struggle to discern subtle relationships between audio and visual signals, leading to hallucinations, underscoring the need for reliable benchmarks. To address this, we introduce AVHBench, the first comprehensive benchmark specifically designed to evaluate the perception and comprehension capabilities of audio-visual LLMs. Our benchmark includes tests for assessing hallucinations, as well as the cross-modal matching and reasoning abilities of these models. Our results reveal that most existing audio-visual LLMs struggle with hallucinations caused by cross-interactions between modalities, due to their limited capacity to perceive complex multimodal signals and their relationships. Additionally, we demonstrate that simple training with our AVHBench improves robustness of audio-visual LLMs against hallucinations.

[Arxiv](https://arxiv.org/abs/2410.18325)