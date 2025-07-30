# UserBench：面向用户中心智能体的交互式 Gym 环境

发布时间：2025年07月29日

`Agent` `人机交互` `基准测试`

> UserBench: An Interactive Gym Environment for User-Centric Agents

# 摘要

> 基于大型语言模型（LLMs）的代理在推理和工具使用方面取得了显著进展，能够解决复杂任务。然而，它们在主动与用户协作，特别是在目标模糊、动态变化或间接表达时的能力，仍有待深入探索。为填补这一空白，我们推出了UserBench——一个用户为中心的基准测试，旨在评估代理在多轮、偏好驱动的交互中的表现。UserBench模拟用户从不明确的目标开始，并逐步揭示偏好，要求代理主动澄清意图并利用工具做出有依据的决策。我们对领先开源和闭源LLMs的评估显示，任务完成与用户对齐之间存在显著差距。例如，模型仅在20%的时间内平均完全符合所有用户意图，即使是最先进的模型也只能通过主动交互发现不到30%的用户偏好。这些结果突显了构建不仅是有能力的任务执行者，更是真正的协作伙伴的代理的挑战。UserBench提供了一个交互式环境，用于衡量和提升这一关键能力。

> Large Language Models (LLMs)-based agents have made impressive progress in reasoning and tool use, enabling them to solve complex tasks. However, their ability to proactively collaborate with users, especially when goals are vague, evolving, or indirectly expressed, remains underexplored. To address this gap, we introduce UserBench, a user-centric benchmark designed to evaluate agents in multi-turn, preference-driven interactions. UserBench features simulated users who start with underspecified goals and reveal preferences incrementally, requiring agents to proactively clarify intent and make grounded decisions with tools. Our evaluation of leading open- and closed-source LLMs reveals a significant disconnect between task completion and user alignment. For instance, models provide answers that fully align with all user intents only 20% of the time on average, and even the most advanced models uncover fewer than 30% of all user preferences through active interaction. These results highlight the challenges of building agents that are not just capable task executors, but true collaborative partners. UserBench offers an interactive environment to measure and advance this critical capability.

[Arxiv](https://arxiv.org/abs/2507.22034)