# Envisioning Beyond the Pixels: Benchmarking Reasoning-Informed Visual Editing
超越像素：推理驱动的视觉编辑基准测试

发布时间：2025年04月03日

`其他` `视觉编辑` `推理系统`

> Envisioning Beyond the Pixels: Benchmarking Reasoning-Informed Visual Editing

# 摘要

> 大型多模态模型（LMMs）在视觉理解和生成方面取得了长足进步，但在通用视觉编辑领域，尤其是在处理复杂指令、保持视觉一致性和支持多样化输入格式方面，仍面临诸多挑战。为应对这一研究空白，我们推出了RISEBench，这是首个专注于评估基于推理的视觉编辑（RISE）能力的基准测试。RISEBench聚焦于四大核心推理类型：时序、因果、空间和逻辑推理。我们为每个类别精心挑选了高质量的测试案例，并构建了一套全面的评估框架，通过人工评审和基于LMM的自动化评审相结合的方式，从指令理解、视觉一致性和生成合理性三个维度进行综合评估。实验结果表明，尽管GPT-4o-Native在性能上远超其他开源及专有模型，但即便是这一最先进的系统，在处理复杂的逻辑推理任务时仍显吃力，凸显了该领域研究的空白。作为一项开创性工作，RISEBench旨在为推理增强的视觉编辑提供基础性的研究视角，并推动未来研究的深入开展。尽管仍处于起步阶段，但我们致力于持续扩展和优化这一基准测试，以支持对下一代多模态系统进行全面、可靠且可扩展的评估。我们的代码和数据将在https://github.com/PhoenixZ810/RISEBench上公开发布。

> Large Multi-modality Models (LMMs) have made significant progress in visual understanding and generation, but they still face challenges in General Visual Editing, particularly in following complex instructions, preserving appearance consistency, and supporting flexible input formats. To address this gap, we introduce RISEBench, the first benchmark for evaluating Reasoning-Informed viSual Editing (RISE). RISEBench focuses on four key reasoning types: Temporal, Causal, Spatial, and Logical Reasoning. We curate high-quality test cases for each category and propose an evaluation framework that assesses Instruction Reasoning, Appearance Consistency, and Visual Plausibility with both human judges and an LMM-as-a-judge approach. Our experiments reveal that while GPT-4o-Native significantly outperforms other open-source and proprietary models, even this state-of-the-art system struggles with logical reasoning tasks, highlighting an area that remains underexplored. As an initial effort, RISEBench aims to provide foundational insights into reasoning-aware visual editing and to catalyze future research. Though still in its early stages, we are committed to continuously expanding and refining the benchmark to support more comprehensive, reliable, and scalable evaluations of next-generation multimodal systems. Our code and data will be released at https://github.com/PhoenixZ810/RISEBench.

[Arxiv](https://arxiv.org/abs/2504.02826)