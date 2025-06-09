# 强化代码生成技术：通过基于执行的学习方法提升文本到SQL转换效果

发布时间：2025年06月06日

`LLM应用

理由：这篇论文探讨了大型语言模型 (LLM) 在代码生成任务中的应用，特别是从自然语言问题生成 SQL 查询。论文提出了一种创新的方法，通过强化学习调优来提升模型的性能，并展示了该方法在提升准确率方面的有效性。这属于 LLM 的具体应用领域。` `软件开发` `数据库管理`

> Reinforcing Code Generation: Improving Text-to-SQL with Execution-Based Learning

# 摘要

> # 摘要
本研究聚焦于大型语言模型 (LLM) 在代码生成任务中的应用，尤其是从自然语言问题生成 SQL 查询。我们提出了一种创新方法：不再依赖传统的文本-代码对进行监督微调，而是通过让模型与数据库引擎交互来进行强化学习调优。具体而言，我们将这一问题建模为一个强化学习问题，模型会从环境中获得基于执行的反馈，形式为标量奖励。这些奖励会对执行失败进行惩罚，并在查询返回正确答案时赋予正值。我们将在基于组的相对策略优化 (GRPO) 框架中使用这些奖励。通过一个表格推理基准测试，我们验证了这一方法的有效性。实验结果表明，仅使用以问题-答案对形式提供的弱监督信号，强化学习调优能够将模型生成 SQL 代码的准确率从 31.49% 提升至 49.83%，同时将错误率从 25.43% 降低至 14.71%。这一提升使模型的表现几乎与更大的 SQLCoder-70B 模型相媲美。我们的研究证明了利用基于执行的反馈来增强 LLM 符号推理能力的巨大潜力。

> In this work, we study the problem of code generation with a large language model (LLM), with a focus on generating SQL queries from natural language questions. We ask: Instead of using supervised fine tuning with text-code pairs, can we tune a model by having it interact with a database engine? We frame this problem as a reinforcement learning problem where the model receives execution-based feedback from the environment in the form of scalar rewards. These rewards penalize execution failures and assign positive values when a query returns a correct answer. We use the rewards within the Group Relative Policy Optimization (GRPO) framework. We use a tabular reasoning benchmark to test and evaluate our findings. We find that with only weak supervision in the form of question-answer pairs, RL-tuning improves the accuracy of model generated SQL code from 31.49 to 49.83 while reducing error percentage from 25.43% to 14.71%. This improvement allowed the model nearly match the performance performance to the larger SQLCoder-70B model. Our work demonstrates the potential of using execution-based feedback to improve symbolic reasoning capabilities of LLMs.

[Arxiv](https://arxiv.org/abs/2506.06093)