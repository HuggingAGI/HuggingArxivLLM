# 代码生成评估的基准测试研究：基于变异的方法

发布时间：2025年05月11日

`LLM应用` `知识图谱`

> Benchmarking and Revisiting Code Generation Assessment: A Mutation-Based Approach

# 摘要

> <翻译失败>

> Code Large Language Models (CLLMs) have exhibited outstanding performance in program synthesis, attracting the focus of the research community. The evaluation of CLLM's program synthesis capability has generally relied on manually curated benchmarks. However, there is a substantial gap between real-world scenarios and benchmark settings. Existing benchmarks typically provide only a single input prompt for the evaluation of each synthesis problem. However, in practice, a problem can be described in various ways, including with typos, where developers may struggle to understand certain descriptions and seek clarification to find more suitable wording. Such various descriptions may lead to variations in the performance of CLLMs on the same question, resulting in a biased evaluation when using existing benchmarks. In this paper, we aim to explore these pitfalls with the goal of revisiting and enhancing future benchmark designs. To simulate real-world variations in problem descriptions, we propose 10 mutation strategies and introduce three new metrics to evaluate their impact on code generation. We then assess five popular CLLMs using 12,834 generated prompt variants, and found a significant performance discrepancy between the results from existing benchmarks and those from mutated benchmarks containing perturbations and variations. This finding underscores the need for more robust evaluation methods and benchmarks.

[Arxiv](https://arxiv.org/abs/2505.06880)