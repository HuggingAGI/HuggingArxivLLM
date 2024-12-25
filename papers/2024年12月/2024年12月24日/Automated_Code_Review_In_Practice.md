# 实践中的自动化代码审查

发布时间：2024年12月24日

`LLM应用` `软件开发` `代码审查`

> Automated Code Review In Practice

# 摘要

> 代码审查是一种广泛用于提升软件质量和传递知识的实践方式。但因其需要人工投入且可能存在延迟，所以常被认为耗时。诸如 Qodo、GitHub Copilot 以及 Coderabbit 等几款人工智能辅助工具，借助大型语言模型（LLMs）实现了自动审查。然而，这些工具在行业中的实际效果尚待考察。
  本研究探究了基于 LLM 的自动代码审查工具在工业环境中的影响。该研究在一个采用了人工智能辅助审查工具（基于开源的 Qodo PR Agent）的软件开发环境中开展。十个项目中约 238 名从业者能够使用该工具。我们重点关注了三个项目，其中有 4335 个拉取请求，1568 个接受了自动审查。数据收集涵盖三个来源：（1）对拉取请求数据的定量分析，包括显示开发人员是否对自动评论采取行动的评论标签；（2）向开发人员发送有关他们在单个拉取请求审查方面经验的调查；（3）对 22 名从业者的更广泛调查，以获取他们对自动审查的总体看法。
  73.8%的自动评论得以解决。然而，平均拉取请求关闭时间从 5 小时 52 分钟延长至 8 小时 20 分钟，不同项目的趋势各异。多数从业者表示，由于自动审查，代码质量有小幅提升。
  基于 LLM 的工具在软件开发中证明是有用的，增强了错误检测能力，提升了对代码质量的认知，并推动了最佳实践。不过，它也致使拉取请求关闭时间变长，并带来了诸如错误审查、不必要的更正以及不相关评论等弊端。

> Code review is a widespread practice to improve software quality and transfer knowledge. It is often seen as time-consuming due to the need for manual effort and potential delays. Several AI-assisted tools, such as Qodo, GitHub Copilot, and Coderabbit, provide automated reviews using large language models (LLMs). The effects of such tools in the industry are yet to be examined.
  This study examines the impact of LLM-based automated code review tools in an industrial setting. The study was conducted within a software development environment that adopted an AI-assisted review tool (based on open-source Qodo PR Agent). Around 238 practitioners across ten projects had access to the tool. We focused on three projects with 4,335 pull requests, 1,568 of which underwent automated reviews. Data collection comprised three sources: (1) a quantitative analysis of pull request data, including comment labels indicating whether developers acted on the automated comments, (2) surveys sent to developers regarding their experience with reviews on individual pull requests, and (3) a broader survey of 22 practitioners capturing their general opinions on automated reviews.
  73.8% of automated comments were resolved. However, the average pull request closure duration increased from five hours 52 minutes to eight hours 20 minutes, with varying trends across projects. Most practitioners reported a minor improvement in code quality due to automated reviews.
  The LLM-based tool proved useful in software development, enhancing bug detection, increasing awareness of code quality, and promoting best practices. However, it also led to longer pull request closure times and introduced drawbacks like faulty reviews, unnecessary corrections, and irrelevant comments.

[Arxiv](https://arxiv.org/abs/2412.18531)