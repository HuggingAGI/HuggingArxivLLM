# 多模态大语言模型中的推测解码新定义

发布时间：2025年05月20日

`LLM应用` `人工智能` `机器学习`

> Speculative Decoding Reimagined for Multimodal Large Language Models

# 摘要

> 本文提出了一种名为多模态投机解码（MSD）的方法，旨在加速多模态大型语言模型（MLLMs）的推理过程。投机解码已被证明可以在不降低准确性的情况下加速大型语言模型（LLMs）的推理。然而，目前针对MLLMs的投机解码方法未能达到与LLMs相同的加速效果。为了解决这一问题，我们重新设计了专门适用于MLLMs的投机解码方法。通过对MLLMs特性的分析，我们得出了MSD的两大核心设计原则：（1）文本和视觉令牌具有本质上的不同特性，需要在草稿阶段分别处理；（2）草稿模型的语言建模能力和视觉感知能力都至关重要。针对第一条原则，MSD在草稿模型中分离了文本和视觉令牌，使每种令牌都能根据其自身特性进行处理。针对第二条原则，MSD采用了两阶段训练策略：第一阶段，草稿模型通过仅基于文本的指令微调数据集进行训练，以提升其语言建模能力；第二阶段，MSD逐步引入多模态数据，以增强草稿模型的视觉感知能力。实验结果表明，MSD在多模态基准测试中将推理速度提升了最高【数学公式】倍（针对LLaVA-1.5-7B）和最高【数学公式】倍（针对LLaVA-1.5-13B），充分证明了其有效性。我们的代码已开源，地址为https://github.com/Lyn-Lucy/MSD。


> This paper introduces Multimodal Speculative Decoding (MSD) to accelerate Multimodal Large Language Models (MLLMs) inference. Speculative decoding has been shown to accelerate Large Language Models (LLMs) without sacrificing accuracy. However, current speculative decoding methods for MLLMs fail to achieve the same speedup as they do for LLMs. To address this, we reimagine speculative decoding specifically for MLLMs. Our analysis of MLLM characteristics reveals two key design principles for MSD: (1) Text and visual tokens have fundamentally different characteristics and need to be processed separately during drafting. (2) Both language modeling ability and visual perception capability are crucial for the draft model. For the first principle, MSD decouples text and visual tokens in the draft model, allowing each to be handled based on its own characteristics. For the second principle, MSD uses a two-stage training strategy: In stage one, the draft model is trained on text-only instruction-tuning datasets to improve its language modeling ability. In stage two, MSD gradually introduces multimodal data to enhance the visual perception capability of the draft model. Experiments show that MSD boosts inference speed by up to $2.29\times$ for LLaVA-1.5-7B and up to $2.46\times$ for LLaVA-1.5-13B on multimodal benchmarks, demonstrating its effectiveness. Our code is available at https://github.com/Lyn-Lucy/MSD.

[Arxiv](https://arxiv.org/abs/2505.14260)