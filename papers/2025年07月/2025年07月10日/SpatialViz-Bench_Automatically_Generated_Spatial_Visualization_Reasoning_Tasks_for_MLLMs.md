# SpatialViz-Bench：专为多语言大语言模型设计的自动生成空间可视化推理任务

发布时间：2025年07月10日

`LLM应用` `教育评估` `人工智能`

> SpatialViz-Bench: Automatically Generated Spatial Visualization Reasoning Tasks for MLLMs

# 摘要

> 人类具备在大脑中直接想象与操作视觉图像的能力，这被称为空间可视化能力。尽管多模态大型语言模型（MLLMs）能够支持基于想象的推理，但目前对空间可视化能力的评估仍显不足，通常将其嵌入到更广泛的数学与逻辑评估中。现有评估方法多依赖于可能与训练数据存在重叠的智商测试或数学竞赛，这可能影响评估的可靠性。为此，我们推出了SpatialViz-Bench——一个全面的多模态空间可视化基准测试，涵盖4种子能力的12项任务，包含1180个自动生成的问题。通过对33个最先进MLLMs的评估，我们不仅发现了模型性能的显著差异，证实了该基准测试的强大区分能力，还揭示了令人意外的发现：模型在难度感知上与人类直觉存在偏差，表现出从2D到3D任务的性能断崖，并在需要纯可视化解决的空间任务中，默认采用公式推导方式。SpatialViz-Bench实证表明，当前最先进的MLLMs在空间可视化任务中仍存在明显短板，填补了该领域的重要研究空白。该基准测试现已公开发布。

> Humans can directly imagine and manipulate visual images in their minds, a capability known as spatial visualization. While multi-modal Large Language Models (MLLMs) support imagination-based reasoning, spatial visualization remains insufficiently evaluated, typically embedded within broader mathematical and logical assessments. Existing evaluations often rely on IQ tests or math competitions that may overlap with training data, compromising assessment reliability. To this end, we introduce SpatialViz-Bench, a comprehensive multi-modal benchmark for spatial visualization with 12 tasks across 4 sub-abilities, comprising 1,180 automatically generated problems. Our evaluation of 33 state-of-the-art MLLMs not only reveals wide performance variations and demonstrates the benchmark's strong discriminative power, but also uncovers counter-intuitive findings: models exhibit unexpected behaviors by showing difficulty perception that misaligns with human intuition, displaying dramatic 2D-to-3D performance cliffs, and defaulting to formula derivation despite spatial tasks requiring visualization alone. SpatialVizBench empirically demonstrates that state-of-the-art MLLMs continue to exhibit deficiencies in spatial visualization tasks, thereby addressing a significant lacuna in the field. The benchmark is publicly available.

[Arxiv](https://arxiv.org/abs/2507.07610)