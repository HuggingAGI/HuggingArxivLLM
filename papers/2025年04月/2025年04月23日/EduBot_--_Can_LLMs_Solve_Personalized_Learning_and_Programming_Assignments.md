# EduBot——大型语言模型能否应对个性化学习与编程任务？

发布时间：2025年04月23日

`LLM应用` `软件开发`

> EduBot -- Can LLMs Solve Personalized Learning and Programming Assignments?

# 摘要

> 大型语言模型（LLMs）正在彻底改变代码编写的方式。通用型和代码型 LLMs 在一次性查询生成独立函数和代码补全任务方面表现出色。然而，面对需要递归请求和 bug 修复的综合性编程任务，它们的能力仍有待验证。本文提出了一种名为 EduBot 的智能自动化助手系统，结合概念知识教学、端到端代码开发、递归提示驱动的个性化编程以及基于 LLMs 的有限人工干预调试。通过递归自动提示驱动系统，EduBot 能够解决从概念性到编码性问题的复杂编程任务，无需对 LLMs 进行微调。为了评估 EduBot 的性能，我们设计了一个包含算法、机器学习和现实世界问题的 20 个场景的基准测试套件。结果显示，EduBot 可在 20 分钟内完成大部分场景。通过比较研究，我们采用不同 LLMs 作为核心，验证了 EduBot 在不同能力 LLMs 上的兼容性和鲁棒性。我们相信，EduBot 为探索预训练 LLMs 在多步推理和代码生成方面的潜力提供了一种新思路，尤其在结合知识学习和代码生成解决个性化任务方面。

> The prevalence of Large Language Models (LLMs) is revolutionizing the process of writing code. General and code LLMs have shown impressive performance in generating standalone functions and code-completion tasks with one-shot queries. However, the ability to solve comprehensive programming tasks with recursive requests and bug fixes remains questionable. In this paper, we propose EduBot, an intelligent automated assistant system that combines conceptual knowledge teaching, end-to-end code development, personalized programming through recursive prompt-driven methods, and debugging with limited human interventions powered by LLMs. We show that EduBot can solve complicated programming tasks consisting of sub-tasks with increasing difficulties ranging from conceptual to coding questions by recursive automatic prompt-driven systems without finetuning on LLMs themselves. To further evaluate EduBot's performance, we design and conduct a benchmark suite consisting of 20 scenarios in algorithms, machine learning, and real-world problems. The result shows that EduBot can complete most scenarios in less than 20 minutes. Based on the benchmark suites, we perform a comparative study to take different LLMs as the backbone and to verify EduBot's compatibility and robustness across LLMs with varying capabilities. We believe that EduBot is an exploratory approach to explore the potential of pre-trained LLMs in multi-step reasoning and code generation for solving personalized assignments with knowledge learning and code generation.

[Arxiv](https://arxiv.org/abs/2504.17824)