# MQuant: 全静态量化释放多模态大语言模型的推理潜能

发布时间：2025年02月01日

`LLM应用

理由：这篇论文主要讨论的是多模态大型语言模型（MLLMs）的量化技术，旨在解决其在实际应用中的计算和延迟问题。虽然涉及到模型的理论改进（如量化方法），但其核心目标是优化MLLMs在实际应用中的性能（如推理延迟和准确性），因此更适合归类为“LLM应用”。` `人工智能` `模型优化`

> MQuant: Unleashing the Inference Potential of Multimodal Large Language Models via Full Static Quantization

# 摘要

> # 摘要
多模态大型语言模型（MLLMs）因其强大的多模态理解能力备受瞩目。然而，庞大的参数规模和计算需求严重限制了其实际应用。尽管量化是缩小模型规模和降低推理延迟的有效手段，但其在MLLMs中的应用仍待深入探索。本文提出MQuant，一种专为MLLMs设计的后训练量化（PTQ）框架，旨在解决其独特挑战。传统量化方法在处理MLLMs时面临三大难题：（a）大量视觉标记导致的高延迟，（b）视觉与文本标记的分布差异，（c）Hadamard变换引入的极端异常值。为此，MQuant引入三大创新：模态特定静态量化（MSQ），为视觉和文本标记分配不同静态尺度；注意力不变灵活切换（AIFS），通过重排标记保留因果注意力，同时避免昂贵的逐标记尺度计算；旋转幅度抑制（RMS），缓解在线Hadamard旋转引发的权重异常值。在Qwen-VL、MiniCPM-V、CogVLM2等五种主流MLLMs上，MQuant在W4A8量化下实现了接近浮点精度的准确性（退化<1%），同时将推理延迟降低多达30%，显著超越现有PTQ基线。MQuant为资源受限设备上的高效准确MLLMs推理提供了有力支持。代码即将发布。

> Multimodal large language models (MLLMs) have garnered widespread attention due to their ability to understand multimodal input. However, their large parameter sizes and substantial computational demands severely hinder their practical deployment and application.While quantization is an effective way to reduce model size and inference latency, its application to MLLMs remains underexplored. In this paper, we propose MQuant, a post-training quantization (PTQ) framework designed to tackle the unique challenges of multimodal large language models (MLLMs). Conventional quantization often struggles with MLLMs because of (a) high inference latency from large visual token counts, (b) distributional disparities between visual and textual tokens, and (c) extreme outliers introduced by Hadamard-based transformations. To address these issues, MQuant introduces: Modality-Specific Static Quantization (MSQ), assigning distinct static scales for visual vs. textual tokens; Attention-Invariant Flexible Switching (AIFS), reordering tokens to preserve casual attention while eliminating expensive token-wise scale computations; Rotation Magnitude Suppression (RMS), mitigating weight outliers arising from online Hadamard rotations. On five mainstream MLLMs (including Qwen-VL, MiniCPM-V, CogVLM2), MQuant under W4A8 achieves near-floating-point accuracy (<1% degradation) while reducing inference latency by up to 30%, significantly outperforming existing PTQ baselines. Our MQuant effectively bridges the gap for efficient and accurate MLLMs inference in resource-constrained devices. Code will be released.

[Arxiv](https://arxiv.org/abs/2502.00425)