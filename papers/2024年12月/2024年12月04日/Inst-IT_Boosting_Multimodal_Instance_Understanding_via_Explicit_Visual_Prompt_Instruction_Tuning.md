# Inst-IT：借由显式视觉提示指令调优来增强多模态实例理解

发布时间：2024年12月04日

`LLM应用` `图像视频` `多模态模型`

> Inst-IT: Boosting Multimodal Instance Understanding via Explicit Visual Prompt Instruction Tuning

# 摘要

> 大型多模态模型（LMMs）在指令调优的推动下取得了显著突破。不过，现有的模型虽能从整体上理解图像和视频，但在需要更精细理解和对齐的实例级理解方面仍面临挑战。实例级理解极为关键，因为它聚焦于我们最感兴趣的特定元素。令人欣喜的是，现有研究发现，当给予明确的视觉线索时，最先进的 LMMs 展现出强大的实例理解能力。受此激励，我们引入了由 GPT-4o 协助的自动标注管道，通过明确的视觉提示进行实例指导，从图像和视频中提取实例级信息。基于此管道，我们提出了 Inst-IT，这是一种通过明确的视觉提示指令调优来增强 LMMs 实例理解的方案。Inst-IT 涵盖了一个用于诊断多模态实例级理解的基准、一个大规模的指令调优数据集以及一个连续的指令调优训练范式，能够有效提升现有 LMMs 的时空实例理解能力。实验结果显示，在 Inst-IT 的助力下，我们的模型不仅在 Inst-IT 基准测试中表现出色，而且在各类通用图像和视频理解基准测试中也有显著提升。这表明我们的数据集不仅提升了实例级理解，还增强了通用图像和视频理解的整体能力。

> Large Multimodal Models (LMMs) have made significant breakthroughs with the advancement of instruction tuning. However, while existing models can understand images and videos at a holistic level, they still struggle with instance-level understanding that requires a more nuanced comprehension and alignment. Instance-level understanding is crucial, as it focuses on the specific elements that we are most interested in. Excitingly, existing works find that the state-of-the-art LMMs exhibit strong instance understanding capabilities when provided with explicit visual cues. Motivated by this, we introduce an automated annotation pipeline assisted by GPT-4o to extract instance-level information from images and videos through explicit visual prompting for instance guidance. Building upon this pipeline, we proposed Inst-IT, a solution to enhance LMMs in Instance understanding via explicit visual prompt Instruction Tuning. Inst-IT consists of a benchmark to diagnose multimodal instance-level understanding, a large-scale instruction-tuning dataset, and a continuous instruction-tuning training paradigm to effectively enhance spatial-temporal instance understanding capabilities of existing LMMs. Experimental results show that, with the boost of Inst-IT, our models not only achieve outstanding performance on Inst-IT Bench but also demonstrate significant improvements across various generic image and video understanding benchmarks. This highlights that our dataset not only boosts instance-level understanding but also strengthens the overall capabilities of generic image and video comprehension.

[Arxiv](https://arxiv.org/abs/2412.03565)