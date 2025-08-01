# MPCC：专为多模态大型语言模型设计的复杂约束多模态规划新型基准测试

发布时间：2025年07月31日

`LLM应用`

> MPCC: A Novel Benchmark for Multimodal Planning with Complex Constraints in Multimodal Large Language Models

# 摘要

> 多模态规划能力指的是在多模态上下文中预测、推理和设计任务执行步骤的能力，这对于跨多步骤的复杂推理和决策至关重要。然而，当前的基准测试面临两大关键挑战：(1) 它们无法直接评估多模态现实世界规划能力，(2) 它们缺乏跨模态的约束或隐性约束。为了解决这些问题，我们引入了多模态复杂约束规划（MPCC），这是首个系统评估多模态大语言模型（MLLMs）在规划中处理多模态约束能力的基准。为了解决第一个挑战，MPCC专注于三个现实任务：飞行规划、日历规划和会议规划。为了解决第二个挑战，我们在这些任务中引入了复杂约束（如预算、时间和空间约束），并设置了分级难度级别（EASY、MEDIUM、HARD），以区分约束复杂性和搜索空间扩展。对13个先进MLLMs的实验揭示了重大挑战：闭源模型仅实现21.3%的可行计划，而开源模型平均低于11%。此外，我们发现MLLMs对约束复杂性极为敏感，且传统多模态提示策略在多约束场景下失效。我们的工作正式化了规划中的多模态约束，提供了一个严格的评估框架，并突显了在现实世界MLLM应用中推进约束感知推理的必要性。

> Multimodal planning capabilities refer to the ability to predict, reason, and design steps for task execution with multimodal context, which is essential for complex reasoning and decision-making across multiple steps. However, current benchmarks face two key challenges: (1) they cannot directly assess multimodal real-world planning capabilities, and (2) they lack constraints or implicit constraints across modalities. To address these issues, we introduce Multimodal Planning with Complex Constraints (MPCC), the first benchmark to systematically evaluate MLLMs' ability to handle multimodal constraints in planning. To address the first challenge, MPCC focuses on three real-world tasks: Flight Planning, Calendar Planning, and Meeting Planning. To solve the second challenge, we introduce complex constraints (e.g. budget, temporal, and spatial) in these tasks, with graded difficulty levels (EASY, MEDIUM, HARD) to separate constraint complexity from search space expansion. Experiments on 13 advanced MLLMs reveal significant challenges: closed-source models achieve only 21.3% feasible plans, while open-source models average below 11%. Additionally, we observe that MLLMs are highly sensitive to constraint complexity and that traditional multimodal prompting strategies fail in multi-constraint scenarios. Our work formalizes multimodal constraints in planning, provides a rigorous evaluation framework, and highlights the need for advancements in constraint-aware reasoning for real-world MLLM applications.

[Arxiv](https://arxiv.org/abs/2507.23382)