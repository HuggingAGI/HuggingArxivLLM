# 优化胜于生成：借助人工提交信息优化提交信息

发布时间：2025年01月16日

`LLM应用

理由：这篇论文讨论了如何利用大型语言模型（LLMs）和搜索优化技术来优化提交信息（Commit Message Optimization, CMO）。具体来说，它结合了LLMs和外部反馈来增强人工编写的提交信息，从而提高信息的理性、全面性和表达性。这属于LLM在实际软件开发中的应用，因此归类为LLM应用。` `软件开发`

> Optimization is Better than Generation: Optimizing Commit Message Leveraging Human-written Commit Message

# 摘要

> 提交信息在软件开发中扮演着关键角色，不仅支持维护任务，还促进了开发者之间的沟通。尽管大型语言模型（LLMs）已通过多种软件上下文推动了提交信息生成（CMG）的进步，但开发者所关注的一些上下文往往被CMG技术忽视，且难以通过自动化工具检索。为此，我们提出了提交信息优化（CMO），它结合LLMs和搜索优化技术，对人工编写的提交信息进行增强。CMO从人工编写的提交信息出发，通过整合关键上下文和外部反馈，逐步优化信息内容。我们的评估结果显示，CMO生成的提交信息在理性、全面性和表达性上显著优于现有CMG方法和人工编写的提交信息，88.2%-95.4%的情况下表现更佳。

> Commit messages are crucial in software development, supporting maintenance tasks and communication among developers. While Large Language Models (LLMs) have advanced Commit Message Generation (CMG) using various software contexts, some contexts developers consider are often missed by CMG techniques and can't be easily retrieved or even retrieved at all by automated tools. To address this, we propose Commit Message Optimization (CMO), which enhances human-written messages by leveraging LLMs and search-based optimization. CMO starts with human-written messages and iteratively improves them by integrating key contexts and feedback from external evaluators. Our extensive evaluation shows CMO generates commit messages that are significantly more Rational, Comprehensive, and Expressive while outperforming state-of-the-art CMG methods and human messages 88.2%-95.4% of the time.

[Arxiv](https://arxiv.org/abs/2501.09861)