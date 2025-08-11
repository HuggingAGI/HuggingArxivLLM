# OmniEAR: 针具身任务的智能体推理能力评测

发布时间：2025年08月07日

`Agent` `机器人技术`

> OmniEAR: Benchmarking Agent Reasoning in Embodied Tasks

# 摘要

> 大型语言模型在抽象推理方面表现出色，但它们在具身智能体推理方面的能力仍 largely 未被探索。我们提出了 OmniEAR，一个全面的框架，用于评估语言模型在具身任务中对物理交互、工具使用和多智能体协作的推理能力。与现有提供预定义工具集或显式协作指令的基准不同，OmniEAR 要求智能体根据任务需求动态获取能力和自主确定协作策略。通过基于文本的环境表示，我们在涵盖家庭和工业领域的 1,500 个场景中建模了连续的物理特性和复杂空间关系。我们的系统评估显示，当模型必须从约束中推理时，性能显著下降：在显式指令下达到 85-96% 的成功率，但在工具推理中降至 56-85%，在隐式协作中降至 63-85%，复合任务的失败率超过 50%。令人惊讶的是，完整的环境信息会降低协作性能，表明模型无法筛选与任务相关的约束。微调对单智能体任务有显著提升（从 0.6% 提升至 76.3%），但对多智能体任务的提升有限（从 1.5% 提升至 5.5%），揭示了模型架构的基本限制。这些发现表明，具身推理提出了当前模型无法完全解决的根本性挑战，确立了 OmniEAR 作为评估和推进具身 AI 系统的严格基准。我们的代码和数据包含在补充材料中，并将在接受后开源。

> Large language models excel at abstract reasoning but their capacity for embodied agent reasoning remains largely unexplored. We present OmniEAR, a comprehensive framework for evaluating how language models reason about physical interactions, tool usage, and multi-agent coordination in embodied tasks. Unlike existing benchmarks that provide predefined tool sets or explicit collaboration directives, OmniEAR requires agents to dynamically acquire capabilities and autonomously determine coordination strategies based on task demands. Through text-based environment representation, we model continuous physical properties and complex spatial relationships across 1,500 scenarios spanning household and industrial domains. Our systematic evaluation reveals severe performance degradation when models must reason from constraints: while achieving 85-96% success with explicit instructions, performance drops to 56-85% for tool reasoning and 63-85% for implicit collaboration, with compound tasks showing over 50% failure rates. Surprisingly, complete environmental information degrades coordination performance, indicating models cannot filter task-relevant constraints. Fine-tuning improves single-agent tasks dramatically (0.6% to 76.3%) but yields minimal multi-agent gains (1.5% to 5.5%), exposing fundamental architectural limitations. These findings demonstrate that embodied reasoning poses fundamentally different challenges than current models can address, establishing OmniEAR as a rigorous benchmark for evaluating and advancing embodied AI systems. Our code and data are included in the supplementary materials and will be open-sourced upon acceptance.

[Arxiv](https://arxiv.org/abs/2508.05614)