# 对话式规划用于私人计划

发布时间：2025年02月26日

`LLM应用` `对话系统`

> Conversational Planning for Personal Plans

# 摘要

> 大型语言模型（LLMs）凭借其强大的语言生成和推理能力，使对话系统在代码生成、撰写文章、通过 STEM 和法律考试，乃至知识搜索等领域表现出色。除了这些短期应用，LLMs 还被越来越多地用于帮助实现长期目标或需要较长时间完成的任务，涉及跨越数天、数周、数月甚至数年的多个会话。为了让对话系统能够处理长期交互和任务，我们需要具备长期规划能力的语言代理。传统上，这类能力由具有分层规划能力的强化学习代理实现。在这项工作中，我们提出了一种新型架构：LLM 作为元控制器，决定代理的下一步宏观动作，而工具增强的 LLM 基础选项策略执行选定的宏观动作。我们针对特定的宏观动作集实现了这一框架，通过对话和后续问题收集用户反馈，从而实现用户个人计划的自适应规划。这一范式可应用于从学术和非学术任务的辅导到个人健康计划的对话教练等多种场景。

> The language generation and reasoning capabilities of large language models (LLMs) have enabled conversational systems with impressive performance in a variety of tasks, from code generation, to composing essays, to passing STEM and legal exams, to a new paradigm for knowledge search. Besides those short-term use applications, LLMs are increasingly used to help with real-life goals or tasks that take a long time to complete, involving multiple sessions across days, weeks, months, or even years. Thus to enable conversational systems for long term interactions and tasks, we need language-based agents that can plan for long horizons. Traditionally, such capabilities were addressed by reinforcement learning agents with hierarchical planning capabilities. In this work, we explore a novel architecture where the LLM acts as the meta-controller deciding the agent's next macro-action, and tool use augmented LLM-based option policies execute the selected macro-action. We instantiate this framework for a specific set of macro-actions enabling adaptive planning for users' personal plans through conversation and follow-up questions collecting user feedback. We show how this paradigm can be applicable in scenarios ranging from tutoring for academic and non-academic tasks to conversational coaching for personal health plans.

[Arxiv](https://arxiv.org/abs/2502.19500)