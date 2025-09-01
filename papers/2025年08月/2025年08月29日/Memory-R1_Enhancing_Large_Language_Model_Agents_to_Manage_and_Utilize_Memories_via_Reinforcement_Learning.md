# Memory-R1：通过强化学习增强大型语言模型智能体的记忆管理与利用能力

发布时间：2025年08月29日

`Agent` `基础理论`

> Memory-R1: Enhancing Large Language Model Agents to Manage and Utilize Memories via Reinforcement Learning

# 摘要

> 大型语言模型（LLMs）在众多自然语言处理（NLP）任务中已展现出惊人能力，但它们本质上仍是无状态模型，受限于有限的上下文窗口，难以进行长程推理。近期虽有研究尝试为LLMs配备外部记忆库以突破这一局限，但多数现有方案静态且依赖启发式规则，缺乏学习机制来决定存储、更新或检索哪些内容。为此，我们提出Memory-R1——一个强化学习（RL）框架，通过两个专用智能体让LLMs具备主动管理和利用外部记忆的能力：记忆管理器负责学习执行结构化记忆操作（包括添加、更新、删除记忆条目或不操作）；回答智能体则筛选出最相关的条目并对其推理以生成答案。两个智能体均通过结果驱动的强化学习（PPO与GRPO）进行微调，能在最小监督下实现自适应记忆管理与利用。仅用152个问答对及相应的时序记忆库训练，Memory-R1便超越了现有最强基线，并在不同问题类型和LLM骨干模型上均展现出强大的泛化能力。除提供这一高效方案外，本研究还深入揭示了强化学习如何激发LLMs更具智能体特性、记忆感知的行为，为构建更丰富、更持久的推理系统提供了方向。

> Large Language Models (LLMs) have demonstrated impressive capabilities across a wide range of NLP tasks, but they remain fundamentally stateless, constrained by limited context windows that hinder long-horizon reasoning. Recent efforts to address this limitation often augment LLMs with an external memory bank, yet most existing pipelines are static and heuristic-driven, lacking any learned mechanism for deciding what to store, update, or retrieve. We present Memory-R1, a reinforcement learning (RL) framework that equips LLMs with the ability to actively manage and utilize external memory through two specialized agents: a Memory Manager that learns to perform structured memory operations, including adding, updating, deleting, or taking no operation on memory entries; and an Answer Agent that selects the most relevant entries and reasons over them to produce an answer. Both agents are fine-tuned with outcome-driven RL (PPO and GRPO), enabling adaptive memory management and utilization with minimal supervision. With as few as 152 question-answer pairs and a corresponding temporal memory bank for training, Memory-R1 outperforms the strongest existing baseline and demonstrates strong generalization across diverse question types and LLM backbones. Beyond presenting an effective approach, this work provides insights into how RL can unlock more agentic, memory-aware behavior in LLMs, pointing toward richer, more persistent reasoning systems.

[Arxiv](https://arxiv.org/abs/2508.19828)