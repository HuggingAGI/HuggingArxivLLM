# 大型语言模型与代码安全：一篇系统性文献综述

发布时间：2024年12月19日

`LLM应用` `代码安全`

> Large Language Models and Code Security: A Systematic Literature Review

# 摘要

> 大型语言模型（LLMs）已然成为自动化各类编程任务（涵盖诸如检测和修复漏洞等安全相关任务）的有力工具。尽管它们能力出众，但在生成或修改既有代码时，LLMs 可能会引入程序员未曾察觉的漏洞。分析代码时，它们可能会遗漏明显漏洞，或者误报不存在的漏洞。在本次系统文献综述（SLR）中，我们旨在探究将 LLMs 用于各种代码相关任务的安全优势与潜在弊端。具体而言，首先我们聚焦于 LLMs 用于生成代码时可能引入的漏洞类型。其次，我们剖析 LLMs 在任意给定代码中检测和修复漏洞的能力，以及所选的提示策略如何影响其在这两项任务中的表现。最后，我们深入分析针对 LLMs 的数据投毒攻击会如何影响上述任务中的性能。

> Large Language Models (LLMs) have emerged as powerful tools for automating various programming tasks, including security-related ones, such as detecting and fixing vulnerabilities. Despite their promising capabilities, when required to produce or modify pre-existing code, LLMs could introduce vulnerabilities unbeknown to the programmer. When analyzing code, they could miss clear vulnerabilities or signal nonexistent ones. In this Systematic Literature Review (SLR), we aim to investigate both the security benefits and potential drawbacks of using LLMs for a variety of code-related tasks. In particular, first we focus on the types of vulnerabilities that could be introduced by LLMs, when used for producing code. Second, we analyze the capabilities of LLMs to detect and fix vulnerabilities, in any given code, and how the prompting strategy of choice impacts their performance in these two tasks. Last, we provide an in-depth analysis on how data poisoning attacks on LLMs can impact performance in the aforementioned tasks.

[Arxiv](https://arxiv.org/abs/2412.15004)