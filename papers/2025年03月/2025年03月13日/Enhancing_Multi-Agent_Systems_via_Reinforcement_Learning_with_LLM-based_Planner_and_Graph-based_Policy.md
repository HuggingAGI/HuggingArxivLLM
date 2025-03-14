# 基于强化学习的多智能体系统增强方法：结合LLM规划器与图结构策略

发布时间：2025年03月13日

`Agent` `多智能体系统` `机器人`

> Enhancing Multi-Agent Systems via Reinforcement Learning with LLM-based Planner and Graph-based Policy

# 摘要

> 多智能体系统（MAS）在复杂任务执行中展现出巨大潜力，但协调与安全性仍是重大挑战。多智能体强化学习（MARL）为智能体协作提供了一个有前景的框架，但在处理复杂任务和设计奖励函数方面仍面临困难。大型语言模型（LLMs）的引入为MAS带来了更强的推理和认知能力，但现有基于LLM的系统在动态环境中难以快速准确地响应。为应对这些挑战，我们提出了一种基于LLM的图协作MARL框架（LGC-MARL），该框架能够高效结合LLMs与MARL。此框架将复杂任务分解为可执行子任务，并通过基于图的协调实现多智能体的高效协作。具体而言，LGC-MARL包含两个主要组件：LLM规划器和基于图的协作元策略。LLM规划器将复杂的任务指令转化为一系列可执行子任务，利用批评模型评估这些子任务的合理性，并生成动作依赖图。基于图的协作元策略根据动作依赖图促进智能体间的沟通与协作，并通过元学习适应新的任务环境。在AI2-THOR仿真平台上进行的实验结果表明，LGC-MARL在完成各种复杂任务方面具有优越的性能和良好的可扩展性。

> Multi-agent systems (MAS) have shown great potential in executing complex tasks, but coordination and safety remain significant challenges. Multi-Agent Reinforcement Learning (MARL) offers a promising framework for agent collaboration, but it faces difficulties in handling complex tasks and designing reward functions. The introduction of Large Language Models (LLMs) has brought stronger reasoning and cognitive abilities to MAS, but existing LLM-based systems struggle to respond quickly and accurately in dynamic environments. To address these challenges, we propose LLM-based Graph Collaboration MARL (LGC-MARL), a framework that efficiently combines LLMs and MARL. This framework decomposes complex tasks into executable subtasks and achieves efficient collaboration among multiple agents through graph-based coordination. Specifically, LGC-MARL consists of two main components: an LLM planner and a graph-based collaboration meta policy. The LLM planner transforms complex task instructions into a series of executable subtasks, evaluates the rationality of these subtasks using a critic model, and generates an action dependency graph. The graph-based collaboration meta policy facilitates communication and collaboration among agents based on the action dependency graph, and adapts to new task environments through meta-learning. Experimental results on the AI2-THOR simulation platform demonstrate the superior performance and scalability of LGC-MARL in completing various complex tasks.

[Arxiv](https://arxiv.org/abs/2503.10049)