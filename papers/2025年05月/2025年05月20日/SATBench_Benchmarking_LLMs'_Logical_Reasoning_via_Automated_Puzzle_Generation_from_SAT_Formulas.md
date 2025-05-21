# SATBench — 通过自动转换生成逻辑推理题对LLMs的逻辑推理能力进行评估基准

发布时间：2025年05月20日

`LLM理论` `逻辑推理` `人工智能`

> SATBench: Benchmarking LLMs' Logical Reasoning via Automated Puzzle Generation from SAT Formulas

# 摘要

> 我们推出 SATBench，一个通过源自布尔可满足性（SAT）问题的逻辑谜题来评测大型语言模型（LLMs）逻辑推理能力的基准。与以往专注于基于推理规则的逻辑推理不同，我们的方法利用了 SAT 问题的搜索本质，目标在于寻找满足特定逻辑约束的解决方案。SATBench 中的每个实例均源于 SAT 公式，再经由 LLMs 转化为故事情境与条件。生成过程全自动化，难度可通过调整子句数量灵活调节。所有 2100 个谜题均经过 LLM 辅助与基于求解器的一致性验证，部分还通过了人工审核。实验数据显示，即便是最强的 o4-mini 模型，在困难的 UNSAT 问题上也仅达 65.0% 的准确率，几乎与随机基线的 50% 相当。SATBench 揭示了当前 LLMs 在基于搜索的逻辑推理能力上的根本限制，同时为未来逻辑推理研究提供了可扩展的测试平台。

> We introduce SATBench, a benchmark for evaluating the logical reasoning capabilities of large language models (LLMs) through logical puzzles derived from Boolean satisfiability (SAT) problems. Unlike prior work that focuses on inference rule-based reasoning, which often involves deducing conclusions from a set of premises, our approach leverages the search-based nature of SAT problems, where the objective is to find a solution that fulfills a specified set of logical constraints. Each instance in SATBench is generated from a SAT formula, then translated into a story context and conditions using LLMs. The generation process is fully automated and allows for adjustable difficulty by varying the number of clauses. All 2100 puzzles are validated through both LLM-assisted and solver-based consistency checks, with human validation on a subset. Experimental results show that even the strongest model, o4-mini, achieves only 65.0% accuracy on hard UNSAT problems, close to the random baseline of 50%. SATBench exposes fundamental limitations in the search-based logical reasoning abilities of current LLMs and provides a scalable testbed for future research in logical reasoning.

[Arxiv](https://arxiv.org/abs/2505.14615)