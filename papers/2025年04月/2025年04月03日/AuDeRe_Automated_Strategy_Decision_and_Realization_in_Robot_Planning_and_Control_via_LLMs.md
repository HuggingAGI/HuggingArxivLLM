# AuDeRe：基于LLMs的机器人规划与控制中自动化策略决策与实现

发布时间：2025年04月03日

`LLM应用` `机器人` `智能决策系统`

> AuDeRe: Automated Strategy Decision and Realization in Robot Planning and Control via LLMs

# 摘要

> 大型语言模型（LLMs）近期在机器人等多领域展现出巨大潜力。然而，现有基于LLMs的机器人应用大多受限于直接预测路点或固定工具框架，灵活性不足。我们提出了一种创新框架，通过LLMs根据任务描述、环境约束和系统动力学选择最优规划与控制策略，并调用全面API执行。我们的迭代推理方法结合性能反馈，持续优化算法选择。从简单跟踪到复杂规划场景的实验验证了该方法的显著优势：显著提升机器人自主性，减少手动调整需求，同时超越传统基线方法，展现出强大的跨任务通用性。

> Recent advancements in large language models (LLMs) have shown significant promise in various domains, especially robotics. However, most prior LLM-based work in robotic applications either directly predicts waypoints or applies LLMs within fixed tool integration frameworks, offering limited flexibility in exploring and configuring solutions best suited to different tasks. In this work, we propose a framework that leverages LLMs to select appropriate planning and control strategies based on task descriptions, environmental constraints, and system dynamics. These strategies are then executed by calling the available comprehensive planning and control APIs. Our approach employs iterative LLM-based reasoning with performance feedback to refine the algorithm selection. We validate our approach through extensive experiments across tasks of varying complexity, from simple tracking to complex planning scenarios involving spatiotemporal constraints. The results demonstrate that using LLMs to determine planning and control strategies from natural language descriptions significantly enhances robotic autonomy while reducing the need for extensive manual tuning and expert knowledge. Furthermore, our framework maintains generalizability across different tasks and notably outperforms baseline methods that rely on LLMs for direct trajectory, control sequence, or code generation.

[Arxiv](https://arxiv.org/abs/2504.03015)