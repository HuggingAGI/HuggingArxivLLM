# 定义并检测基于大型语言模型的自主代理存在的缺陷

发布时间：2024年12月24日

`Agent` `AI 代理` `软件开发`

> Defining and Detecting the Defects of the Large Language Model-based Autonomous Agents

# 摘要

> AI 代理是能够感知环境、自主规划并执行任务的系统。LLM 的最新进展为 AI 代理带来了变革性的范式，使其能通过提示与外部资源和工具交互。在此类代理中，工作流将开发人员编写的用于管理框架构建和逻辑控制的代码，与 LLM 生成的能增强动态决策和交互的自然语言相融合。然而，开发人员实现的逻辑与 LLM 动态生成的内容在行为和预期结果上的差异，可能导致诸如工具调用失败和任务执行错误等缺陷。这些问题带来特定风险，致使基于 LLM 的 AI 代理出现各种缺陷，比如服务中断。尽管这些问题至关重要，但目前缺乏专注于分析基于 LLM 的 AI 代理以找出其代码缺陷的系统性工作。在本文中，我们开展了首个专注于识别和检测 LLM 代理缺陷的研究。我们从 StackOverflow 收集并分析了 6854 个相关帖子，定义了 8 种代理缺陷类型。对于每种类型，我们都给出了详细描述和示例。接着，我们设计了名为 Agentable 的静态分析工具来检测缺陷。Agentable 借助代码属性图和 LLM 来分析代理工作流，通过高效识别特定代码模式和分析自然语言描述来实现。为评估 Agentable，我们构建了两个数据集：AgentSet 由 84 个真实世界的代理组成，AgentTest 包含 78 个专门设计涵盖各种缺陷类型的代理。我们的结果显示，Agentable 的总体准确率达 88.79%，召回率达 91.03%。此外，我们的分析揭示了 AgentSet 存在 889 个缺陷，凸显了这些缺陷的普遍性。

> AI agents are systems capable of perceiving their environment, autonomously planning and executing tasks. Recent advancements in LLM have introduced a transformative paradigm for AI agents, enabling them to interact with external resources and tools through prompts. In such agents, the workflow integrates developer-written code, which manages framework construction and logic control, with LLM-generated natural language that enhances dynamic decision-making and interaction. However, discrepancies between developer-implemented logic and the dynamically generated content of LLMs in terms of behavior and expected outcomes can lead to defects, such as tool invocation failures and task execution errors. These issues introduce specific risks, leading to various defects in LLM-based AI Agents, such as service interruptions. Despite the importance of these issues, there is a lack of systematic work that focuses on analyzing LLM-based AI Agents to uncover defects in their code. In this paper, we present the first study focused on identifying and detecting defects in LLM Agents. We collected and analyzed 6,854 relevant posts from StackOverflow to define 8 types of agent defects. For each type, we provided detailed descriptions with an example. Then, we designed a static analysis tool, named Agentable, to detect the defects. Agentable leverages Code Property Graphs and LLMs to analyze Agent workflows by efficiently identifying specific code patterns and analyzing natural language descriptions. To evaluate Agentable, we constructed two datasets: AgentSet, consists of 84 real-world Agents, and AgentTest, which contains 78 Agents specifically designed to include various types of defects. Our results show that Agentable achieved an overall accuracy of 88.79% and a recall rate of 91.03%. Furthermore, our analysis reveals the 889 defects of the AgentSet, highlighting the prevalence of these defects.

[Arxiv](https://arxiv.org/abs/2412.18371)