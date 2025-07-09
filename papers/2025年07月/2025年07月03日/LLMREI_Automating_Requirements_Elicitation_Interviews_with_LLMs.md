# LLMREI：利用大型语言模型（LLMs）自动进行需求提取访谈

发布时间：2025年07月03日

`LLM应用` `软件工程`

> LLMREI: Automating Requirements Elicitation Interviews with LLMs

# 摘要

> 需求采集访谈是收集系统需求的关键环节，但这类访谈耗时费力，容易受人为偏见影响，且沟通易出差错。大型语言模型的最新进展为自动化部分流程提供了新机遇。本研究推出 LLMREI，一款旨在最大限度减少人工干预、进行需求采集访谈的聊天机器人，旨在降低常见采访者错误并提升需求采集的可扩展性。我们主要探索了两种方法：zero-shot prompting 和 least-to-most prompting，以优化 LLMREI 的需求采集能力，并在 33 次模拟利益相关者采访中评估其性能。最初考虑的第三种方法是 fine-tuning，但因初步试验表现不佳而放弃。本研究评估了聊天机器人在三个方面的能力：减少常见采访错误、提取相关需求、以及根据采访上下文和用户回应调整提问。研究发现，LLMREI 的错误数量与人类采访者相当，能够提取大部分需求，并展现出生成高度情境相关问题的显著能力。我们预计 LLMREI 的最大优势在于能够自动化处理大量利益相关者的采访。


> Requirements elicitation interviews are crucial for gathering system requirements but heavily depend on skilled analysts, making them resource-intensive, susceptible to human biases, and prone to miscommunication. Recent advancements in Large Language Models present new opportunities for automating parts of this process. This study introduces LLMREI, a chat bot designed to conduct requirements elicitation interviews with minimal human intervention, aiming to reduce common interviewer errors and improve the scalability of requirements elicitation. We explored two main approaches, zero-shot prompting and least-to-most prompting, to optimize LLMREI for requirements elicitation and evaluated its performance in 33 simulated stakeholder interviews. A third approach, fine-tuning, was initially considered but abandoned due to poor performance in preliminary trials. Our study assesses the chat bot's effectiveness in three key areas: minimizing common interview errors, extracting relevant requirements, and adapting its questioning based on interview context and user responses. Our findings indicate that LLMREI makes a similar number of errors compared to human interviewers, is capable of extracting a large portion of requirements, and demonstrates a notable ability to generate highly context-dependent questions. We envision the greatest benefit of LLMREI in automating interviews with a large number of stakeholders.

[Arxiv](https://arxiv.org/abs/2507.02564)