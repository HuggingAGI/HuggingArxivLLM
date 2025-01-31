# 深入分析大型语言模型代码执行推理的工具

发布时间：2025年01月30日

`LLM应用

理由：这篇论文主要讨论了如何通过工具和启发式方法来分析代码执行推理结果，以帮助理解基准测试中代码属性对推理的影响。这涉及到LLM在编程能力评估中的应用，特别是代码执行推理方面。因此，这篇论文属于LLM应用的范畴。` `软件开发` `人工智能`

> A Tool for In-depth Analysis of Code Execution Reasoning of Large Language Models

# 摘要

> 代码执行推理正成为评估LLMs编程能力的新指标。现有框架（如CodeMind或REval）和基准测试（如CruxEval）通常聚焦于LLM对代码输入/输出或中间变量状态的预测，但仅限于少量程序。目前缺乏深入分析结果的工具，导致LLM代码执行推理的观察难以推广到更多数据集，阻碍了下一代LLMs的开发。本文推出ExeRScope，这是一套工具和启发式方法，用于分析代码执行推理结果，帮助理解基准测试中代码属性对推理的影响。借助这些工具，分析可推广到相似属性的代码，无需设计更多繁琐的基准测试。

> Code Executing Reasoning is becoming a new non-functional metric that assesses the ability of large language models (LLMs) in programming tasks. State-of-the-art frameworks (CodeMind or REval) and benchmarks (CruxEval) usually focus on LLM's prediction of a given code's input/output or intermediate variable states/values on limited programs. However, there is no tool for more in-depth analysis of the results. Without such a tool, the observations about LLM's code execution reasoning cannot be generalized to more datasets, preventing the research community and practitioners from devising the next generation of LLMs with better code execution reasoning abilities. This paper introduces ExeRScope, a series of tools and heuristics to analyze the result of code execution reasoning frameworks to understand better the impact of code properties in the studied benchmarks on the code execution reasoning. With such tooling, analysis can be generalized to code with similar properties without the urgent need to design more benchmarks, which is a cumbersome effort.

[Arxiv](https://arxiv.org/abs/2501.18482)