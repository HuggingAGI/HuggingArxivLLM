# OmniEVA：基于任务自适应3D接地与具身感知推理的具身多能规划器

发布时间：2025年09月11日

`Agent` `工业与制造`

> OmniEVA: Embodied Versatile Planner via Task-Adaptive 3D-Grounded and Embodiment-aware Reasoning

# 摘要

> 多模态大型语言模型（MLLMs）的最新进展为具身智能带来了新机遇，使其能够实现多模态理解、推理、交互以及连续的空间决策。然而，当前基于MLLM的具身系统存在两个关键局限。第一，几何适应性差距：仅依赖2D输入训练或通过硬编码注入3D几何信息的模型，要么空间信息不足，要么2D泛化能力受限，从而在空间需求多样的任务中适应性欠佳。第二，具身约束差距：以往研究常忽略真实机器人的物理约束与能力，使得任务计划虽理论有效却难以实际执行。为弥合这些差距，我们提出OmniEVA——一个具身通用规划器，它通过两项关键创新实现了高级具身推理与任务规划：（1）任务自适应3D接地机制：引入门控路由器，根据上下文需求对3D融合进行显式选择性调节，从而为不同具身任务提供上下文感知的3D接地。（2）具身感知推理框架：将任务目标与具身约束联合融入推理循环，生成既面向目标又可执行的规划决策。大量实验结果表明，OmniEVA不仅在通用具身推理性能上达到了最先进水平，还在各类下游场景中展现出强大能力。通过对一系列新提出的具身基准（涵盖基础任务与复合任务）的评估，证实了其稳健且通用的规划能力。项目页面：https://omnieva.github.io

> Recent advances in multimodal large language models (MLLMs) have opened new opportunities for embodied intelligence, enabling multimodal understanding, reasoning, and interaction, as well as continuous spatial decision-making. Nevertheless, current MLLM-based embodied systems face two critical limitations. First, Geometric Adaptability Gap: models trained solely on 2D inputs or with hard-coded 3D geometry injection suffer from either insufficient spatial information or restricted 2D generalization, leading to poor adaptability across tasks with diverse spatial demands. Second, Embodiment Constraint Gap: prior work often neglects the physical constraints and capacities of real robots, resulting in task plans that are theoretically valid but practically infeasible.To address these gaps, we introduce OmniEVA -- an embodied versatile planner that enables advanced embodied reasoning and task planning through two pivotal innovations: (1) a Task-Adaptive 3D Grounding mechanism, which introduces a gated router to perform explicit selective regulation of 3D fusion based on contextual requirements, enabling context-aware 3D grounding for diverse embodied tasks. (2) an Embodiment-Aware Reasoning framework that jointly incorporates task goals and embodiment constraints into the reasoning loop, resulting in planning decisions that are both goal-directed and executable. Extensive experimental results demonstrate that OmniEVA not only achieves state-of-the-art general embodied reasoning performance, but also exhibits a strong ability across a wide range of downstream scenarios. Evaluations of a suite of proposed embodied benchmarks, including both primitive and composite tasks, confirm its robust and versatile planning capabilities. Project page: https://omnieva.github.io

[Arxiv](https://arxiv.org/abs/2509.09332)