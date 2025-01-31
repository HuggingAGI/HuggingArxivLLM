# RepoAudit: 一个自主的LLM代理，专为仓库级代码审计而生

发布时间：2025年01月30日

`Agent

理由：这篇论文介绍了一个自主的LLM代理RepoAudit，用于实现精确且高效的仓库级别代码审计。RepoAudit配备了代理记忆和验证器，能够按需探索代码仓库并分析数据流事实，以减轻幻觉和验证潜在错误路径。这些特征表明RepoAudit是一个具有自主性和记忆功能的代理系统，因此将其分类为Agent。` `软件开发` `代码审计`

> RepoAudit: An Autonomous LLM-Agent for Repository-Level Code Auditing

# 摘要

> 代码审计是一种旨在发现错误的代码审查过程。大型语言模型（LLMs）在这一任务中展现了巨大潜力，能够无需编译即可分析程序，并根据指定提示进行定制错误检测。然而，将LLMs应用于仓库级别的代码审计面临显著挑战。LLMs固有的上下文限制和幻觉可能导致错误报告质量低下，而软件仓库的大规模则带来了高昂的时间和令牌成本，影响了实际场景中的效率和可扩展性。
    本研究提出了一种自主的LLM代理RepoAudit，旨在实现精确且高效的仓库级别代码审计。RepoAudit配备了代理记忆，能够按需探索代码仓库，分析单个函数中不同可行程序路径的数据流事实。此外，RepoAudit引入了验证器，用于检查数据流事实以减轻幻觉，并验证潜在错误路径的路径条件的可满足性，从而在代码审计中有效排除误报。实验结果显示，由Claude 3.5 Sonnet驱动的RepoAudit在15个真实系统中成功发现了38个真实错误，平均每个项目耗时0.44小时，成本为2.54美元。

> Code auditing is a code review process with the goal of finding bugs. Large Language Models (LLMs) have shown substantial potential in this task, offering the ability to analyze programs without compilation and enabling customized bug detection following specified prompts. However, applying LLMs to repository-level code auditing presents notable challenges. The inherent context limits and hallucinations of LLMs can lead to the low quality of bug reports. Meanwhile, the large size of software repositories introduces substantial time and token costs, hindering efficiency and scalability in real-world scenarios.
  This work introduces an autonomous LLM-agent, RepoAudit, designed to enable precise and efficient repository-level code auditing. Equipped with the agent memory, RepoAudit explores the code repository on demand, analyzing data-flow facts along different feasible program paths in individual functions. It also introduces the validator to check the data-flow facts for hallucination mitigation and examine the satisfiability of path conditions of potential buggy paths, which enables RepoAudit to discard false positives in the code auditing. Our experiment shows that RepoAudit powered by Claude 3.5 Sonnet successfully finds 38 true bugs in 15 real-world systems, consuming 0.44 hours and $2.54 per project on average.

[Arxiv](https://arxiv.org/abs/2501.18160)