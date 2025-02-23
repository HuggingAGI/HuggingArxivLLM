# LLM 代理正在打造代理工具

发布时间：2025年02月17日

`Agent` `软件工程`

> LLM Agents Making Agent Tools

# 摘要

> 工具的使用使大型语言模型 (LLMs) 成为能够执行复杂多步骤任务的强大智能体，它们通过动态调用外部软件组件实现这一点。然而，这些工具必须由人类开发人员预先实现，这限制了 LLM 智能体在需要大量高度专业化工具的领域（如生命科学和医学）中的应用。受科学研究日益伴随之公共代码仓库这一趋势的启发，我们提出了一种全新的智能体框架 ToolMaker，它可以自主地将附带代码的论文转化为与 LLM 兼容的工具。给定一个简短的任务描述和一个仓库 URL，ToolMaker 自主安装所需的依赖项并生成代码来执行任务，利用闭环自我修正机制来迭代诊断和纠正错误。为了评估我们的方法，我们引入了一个基准测试，其中包括 15 个多样且复杂的计算任务，涵盖医学和非医学领域，并提供了超过 100 个单元测试，以客观评估工具的正确性和鲁棒性。ToolMaker 正确实现了 80% 的任务，显著优于当前最先进的软件工程智能体。因此，ToolMaker 是实现完全自主的基于智能体的科学工作流程的重要一步。

> Tool use has turned large language models (LLMs) into powerful agents that can perform complex multi-step tasks by dynamically utilising external software components. However, these tools must be implemented in advance by human developers, hindering the applicability of LLM agents in domains which demand large numbers of highly specialised tools, like in life sciences and medicine. Motivated by the growing trend of scientific studies accompanied by public code repositories, we propose ToolMaker, a novel agentic framework that autonomously transforms papers with code into LLM-compatible tools. Given a short task description and a repository URL, ToolMaker autonomously installs required dependencies and generates code to perform the task, using a closed-loop self-correction mechanism to iteratively diagnose and rectify errors. To evaluate our approach, we introduce a benchmark comprising 15 diverse and complex computational tasks spanning both medical and non-medical domains with over 100 unit tests to objectively assess tool correctness and robustness. ToolMaker correctly implements 80% of the tasks, substantially outperforming current state-of-the-art software engineering agents. ToolMaker therefore is a step towards fully autonomous agent-based scientific workflows.

[Arxiv](https://arxiv.org/abs/2502.11705)