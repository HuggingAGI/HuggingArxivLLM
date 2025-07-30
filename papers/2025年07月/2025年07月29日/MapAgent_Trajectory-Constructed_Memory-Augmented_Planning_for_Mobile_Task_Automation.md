# MapAgent：轨迹构建增强记忆规划，助力移动任务自动化

发布时间：2025年07月29日

`Agent` `移动应用` `自动化`

> MapAgent: Trajectory-Constructed Memory-Augmented Planning for Mobile Task Automation

# 摘要

> 由大型语言模型 (LLMs) 驱动的自主代理近期在移动端设备上通过图形用户界面 (GUI) 自动化任务方面展现出巨大潜力。尽管取得了一些初步进展，但这些代理在处理复杂的现实世界任务时仍面临诸多挑战。这些挑战源于基于 LLM 的代理对真实移动应用缺乏足够的了解，这可能导致任务规划低效，甚至产生幻觉。为解决这些问题，我们提出了一种名为 MapAgent 的全新 LLM 基础代理框架，该框架利用基于历史轨迹构建的记忆来增强当前的任务规划能力。

具体来说，MapAgent 框架包含三个核心组件：首先，我们提出了一种基于轨迹的记忆机制，能够将任务执行轨迹转化为可重用且结构化的页面记忆数据库。每个轨迹中的页面都会被提取为一个简洁而全面的快照，既包含其 UI 布局，也包含功能上下文。其次，我们引入了一种由粗到细的任务规划方法，通过相似性从记忆数据库中检索相关页面，并将其注入到 LLM 规划器中，以此弥补对现实世界应用情景理解的不足，从而实现更加知情且上下文感知的任务规划。最后，通过一个由双 LLM 架构支持的任务执行器，将规划好的任务转换为可执行的操作，确保任务进度的有效追踪。

在真实场景下的实验结果表明，MapAgent 的性能优于现有方法。该代码将开源以支持进一步研究。

> The recent advancement of autonomous agents powered by Large Language Models (LLMs) has demonstrated significant potential for automating tasks on mobile devices through graphical user interfaces (GUIs). Despite initial progress, these agents still face challenges when handling complex real-world tasks. These challenges arise from a lack of knowledge about real-life mobile applications in LLM-based agents, which may lead to ineffective task planning and even cause hallucinations. To address these challenges, we propose a novel LLM-based agent framework called MapAgent that leverages memory constructed from historical trajectories to augment current task planning. Specifically, we first propose a trajectory-based memory mechanism that transforms task execution trajectories into a reusable and structured page-memory database. Each page within a trajectory is extracted as a compact yet comprehensive snapshot, capturing both its UI layout and functional context. Secondly, we introduce a coarse-to-fine task planning approach that retrieves relevant pages from the memory database based on similarity and injects them into the LLM planner to compensate for potential deficiencies in understanding real-world app scenarios, thereby achieving more informed and context-aware task planning. Finally, planned tasks are transformed into executable actions through a task executor supported by a dual-LLM architecture, ensuring effective tracking of task progress. Experimental results in real-world scenarios demonstrate that MapAgent achieves superior performance to existing methods. The code will be open-sourced to support further research.

[Arxiv](https://arxiv.org/abs/2507.21953)