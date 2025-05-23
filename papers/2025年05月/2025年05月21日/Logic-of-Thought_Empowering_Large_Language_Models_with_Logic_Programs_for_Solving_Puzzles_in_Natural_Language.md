# # **思维逻辑：助力大型语言模型借助逻辑程序解决自然语言谜题**

发布时间：2025年05月21日

`LLM应用` `逻辑推理` `谜题解决`

> Logic-of-Thought: Empowering Large Language Models with Logic Programs for Solving Puzzles in Natural Language

# 摘要

> 在自然语言中解决谜题一直是人工智能领域的一个长期难题。尽管大型语言模型（LLMs）在多种任务中表现优异，但面对需要精确推理和穷举搜索的复杂谜题时，它们仍然力不从心。本文中，我们提出了“逻辑思维框架”（Logot），这一创新性方法将大型语言模型与逻辑编程相结合，为解决这一难题提供了全新思路。我们的方法通过大型语言模型将谜题规则和状态转换为答案集程序（ASP），再借助ASP解释器进行准确高效的求解。这种结合了大型语言模型自然语言理解能力和逻辑程序精确推理能力的混合方法，在实验中针对各种网格谜题和涉及动作的动态谜题均达到了几乎完美的准确率。我们的代码和数据已公开，访问地址为：https://github.com/naiqili/Logic-of-Thought。

> Solving puzzles in natural language poses a long-standing challenge in AI. While large language models (LLMs) have recently shown impressive capabilities in a variety of tasks, they continue to struggle with complex puzzles that demand precise reasoning and exhaustive search. In this paper, we propose Logic-of-Thought (Logot), a novel framework that bridges LLMs with logic programming to address this problem. Our method leverages LLMs to translate puzzle rules and states into answer set programs (ASPs), the solution of which are then accurately and efficiently inferred by an ASP interpreter. This hybrid approach combines the natural language understanding of LLMs with the precise reasoning capabilities of logic programs. We evaluate our method on various grid puzzles and dynamic puzzles involving actions, demonstrating near-perfect accuracy across all tasks. Our code and data are available at: https://github.com/naiqili/Logic-of-Thought.

[Arxiv](https://arxiv.org/abs/2505.16114)