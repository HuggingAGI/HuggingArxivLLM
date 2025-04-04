# LearNAT: 针对大型语言模型的自然语言到SQL转换任务，采用基于抽象语法树的任务分解方法进行学习

发布时间：2025年04月03日

`LLM应用` `数据库` `人工智能`

> LearNAT: Learning NL2SQL with AST-guided Task Decomposition for Large Language Models

# 摘要

> 自然语言到SQL（NL2SQL）是实现与数据库无缝交互的关键任务。大型语言模型（LLMs）在这一领域取得了显著进展，但现有方法主要依赖闭源模型和提示工程，开源模型通常需要微调以获取特定领域知识。然而，开源LLMs在处理复杂NL2SQL任务时仍面临挑战，这主要源于用户查询目标的间接表达以及用户查询与数据库模式之间的语义差距。受强化学习在数学问题求解中鼓励逐步推理的启发，我们提出了LearNAT（基于AST引导的任务分解学习NL2SQL），这是一种通过任务分解和强化学习提升开源LLMs在复杂NL2SQL任务上性能的新颖框架。LearNAT引入了三个关键组件：(1) 基于抽象语法树（ASTs）引导任务分解的高效搜索和剪枝策略的分解综合过程，(2) 基于DPO并通过AST边界实现细粒度步骤级优化的边界感知强化学习，以及(3) 动态选择相关示例以增强分解能力的自适应演示推理机制。在Spider和BIRD两个基准数据集上的大量实验表明，LearNAT使一个70亿参数的开源LLM能够达到与GPT-4相当的性能，同时提升了效率和可访问性。

> Natural Language to SQL (NL2SQL) has emerged as a critical task for enabling seamless interaction with databases. Recent advancements in Large Language Models (LLMs) have demonstrated remarkable performance in this domain. However, existing NL2SQL methods predominantly rely on closed-source LLMs leveraging prompt engineering, while open-source models typically require fine-tuning to acquire domain-specific knowledge. Despite these efforts, open-source LLMs struggle with complex NL2SQL tasks due to the indirect expression of user query objectives and the semantic gap between user queries and database schemas. Inspired by the application of reinforcement learning in mathematical problem-solving to encourage step-by-step reasoning in LLMs, we propose LearNAT (Learning NL2SQL with AST-guided Task Decomposition), a novel framework that improves the performance of open-source LLMs on complex NL2SQL tasks through task decomposition and reinforcement learning. LearNAT introduces three key components: (1) a Decomposition Synthesis Procedure that leverages Abstract Syntax Trees (ASTs) to guide efficient search and pruning strategies for task decomposition, (2) Margin-aware Reinforcement Learning, which employs fine-grained step-level optimization via DPO with AST margins, and (3) Adaptive Demonstration Reasoning, a mechanism for dynamically selecting relevant examples to enhance decomposition capabilities. Extensive experiments on two benchmark datasets, Spider and BIRD, demonstrate that LearNAT enables a 7B-parameter open-source LLM to achieve performance comparable to GPT-4, while offering improved efficiency and accessibility.

[Arxiv](https://arxiv.org/abs/2504.02327)