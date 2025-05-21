# SayCoNav：基于大型语言模型的去中心化多机器人导航系统中的自适应协作机制

发布时间：2025年05月19日

`Agent` `机器人` `团队协作`

> SayCoNav: Utilizing Large Language Models for Adaptive Collaboration in Decentralized Multi-Robot Navigation

# 摘要

> 在大规模未知环境中，团队协作是自主机器人完成复杂导航任务的关键。一个成功的协作策略需要根据每台机器人的技能和实时状态灵活调整，以确保团队目标的实现。我们提出了 SayCoNav，这是一种基于大型语言模型（LLMs）的全新方法，能够为机器人团队自动生成并优化协作策略。每个机器人利用 LLM 以分散的方式规划和执行任务，同时通过实时信息共享不断更新自己的行动方案。我们在多目标导航（MultiON）任务中验证了 SayCoNav 的有效性，该任务要求机器人团队在未知环境中高效搜索多个目标。实验结果表明，与传统方法相比，SayCoNav 能够通过机器人间的高效协作将搜索效率提升 44.28%，并且在任务执行过程中能够动态适应环境变化。

> Adaptive collaboration is critical to a team of autonomous robots to perform complicated navigation tasks in large-scale unknown environments. An effective collaboration strategy should be determined and adapted according to each robot's skills and current status to successfully achieve the shared goal. We present SayCoNav, a new approach that leverages large language models (LLMs) for automatically generating this collaboration strategy among a team of robots. Building on the collaboration strategy, each robot uses the LLM to generate its plans and actions in a decentralized way. By sharing information to each other during navigation, each robot also continuously updates its step-by-step plans accordingly. We evaluate SayCoNav on Multi-Object Navigation (MultiON) tasks, that require the team of the robots to utilize their complementary strengths to efficiently search multiple different objects in unknown environments. By validating SayCoNav with varied team compositions and conditions against baseline methods, our experimental results show that SayCoNav can improve search efficiency by at most 44.28% through effective collaboration among heterogeneous robots. It can also dynamically adapt to the changing conditions during task execution.

[Arxiv](https://arxiv.org/abs/2505.13729)