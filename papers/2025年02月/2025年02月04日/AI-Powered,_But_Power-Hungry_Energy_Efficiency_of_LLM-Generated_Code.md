# AI驱动，但能耗高吗？LLM生成代码的能源效率

发布时间：2025年02月04日

`LLM应用

**理由**：这篇论文主要研究的是大型语言模型（LLMs）在代码生成和补全任务中的应用，特别是对其生成代码的性能和能效进行评估。这属于LLM在实际应用中的表现和效果分析，因此归类为LLM应用。` `软件开发` `能效优化`

> AI-Powered, But Power-Hungry? Energy Efficiency of LLM-Generated Code

# 摘要

> 大型语言模型（LLMs）在软件开发中广泛应用于代码生成和补全等任务，但对其生成结果的评估往往只关注正确性，而忽略了性能和能效等关键因素。研究LLM生成代码的性能和能效，对于理解其在构建操作系统、服务器和移动应用等性能与能源敏感软件中的潜力至关重要。本文首次在Mac和PC两个平台上，利用Github Copilot、GPT-4o和OpenAI o1-mini三个前沿LLMs，对Python、Java和C++代码的能效和性能进行了分析，目标为LeetCode上的“困难”编程问题。结果显示，这些模型在生成Python和Java代码时表现更为出色。

> Large language models (LLMs) are used in software development to assist in various tasks, e.g., code generation and code completion, but empirical evaluations of the quality of the results produced by these models focus on correctness and ignore other relevant aspects, such as their performance and energy efficiency. Studying the performance of LLM-produced programs is essential to understand how well LLMs can support the construction of performance- and energy-critical software, such as operating systems, servers, and mobile applications. This paper presents the first study analyzing the energy efficiency and performance of LLM-generated code for three programming languages Python, Java, and C++, on two platforms, a Mac and a PC, leveraging three frontier LLMs, Github Copilot, GPT-4o, and the recently-released OpenAI o1-mini, and targeting ``hard'' programming problems from LeetCode. Our results show that the models are much more successful in generating Python and Java than C++ code.

[Arxiv](https://arxiv.org/abs/2502.02412)