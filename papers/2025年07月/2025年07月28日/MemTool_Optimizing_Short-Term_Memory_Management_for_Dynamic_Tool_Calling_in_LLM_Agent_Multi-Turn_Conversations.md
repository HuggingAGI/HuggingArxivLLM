# MemTool：优化大型语言模型智能体在多轮对话中的动态工具调用短期记忆管理

发布时间：2025年07月28日

`Agent` `对话系统` `人工智能`

> MemTool: Optimizing Short-Term Memory Management for Dynamic Tool Calling in LLM Agent Multi-Turn Conversations

# 摘要

> 大型语言模型（LLM）代理展现了强大的自主能力，能够动态搜索和整合相关工具或模型上下文协议（MCP）服务器，但固定上下文窗口限制了其在多轮对话中独立重复使用工具的效果。为此，我们提出MemTool——一种短期记忆框架，使LLM代理能够在多轮对话中动态管理工具或MCP服务器的上下文。MemTool 提供三种智能架构：1）自主代理模式，赋予完整的工具管理自主权；2）工作流模式，提供无自主权的确定性控制；3）混合模式，结合自主和确定性控制。我们在ScaleMCP基准测试中对13种以上LLM进行了MemTool各模式的评估，进行了100次连续用户交互实验，测量工具移除率（短期记忆效率）和任务完成准确性。在自主代理模式下，具备推理能力的LLM实现了高工具移除效率（3窗口平均90-94%），而中型规模模型效率显著较低（0-60%）。工作流和混合模式在工具移除管理上表现一致，而自主和混合模式在任务完成上更为出色。我们根据任务准确性、自主性和模型能力，分析了各MemTool模式的权衡并提出了建议。

> Large Language Model (LLM) agents have shown significant autonomous capabilities in dynamically searching and incorporating relevant tools or Model Context Protocol (MCP) servers for individual queries. However, fixed context windows limit effectiveness in multi-turn interactions requiring repeated, independent tool usage. We introduce MemTool, a short-term memory framework enabling LLM agents to dynamically manage tools or MCP server contexts across multi-turn conversations. MemTool offers three agentic architectures: 1) Autonomous Agent Mode, granting full tool management autonomy, 2) Workflow Mode, providing deterministic control without autonomy, and 3) Hybrid Mode, combining autonomous and deterministic control. Evaluating each MemTool mode across 13+ LLMs on the ScaleMCP benchmark, we conducted experiments over 100 consecutive user interactions, measuring tool removal ratios (short-term memory efficiency) and task completion accuracy. In Autonomous Agent Mode, reasoning LLMs achieve high tool-removal efficiency (90-94% over a 3-window average), while medium-sized models exhibit significantly lower efficiency (0-60%). Workflow and Hybrid modes consistently manage tool removal effectively, whereas Autonomous and Hybrid modes excel at task completion. We present trade-offs and recommendations for each MemTool mode based on task accuracy, agency, and model capabilities.

[Arxiv](https://arxiv.org/abs/2507.21428)