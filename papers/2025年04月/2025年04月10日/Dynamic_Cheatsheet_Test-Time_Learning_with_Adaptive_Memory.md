# # 动态备忘单：自适应记忆的测试时学习方法

发布时间：2025年04月10日

`LLM应用`

> Dynamic Cheatsheet: Test-Time Learning with Adaptive Memory

# 摘要

> 尽管当前语言模型（LMs）在复杂任务中表现出色，但它们通常处于信息孤岛中：每个输入查询独立处理，不保留之前尝试的见解。我们介绍的动态备忘录（DC）是一个轻量级框架，赋予黑箱语言模型持久且演进的记忆能力。DC让模型在推理时存储和复用积累的策略、代码片段和通用问题解决见解，避免反复重新发现或重复同样的解决方案和错误。这种推理时的学习显著提升了多种任务的性能，无需显式的地面真实标签或人工反馈。借助DC，Claude 3.5 Sonnet在AIME数学考试中的准确率在其开始跨问题保留代数见解后提升了超过一倍。GPT-4o在发现并复用一个基于Python的解决方案后，24点游戏的成功率从10%跃升至99%。在容易出现算术错误的任务中，如平衡方程，DC通过复用之前验证过的代码使GPT-4o和Claude达到近乎完美的准确率，而基线模型则停滞在50%左右。除了算术挑战，DC在知识密集型任务中也带来了显著的准确率提升。Claude在GPQA-Diamond问题上实现了9%的提升，在MMLU-Pro问题上提高了8%。DC的记忆是自我整理的，专注于简洁、可迁移的片段，而非整个转录。与微调或静态检索方法不同，DC能够动态适应语言模型的问题解决能力，无需修改其底层参数。总体而言，DC是一个有前景的方法，能够为语言模型赋予持久记忆，弥合孤立推理事件与人类认知中累积经验驱动学习之间的鸿沟。

> Despite their impressive performance on complex tasks, current language models (LMs) typically operate in a vacuum: Each input query is processed separately, without retaining insights from previous attempts. Here, we present Dynamic Cheatsheet (DC), a lightweight framework that endows a black-box LM with a persistent, evolving memory. Rather than repeatedly re-discovering or re-committing the same solutions and mistakes, DC enables models to store and reuse accumulated strategies, code snippets, and general problem-solving insights at inference time. This test-time learning enhances performance substantially across a range of tasks without needing explicit ground-truth labels or human feedback. Leveraging DC, Claude 3.5 Sonnet's accuracy more than doubled on AIME math exams once it began retaining algebraic insights across questions. Similarly, GPT-4o's success rate on Game of 24 increased from 10% to 99% after the model discovered and reused a Python-based solution. In tasks prone to arithmetic mistakes, such as balancing equations, DC enabled GPT-4o and Claude to reach near-perfect accuracy by recalling previously validated code, whereas their baselines stagnated around 50%. Beyond arithmetic challenges, DC yields notable accuracy gains on knowledge-demanding tasks. Claude achieved a 9% improvement in GPQA-Diamond and an 8% boost on MMLU-Pro problems. Crucially, DC's memory is self-curated, focusing on concise, transferable snippets rather than entire transcript. Unlike finetuning or static retrieval methods, DC adapts LMs' problem-solving skills on the fly, without modifying their underlying parameters. Overall, our findings present DC as a promising approach for augmenting LMs with persistent memory, bridging the divide between isolated inference events and the cumulative, experience-driven learning characteristic of human cognition.

[Arxiv](https://arxiv.org/abs/2504.07952)