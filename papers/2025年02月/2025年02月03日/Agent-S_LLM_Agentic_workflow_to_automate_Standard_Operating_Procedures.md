# Agent-S：基于LLM的智能体工作流，实现标准操作程序的自动化

发布时间：2025年02月03日

`Agent

理由：这篇论文的重点在于设计和实现一个基于LLMs的智能体系统，用于自动化标准操作程序。论文详细描述了智能体的架构、工作流程以及在复杂现实任务中的应用，因此更适合归类到Agent类别。` `电子商务`

> Agent-S: LLM Agentic workflow to automate Standard Operating Procedures

# 摘要

> 基于大型语言模型（LLMs）的AI代理在解决复杂现实任务方面展现出巨大潜力。本文提出了一种基于LLMs的智能体工作流，用于自动化标准操作程序（SOP）。在客服领域，SOP为人工客服解决客户问题提供了逻辑性的分步指南。我们发现，SOP中的每一步骤均可归类为用户交互或API调用，而其逻辑流程则决定了导航路径。通过增强LLMs的记忆和环境（包括API工具、用户界面和外部知识来源），我们实现了SOP的自动化。我们的智能体架构包含三个特定任务的LLMs、全局动作仓库（GAR）、执行记忆和多个环境。SOP工作流以简洁的逻辑文本块形式编写。基于当前执行记忆和SOP，智能体选择要执行的动作；通过与适当环境（用户/API）交互收集观察结果和反馈，这些信息随后输入到记忆中以决定下一步动作。该智能体设计为容错型，能够动态决定重复某个动作或从外部知识源获取输入。我们在电子商务卖家领域的三个SOP上验证了所提智能体的效能，实验结果表明其在复杂现实场景中表现出色。

> AI agents using Large Language Models (LLMs) as foundations have shown promise in solving complex real-world tasks. In this paper, we propose an LLM-based agentic workflow for automating Standard Operating Procedures (SOP). For customer care operations, an SOP defines a logical step-by-step process for human agents to resolve customer issues. We observe that any step in the SOP can be categorized as user interaction or API call, while the logical flow in the SOP defines the navigation. We use LLMs augmented with memory and environments (API tools, user interface, external knowledge source) for SOP automation. Our agentic architecture consists of three task-specific LLMs, a Global Action Repository (GAR), execution memory, and multiple environments. SOP workflow is written as a simple logical block of text. Based on the current execution memory and the SOP, the agent chooses the action to execute; it interacts with an appropriate environment (user/API) to collect observations and feedback, which are, in turn, inputted to memory to decide the next action. The agent is designed to be fault-tolerant, where it dynamically decides to repeat an action or seek input from an external knowledge source. We demonstrate the efficacy of the proposed agent on the three SOPs from the e-commerce seller domain. The experimental results validate the agent's performance under complex real-world scenarios.

[Arxiv](https://arxiv.org/abs/2503.15520)