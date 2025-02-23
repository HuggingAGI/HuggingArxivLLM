# STaR-SQL：文本到SQL的自我学习推理器

发布时间：2025年02月19日

`LLM应用` `数据库`

> STaR-SQL: Self-Taught Reasoner for Text-to-SQL

# 摘要

> 逐步生成链式思维推理步骤已被证明能有效提升大型语言模型在复杂推理任务中的表现。然而，将其应用于结构化任务如文本到SQL，仍然是一个未被充分探索的领域。本文介绍了一种全新的方法——文本到SQL的自教学推理器（STaR-SQL），它重新定义了SQL查询生成为一个推理驱动的过程。我们的方法通过提示大型语言模型生成SQL查询的详细推理步骤，并在正确结果的基础上对其进行微调。与传统方法不同，STaR-SQL在推理时额外分配计算资源，使大型语言模型成为自发的推理者，而不仅仅是基于提示的代理。为了进一步扩展推理过程，我们引入了一个基于结果监督的奖励模型（ORM）作为验证器，以提升SQL查询的准确性。在具有挑战性的Spider基准测试中，STaR-SQL实现了86.6%的执行准确率，显著超越了其他基线方法。这一成绩比几项基线方法高出31.6%，比直接预测答案的微调基线高出18.0%。此外，STaR-SQL还超越了利用更强大但不开源模型（如GPT-4）的代理式提示方法。这些发现凸显了推理增强训练在结构化任务中的潜力，并为将自我改进的推理模型扩展到文本到SQL生成及更广泛的领域打开了大门。

> Generating step-by-step "chain-of-thought" rationales has proven effective for improving the performance of large language models on complex reasoning tasks. However, applying such techniques to structured tasks, such as text-to-SQL, remains largely unexplored. In this paper, we introduce Self-Taught Reasoner for text-to-SQL (STaR-SQL), a novel approach that reframes SQL query generation as a reasoning-driven process. Our method prompts the LLM to produce detailed reasoning steps for SQL queries and fine-tunes it on rationales that lead to correct outcomes. Unlike traditional methods, STaR-SQL dedicates additional test-time computation to reasoning, thereby positioning LLMs as spontaneous reasoners rather than mere prompt-based agents. To further scale the inference process, we incorporate an outcome-supervised reward model (ORM) as a verifier, which enhances SQL query accuracy. Experimental results on the challenging Spider benchmark demonstrate that STaR-SQL significantly improves text-to-SQL performance, achieving an execution accuracy of 86.6%. This surpasses a few-shot baseline by 31.6% and a baseline fine-tuned to predict answers directly by 18.0%. Additionally, STaR-SQL outperforms agent-like prompting methods that leverage more powerful yet closed-source models such as GPT-4. These findings underscore the potential of reasoning-augmented training for structured tasks and open the door to extending self-improving reasoning models to text-to-SQL generation and beyond.

[Arxiv](https://arxiv.org/abs/2502.13550)