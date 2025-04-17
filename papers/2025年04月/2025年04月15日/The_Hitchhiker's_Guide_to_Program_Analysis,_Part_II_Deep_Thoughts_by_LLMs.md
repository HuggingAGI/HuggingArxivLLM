# # 程序分析漫游指南，第二部：LLMs 的深度思考之旅

发布时间：2025年04月15日

`LLM应用

理由：这篇论文主要探讨了大型语言模型（LLMs）在静态分析中的应用，特别是在提升软件漏洞检测的精度方面。通过引入BugLens框架，论文展示了如何利用LLMs来增强传统静态分析工具的效果，属于LLM在实际应用中的具体案例。因此，分类为LLM应用。` `软件工程`

> The Hitchhiker's Guide to Program Analysis, Part II: Deep Thoughts by LLMs

# 摘要

> 静态分析是软件漏洞检测的重要基石，但常常在精度与可扩展性之间难以平衡。在大型代码库如Linux内核中，这类工具往往产生较高的误报率。这种不精确性源于对漏洞的简化建模和对路径及数据约束的过度近似。尽管大型语言模型（LLMs）在代码理解方面展现出潜力，但直接应用于程序分析会导致不可靠的结果，原因在于其内在的推理局限性。我们引入了BugLens，一个显著提升静态分析精度的后精炼框架。通过评估漏洞代码模式的安全影响并验证与静态警告相关的约束条件，BugLens引导LLM遵循传统的分析步骤。在真实世界的Linux内核漏洞上进行评估，BugLens将精度从0.10（原始）和0.50（半自动精炼）提升至0.72，大幅降低了误报率，并揭示了四个此前未报告的漏洞。我们的结果表明，基于LLM的结构化工作流能够显著增强静态分析工具的有效性。

> Static analysis is a cornerstone for software vulnerability detection, yet it often struggles with the classic precision-scalability trade-off. In practice, such tools often produce high false positive rates, particularly in large codebases like the Linux kernel. This imprecision can arise from simplified vulnerability modeling and over-approximation of path and data constraints. While large language models (LLMs) show promise in code understanding, their naive application to program analysis yields unreliable results due to inherent reasoning limitations. We introduce BugLens, a post-refinement framework that significantly improves static analysis precision. BugLens guides an LLM to follow traditional analysis steps by assessing buggy code patterns for security impact and validating the constraints associated with static warnings. Evaluated on real-world Linux kernel bugs, BugLens raises precision from 0.10 (raw) and 0.50 (semi-automated refinement) to 0.72, substantially reducing false positives and revealing four previously unreported vulnerabilities. Our results suggest that a structured LLM-based workflow can meaningfully enhance the effectiveness of static analysis tools.

[Arxiv](https://arxiv.org/abs/2504.11711)