# 基础模型在逐步具身推理中的表现如何？

发布时间：2025年09月18日

`Agent` `工业与制造`

> How Good are Foundation Models in Step-by-Step Embodied Reasoning?

# 摘要

> 在物理世界中活动的具身智能体，其决策不仅要高效，还需兼顾安全性、空间连贯性与情境适配性。尽管大型多模态模型（LMMs）近年来在视觉理解与语言生成上展现出不俗潜力，但其在现实具身任务中进行结构化推理的能力尚未得到深入研究。本研究旨在探究基础模型在具身环境中的逐步推理能力。为此，我们构建了基础模型具身推理（FoMER）基准，用于评估LMMs在复杂具身决策场景中的推理表现。该基准包含多样化任务集，要求智能体完成多模态观察解读、物理约束与安全性推理，并以自然语言生成合理的下一步行动。具体而言，我们的贡献包括：（i）一套大规模、精心构建的具身推理任务集；（ii）一个新颖的评估框架，可分离感知接地与行动推理过程；（iii）在此设置下对主流LMMs的实证分析。该基准包含超1.1k个样本，覆盖10项任务与8种具身形态，每项样本均配有详细的逐步推理过程，涉及三类不同机器人。研究结果揭示了LMMs在具身推理中的潜力与不足，为机器人智能领域的未来研究指明了关键挑战与机遇。相关数据与代码将公开发布。

> Embodied agents operating in the physical world must make decisions that are not only effective but also safe, spatially coherent, and grounded in context. While recent advances in large multimodal models (LMMs) have shown promising capabilities in visual understanding and language generation, their ability to perform structured reasoning for real-world embodied tasks remains underexplored. In this work, we aim to understand how well foundation models can perform step-by-step reasoning in embodied environments. To this end, we propose the Foundation Model Embodied Reasoning (FoMER) benchmark, designed to evaluate the reasoning capabilities of LMMs in complex embodied decision-making scenarios. Our benchmark spans a diverse set of tasks that require agents to interpret multimodal observations, reason about physical constraints and safety, and generate valid next actions in natural language. We present (i) a large-scale, curated suite of embodied reasoning tasks, (ii) a novel evaluation framework that disentangles perceptual grounding from action reasoning, and (iii) empirical analysis of several leading LMMs under this setting. Our benchmark includes over 1.1k samples with detailed step-by-step reasoning across 10 tasks and 8 embodiments, covering three different robot types. Our results highlight both the potential and current limitations of LMMs in embodied reasoning, pointing towards key challenges and opportunities for future research in robot intelligence. Our data and code will be made publicly available.

[Arxiv](https://arxiv.org/abs/2509.15293)