# ColorBench: 视觉语言模型能否看懂并理解这个多彩世界？一项全面评估视觉语言模型在颜色感知、推理与鲁棒性方面的表现的基准测试

发布时间：2025年04月10日

`LLM应用` `计算机视觉` `颜色感知`

> ColorBench: Can VLMs See and Understand the Colorful World? A Comprehensive Benchmark for Color Perception, Reasoning, and Robustness

# 摘要

> 颜色在人类感知中发挥着重要作用，通常为视觉推理提供关键线索。然而，视觉语言模型（VLMs）是否以及如何像人类一样感知、理解和利用颜色，仍是一个未解之谜。本文介绍了ColorBench，这是一个精心设计的创新基准，旨在全面评估VLMs在颜色感知、推理和鲁棒性方面的表现。通过构建多样化的实际应用场景测试集，ColorBench深入考察了VLMs在颜色识别、基于颜色线索的语义推断以及面对复杂颜色变换时的稳定性。

通过对涵盖不同语言模型和视觉编码器的32个VLMs进行系统性评估，我们发现了几个重要现象：(i) 在ColorBench测试中，模型规模越大性能越优的“规模定律”依然适用，但语言模型的作用较视觉编码器更为关键。(ii) 不过，各模型间性能差距较小，说明现有VLMs对颜色理解能力的重视程度明显不足。(iii) CoT推理显著提升了颜色理解的准确性和鲁棒性，即使在视觉主导的任务中也是如此。(iv) VLMs确实在ColorBench中有效利用了颜色线索，但这些线索也可能在某些任务中对模型产生误导。

这些发现不仅揭示了当前VLMs在颜色理解方面的局限性，也凸显了提升其颜色理解能力的重要性和紧迫性。我们的ColorBench基准测试为推动多模态AI在人级别颜色理解研究提供了重要工具和研究方向。


> Color plays an important role in human perception and usually provides critical clues in visual reasoning. However, it is unclear whether and how vision-language models (VLMs) can perceive, understand, and leverage color as humans. This paper introduces ColorBench, an innovative benchmark meticulously crafted to assess the capabilities of VLMs in color understanding, including color perception, reasoning, and robustness. By curating a suite of diverse test scenarios, with grounding in real applications, ColorBench evaluates how these models perceive colors, infer meanings from color-based cues, and maintain consistent performance under varying color transformations. Through an extensive evaluation of 32 VLMs with varying language models and vision encoders, our paper reveals some undiscovered findings: (i) The scaling law (larger models are better) still holds on ColorBench, while the language model plays a more important role than the vision encoder. (ii) However, the performance gaps across models are relatively small, indicating that color understanding has been largely neglected by existing VLMs. (iii) CoT reasoning improves color understanding accuracies and robustness, though they are vision-centric tasks. (iv) Color clues are indeed leveraged by VLMs on ColorBench but they can also mislead models in some tasks. These findings highlight the critical limitations of current VLMs and underscore the need to enhance color comprehension. Our ColorBenchcan serve as a foundational tool for advancing the study of human-level color understanding of multimodal AI.

[Arxiv](https://arxiv.org/abs/2504.10514)