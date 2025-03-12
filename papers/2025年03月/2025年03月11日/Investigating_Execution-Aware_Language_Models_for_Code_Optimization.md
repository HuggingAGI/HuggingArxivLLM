# 研究具有执行感知能力的语言模型在代码优化中的应用

发布时间：2025年03月11日

`LLM应用

理由：这篇论文探讨了将语言模型应用于代码优化，特别是通过整合代码执行信息来提升模型的优化能力。虽然它涉及了模型的改进和训练策略，但其核心目标是将语言模型应用于一个具体的任务（代码优化），因此更适合归类到LLM应用。` `软件工程` `人工智能`

> Investigating Execution-Aware Language Models for Code Optimization

# 摘要

> 代码优化是提升代码效率的关键环节，同时确保功能不受影响。这一过程需要深入理解代码在运行时的行为，以有效发现并解决低效问题。近期研究表明，语言模型在自动化代码优化方面潜力巨大。然而，这些模型往往缺乏对代码运行时行为的深刻理解。针对这一局限，研究者提出了将代码执行信息融入语言模型的策略。这些方法在提升模型在软件工程任务中的有效性方面初见成效。然而，尽管代码执行行为与效率密切相关，但这些策略对代码优化的具体影响仍待深入探索。本研究旨在探讨将代码执行信息整合到语言模型中如何影响其优化能力。具体而言，我们采用三种不同的训练策略，将行执行、行覆盖率、分支覆盖率和变量状态四个代码执行维度融入知名代码语言模型CodeT5+。研究结果表明，相较于标准CodeT5+模型，引入执行信息的模型在优化代码方面仅带来有限改进。

> Code optimization is the process of enhancing code efficiency, while preserving its intended functionality. This process often requires a deep understanding of the code execution behavior at run-time to identify and address inefficiencies effectively. Recent studies have shown that language models can play a significant role in automating code optimization. However, these models may have insufficient knowledge of how code execute at run-time. To address this limitation, researchers have developed strategies that integrate code execution information into language models. These strategies have shown promise, enhancing the effectiveness of language models in various software engineering tasks. However, despite the close relationship between code execution behavior and efficiency, the specific impact of these strategies on code optimization remains largely unexplored. This study investigates how incorporating code execution information into language models affects their ability to optimize code. Specifically, we apply three different training strategies to incorporate four code execution aspects -- line executions, line coverage, branch coverage, and variable states -- into CodeT5+, a well-known language model for code. Our results indicate that execution-aware models provide limited benefits compared to the standard CodeT5+ model in optimizing code.

[Arxiv](https://arxiv.org/abs/2503.08228)