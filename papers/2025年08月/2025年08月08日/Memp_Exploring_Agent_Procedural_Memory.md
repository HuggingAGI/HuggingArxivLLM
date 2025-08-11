# Memp：深入探索智能体过程记忆

发布时间：2025年08月08日

`Agent` `人工智能` `智能体`

> Memp: Exploring Agent Procedural Memory

# 摘要

> 基于大型语言模型（LLMs）的智能体在多种任务中表现出色，但它们的程序记忆却存在脆弱性，要么需要手动设计，要么与静态参数纠缠在一起。在这项研究中，我们探讨了赋予智能体一种可学习、可更新且终身的程序记忆的策略。我们提出了Memp，它能够将过去的智能体轨迹提炼成细致入微的分步指令以及更高层次的脚本式抽象，并探索了程序记忆在构建、检索和更新过程中不同策略的影响。配合一个动态机制，该机制持续更新、修正和淘汰其内容，这个记忆库能够与新的经验同步演进。在TravelPlanner和ALFWorld上的实证评估表明，随着记忆库的不断优化，智能体在类似任务上实现了稳步提升的成功率和效率。此外，由更强模型构建的程序记忆依然保有其价值：将程序记忆迁移至较弱模型中，能够带来显著的性能提升。

> Large Language Models (LLMs) based agents excel at diverse tasks, yet they suffer from brittle procedural memory that is manually engineered or entangled in static parameters. In this work, we investigate strategies to endow agents with a learnable, updatable, and lifelong procedural memory. We propose Memp that distills past agent trajectories into both fine-grained, step-by-step instructions and higher-level, script-like abstractions, and explore the impact of different strategies for Build, Retrieval, and Update of procedural memory. Coupled with a dynamic regimen that continuously updates, corrects, and deprecates its contents, this repository evolves in lockstep with new experience. Empirical evaluation on TravelPlanner and ALFWorld shows that as the memory repository is refined, agents achieve steadily higher success rates and greater efficiency on analogous tasks. Moreover, procedural memory built from a stronger model retains its value: migrating the procedural memory to a weaker model yields substantial performance gains.

[Arxiv](https://arxiv.org/abs/2508.06433)