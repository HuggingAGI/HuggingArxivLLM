# # debug-gym：专为交互式调试设计的文本交互式调试环境

发布时间：2025年03月27日

`Agent` `软件工程` `人工智能`

> debug-gym: A Text-Based Environment for Interactive Debugging

# 摘要

> 大型语言模型 (LLMs) 在编码任务中越来越不可或缺，但现有方法通常假设所有相关信息都能在上下文中获取或与训练数据匹配。我们提出，LLMs 可通过与代码库进行交互式探索来收集相关任务信息而获益。为此，我们开发了名为 debug-gym 的文本环境，用于在交互式编码场景中训练基于 LLM 的智能体。该环境设计轻量化，并内置 Python 调试器 (pdb) 等实用工具，专为辅助 LLM 智能体的交互式调试而优化。除编码与调试外，此方法还可扩展至其他任何能从 LLM 代理主动探索行为中受益的任务场景。

> Large Language Models (LLMs) are increasingly relied upon for coding tasks, yet in most scenarios it is assumed that all relevant information can be either accessed in context or matches their training data. We posit that LLMs can benefit from the ability to interactively explore a codebase to gather the information relevant to their task. To achieve this, we present a textual environment, namely debug-gym, for developing LLM-based agents in an interactive coding setting. Our environment is lightweight and provides a preset of useful tools, such as a Python debugger (pdb), designed to facilitate an LLM-based agent's interactive debugging. Beyond coding and debugging tasks, this approach can be generalized to other tasks that would benefit from information-seeking behavior by an LLM agent.

[Arxiv](https://arxiv.org/abs/2503.21557)