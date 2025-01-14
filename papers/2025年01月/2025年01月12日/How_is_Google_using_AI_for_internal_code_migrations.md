# Google 如何利用 AI 进行内部代码迁移？

发布时间：2025年01月12日

`LLM应用

理由：这篇论文主要讨论了大型语言模型（LLMs）在软件工程中的应用，特别是代码迁移的实践经验。论文分享了Google使用LLMs进行代码迁移的实际案例，并强调了LLMs在缩短迁移时间和降低迁移难度方面的优势。因此，这篇论文属于LLM应用的范畴。` `软件工程` `代码迁移`

> How is Google using AI for internal code migrations?

# 摘要

> 近年来，生成式AI，尤其是大型语言模型（LLMs）在软件工程中的应用备受关注。目前已有多种商业化工具，许多大公司也开发了基于机器学习的专有工具供内部使用。尽管机器学习在代码补全等常见任务中的应用已相当普及，但人们对于将LLMs用于更定制化的场景，如代码迁移，兴趣日益浓厚。
    本文是Google使用LLMs进行代码迁移的经验分享。我们并未进行与其他方法的对比研究，也未验证假设，而是通过一系列企业级迁移案例，分享了基于LLM的代码迁移实践经验，旨在为行业从业者提供参考。这些经验同样适用于机器学习在软件工程中的其他应用。我们发现，使用LLMs可以大幅缩短迁移时间，并降低启动和完成迁移计划的难度。

> In recent years, there has been a tremendous interest in using generative AI, and particularly large language models (LLMs) in software engineering; indeed there are now several commercially available tools, and many large companies also have created proprietary ML-based tools for their own software engineers. While the use of ML for common tasks such as code completion is available in commodity tools, there is a growing interest in application of LLMs for more bespoke purposes. One such purpose is code migration.
  This article is an experience report on using LLMs for code migrations at Google. It is not a research study, in the sense that we do not carry out comparisons against other approaches or evaluate research questions/hypotheses. Rather, we share our experiences in applying LLM-based code migration in an enterprise context across a range of migration cases, in the hope that other industry practitioners will find our insights useful. Many of these learnings apply to any application of ML in software engineering. We see evidence that the use of LLMs can reduce the time needed for migrations significantly, and can reduce barriers to get started and complete migration programs.

[Arxiv](https://arxiv.org/abs/2501.06972)