# 填补记忆空缺：借助 SQL 语法差异引导的大型语言模型来强化持续语义解析，无需真实数据重放

发布时间：2024年12月10日

`LLM应用` `数据库`

> Filling Memory Gaps: Enhancing Continual Semantic Parsing via SQL Syntax Variance-Guided LLMs without Real Data Replay

# 摘要

> 持续语义解析（CSP）旨在训练解析器，能在注释示例有限的任务中把自然语言问题转化为 SQL，以适应数据库动态更新的现实场景。此前的研究通过重放历史数据或采用参数高效调整（PET）来应对这一挑战，然而它们常常侵犯数据隐私或依赖理想的持续学习设定。为解决这些问题，我们提出了一种新的大型语言模型（LLM）增强型持续语义解析方法，名为 LECSP，它在鼓励泛化的同时减轻遗忘，无需真实数据重放或理想设定。具体而言，它首先从 SQL 语法角度分析任务间的共性和差异，指导 LLM 通过校准策略重建关键记忆并提高记忆准确性。接着，它运用任务感知的双教师蒸馏框架促进顺序训练过程中知识的积累和转移。在两个 CSP 基准测试中的实验结果显示，我们的方法显著优于现有方法，包括那些利用数据重放或理想设定的方法。此外，我们实现了超越上限的泛化性能，能更好地适应未见过的任务。

> Continual Semantic Parsing (CSP) aims to train parsers to convert natural language questions into SQL across tasks with limited annotated examples, adapting to the real-world scenario of dynamically updated databases. Previous studies mitigate this challenge by replaying historical data or employing parameter-efficient tuning (PET), but they often violate data privacy or rely on ideal continual learning settings. To address these problems, we propose a new Large Language Model (LLM)-Enhanced Continuous Semantic Parsing method, named LECSP, which alleviates forgetting while encouraging generalization, without requiring real data replay or ideal settings. Specifically, it first analyzes the commonalities and differences between tasks from the SQL syntax perspective to guide LLMs in reconstructing key memories and improving memory accuracy through a calibration strategy. Then, it uses a task-aware dual-teacher distillation framework to promote the accumulation and transfer of knowledge during sequential training. Experimental results on two CSP benchmarks show that our method significantly outperforms existing methods, even those utilizing data replay or ideal settings. Additionally, we achieve generalization performance beyond the upper limits, better adapting to unseen tasks.

[Arxiv](https://arxiv.org/abs/2412.07246)