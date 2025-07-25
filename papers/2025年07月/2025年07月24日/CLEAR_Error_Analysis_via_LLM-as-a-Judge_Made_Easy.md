# # CLEAR: 通过LLM作为裁判轻松实现错误分析
通过将大型语言模型（LLM）作为裁判进行错误分析变得轻松易行。

发布时间：2025年07月24日

`LLM应用` `知识图谱`

> CLEAR: Error Analysis via LLM-as-a-Judge Made Easy

# 摘要

> <翻译失败>

> The evaluation of Large Language Models (LLMs) increasingly relies on other LLMs acting as judges. However, current evaluation paradigms typically yield a single score or ranking, answering which model is better but not why. While essential for benchmarking, these top-level scores obscure the specific, actionable reasons behind a model's performance. To bridge this gap, we introduce CLEAR, an interactive, open-source package for LLM-based error analysis. CLEAR first generates per-instance textual feedback, then it creates a set of system-level error issues, and quantifies the prevalence of each identified issue. Our package also provides users with an interactive dashboard that allows for a comprehensive error analysis through aggregate visualizations, applies interactive filters to isolate specific issues or score ranges, and drills down to the individual instances that exemplify a particular behavioral pattern. We demonstrate CLEAR analysis for RAG and Math benchmarks, and showcase its utility through a user case study.

[Arxiv](https://arxiv.org/abs/2507.18392)