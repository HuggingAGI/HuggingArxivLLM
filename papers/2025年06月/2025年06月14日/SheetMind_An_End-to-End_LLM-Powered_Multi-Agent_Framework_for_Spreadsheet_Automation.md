# SheetMind：一个LLM赋能的端到端多智能体框架，助力电子表格自动化

发布时间：2025年06月14日

`Agent` `电子表格` `自动化`

> SheetMind: An End-to-End LLM-Powered Multi-Agent Framework for Spreadsheet Automation

# 摘要

> 我们推出了一款名为 SheetMind 的模块化多智能体框架，它借助大型语言模型（LLMs）通过自然语言指令实现电子表格自动化。该系统由三个核心代理构成：管理代理负责将复杂的用户指令拆解为具体任务，行动代理利用 Backus-Naur 形式（BNF）语法将这些任务转化为结构化命令，而反思代理则确保生成的操作与用户原始意图保持一致。通过 Google Sheets 的工作区扩展，SheetMind 实现了无需脚本或公式知识的实时交互体验。在基准测试中，SheetMind 在单步任务中达到了80%的成功率，多步指令的成功率也保持在70%左右，显著超越了其他变体。这一成果充分证明了多智能体分解与基于语法的执行在连接自然语言与电子表格功能方面的卓越效果。

> We present SheetMind, a modular multi-agent framework powered by large language models (LLMs) for spreadsheet automation via natural language instructions. The system comprises three specialized agents: a Manager Agent that decomposes complex user instructions into subtasks; an Action Agent that translates these into structured commands using a Backus Naur Form (BNF) grammar; and a Reflection Agent that validates alignment between generated actions and the user's original intent. Integrated into Google Sheets via a Workspace extension, SheetMind supports real-time interaction without requiring scripting or formula knowledge. Experiments on benchmark datasets demonstrate an 80 percent success rate on single step tasks and approximately 70 percent on multi step instructions, outperforming ablated and baseline variants. Our results highlight the effectiveness of multi agent decomposition and grammar based execution for bridging natural language and spreadsheet functionalities.

[Arxiv](https://arxiv.org/abs/2506.12339)