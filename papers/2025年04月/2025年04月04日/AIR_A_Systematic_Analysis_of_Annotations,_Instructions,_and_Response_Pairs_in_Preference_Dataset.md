# AIR：系统分析偏好数据集中的注释、指令与响应对

发布时间：2025年04月04日

`LLM应用` `模型训练` `机器学习`

> AIR: A Systematic Analysis of Annotations, Instructions, and Response Pairs in Preference Dataset

# 摘要

> 偏好学习是将大型语言模型（LLMs）与人类价值观对齐的关键，而其成功依赖于高质量的数据集，这些数据集由三个核心组件组成：偏好	extbf{A}注释、	extbf{I}指令和	extbf{R}响应对。然而，现有方法将这些组件混为一谈，忽视了它们各自的影响，导致系统优化受阻。为此，我们提出了	extbf{AIR}框架，它通过系统地分离和优化每个组件，并评估它们的协同效应，为偏好学习提供了一种全新的分析方法。通过严格的实验，我们发现：注释的简洁性（点式生成评分）、指令推断的稳定性（基于方差的跨LLM过滤）以及响应对的质量（适度的边界+高绝对分数）是提升模型性能的关键。将这些原则结合使用，即使仅使用14k高质量对，也能使模型性能比基线方法平均提升+5.3。我们的研究将偏好数据集的设计从随意扩展转变为组件感知优化，为高效、可重复的模型对齐提供了清晰的蓝图。

> Preference learning is critical for aligning large language models (LLMs) with human values, yet its success hinges on high-quality datasets comprising three core components: Preference \textbf{A}nnotations, \textbf{I}nstructions, and \textbf{R}esponse Pairs. Current approaches conflate these components, obscuring their individual impacts and hindering systematic optimization. In this work, we propose \textbf{AIR}, a component-wise analysis framework that systematically isolates and optimizes each component while evaluating their synergistic effects. Through rigorous experimentation, AIR reveals actionable principles: annotation simplicity (point-wise generative scoring), instruction inference stability (variance-based filtering across LLMs), and response pair quality (moderate margins + high absolute scores). When combined, these principles yield +5.3 average gains over baseline method, even with only 14k high-quality pairs. Our work shifts preference dataset design from ad hoc scaling to component-aware optimization, offering a blueprint for efficient, reproducible alignment.

[Arxiv](https://arxiv.org/abs/2504.03612)