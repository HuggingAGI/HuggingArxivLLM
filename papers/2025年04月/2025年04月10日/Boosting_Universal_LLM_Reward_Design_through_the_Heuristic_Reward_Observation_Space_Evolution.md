# # 通过启发式奖励观察空间进化提升通用大语言模型奖励设计

发布时间：2025年04月10日

`LLM应用` `人工智能`

> Boosting Universal LLM Reward Design through the Heuristic Reward Observation Space Evolution

# 摘要

> 大型语言模型 (LLMs) 凭借其在常识推理和代码生成方面的强大能力，正在成为自动化强化学习 (RL) 奖励设计的有力工具。通过与 RL 代理进行对话，LLMs 根据环境状态及其内部操作构建奖励观察空间 (ROS)。然而，现有框架尚未有效利用历史探索数据或手动任务描述来优化这一空间。本文提出了一种创新的启发式框架，通过基于表格的探索缓存机制和文本-代码对齐策略，提升 LLM 驱动奖励设计的效果。我们的框架引入了一个状态执行表，用于追踪环境状态的历史使用情况及成功率，从而突破了 LLM 对话中常见的马尔可夫约束，促进更有效的探索。此外，我们利用结构化提示将用户提供的任务描述与专家定义的成功标准进行对齐，确保奖励设计目标的一致性。在基准 RL 任务上的综合评估验证了所提框架的有效性和稳定性。代码和视频演示可在 jingjjjjjie.github.io/LLM2Reward 获取。


> Large Language Models (LLMs) are emerging as promising tools for automated reinforcement learning (RL) reward design, owing to their robust capabilities in commonsense reasoning and code generation. By engaging in dialogues with RL agents, LLMs construct a Reward Observation Space (ROS) by selecting relevant environment states and defining their internal operations. However, existing frameworks have not effectively leveraged historical exploration data or manual task descriptions to iteratively evolve this space. In this paper, we propose a novel heuristic framework that enhances LLM-driven reward design by evolving the ROS through a table-based exploration caching mechanism and a text-code reconciliation strategy. Our framework introduces a state execution table, which tracks the historical usage and success rates of environment states, overcoming the Markovian constraint typically found in LLM dialogues and facilitating more effective exploration. Furthermore, we reconcile user-provided task descriptions with expert-defined success criteria using structured prompts, ensuring alignment in reward design objectives. Comprehensive evaluations on benchmark RL tasks demonstrate the effectiveness and stability of the proposed framework. Code and video demos are available at jingjjjjjie.github.io/LLM2Reward.

[Arxiv](https://arxiv.org/abs/2504.07596)