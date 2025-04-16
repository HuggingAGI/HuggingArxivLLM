# # PuzzleBench：用于大型多模态模型解谜的动态评估框架

发布时间：2025年04月15日

`其他` `视觉问答` `多模态`

> PuzzleBench: A Fully Dynamic Evaluation Framework for Large Multimodal Models on Puzzle Solving

# 摘要

> 大型多模态模型（LMMs）在多模态任务中表现优异，不断刷新各类评估基准。然而，现有基准存在静态化和数据污染问题，手动标注数据集也面临诸多挑战。为解决这些问题，我们提出了动态多模态评估框架OVPG，专注于生成新鲜、多样且可验证的谜题解答任务数据。OVPG由三个模块组成，确保评估实例的基础性、随机性和唯一解，以适应LMMs的持续进化。基于此，我们构建了包含11,840个VQA样本的动态基准PuzzleBench，涵盖六个谜题任务，重点评估视觉识别、逻辑推理和上下文理解能力。与静态基准不同，PuzzleBench通过持续更新和丰富设计，实现与LMMs能力的无缝适配。

> Large Multimodal Models (LMMs) have demonstrated impressive capabilities across a wide range of multimodal tasks, achieving ever-increasing performance on various evaluation benchmarks. However, existing benchmarks are typically static and often overlap with pre-training datasets, leading to fixed complexity constraints and substantial data contamination issues. Meanwhile, manually annotated datasets are labor-intensive, time-consuming, and subject to human bias and inconsistency, leading to reliability and reproducibility issues. To address these problems, we propose a fully dynamic multimodal evaluation framework, named Open-ended Visual Puzzle Generation (OVPG), which aims to generate fresh, diverse, and verifiable evaluation data automatically in puzzle-solving tasks. Specifically, the OVPG pipeline consists of a raw material sampling module, a visual content generation module, and a puzzle rule design module, which ensures that each evaluation instance is primitive, highly randomized, and uniquely solvable, enabling continual adaptation to the evolving capabilities of LMMs. Built upon OVPG, we construct PuzzleBench, a dynamic and scalable benchmark comprising 11,840 VQA samples. It features six carefully designed puzzle tasks targeting three core LMM competencies, visual recognition, logical reasoning, and context understanding. PuzzleBench differs from static benchmarks that quickly become outdated. It enables ongoing dataset refreshing through OVPG and a rich set of open-ended puzzle designs, allowing seamless adaptation to the evolving capabilities of LMMs.

[Arxiv](https://arxiv.org/abs/2504.10885)