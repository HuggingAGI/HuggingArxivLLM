# 基于小型语言模型的代码生成：对 Codeforces 的深入分析

发布时间：2025年04月09日

`LLM应用` `代码生成` `编程竞赛`

> Code Generation with Small Language Models: A Deep Evaluation on Codeforces

# 摘要

> 大型语言模型（LLMs）在代码生成方面展现出了强大的能力，有望显著提升开发者的生产力。然而，由于计算成本高昂、能源需求巨大以及数据泄露和对抗攻击等安全风险，LLMs 的广泛应用仍然受到限制。作为一种轻量级的替代方案，小型语言模型（SLMs）凭借更快的推理速度、更低的部署开销以及在特定领域的出色适应性，成为现实世界应用中一个颇具吸引力的选择。

尽管此前的研究对 LLMs 在竞技编程任务上的表现进行了基准测试，但这些评估往往过于关注 Elo 分数或通过率等指标，忽视了对模型行为、失败模式和问题多样性的深入洞察。此外，SLMs 在处理复杂任务（如竞技编程）方面的潜力尚未得到充分探索。在本研究中，我们对五个开源的 SLM 进行了基准测试，包括 LLAMA 3.2 3B、GEMMA 2 9B、GEMMA 3 12B、DEEPSEEK-R1 14B 和 PHI-4 14B，测试范围涵盖了 Codeforces 平台上 280 个难度从 Elo 800 到 2100 不等、涉及 36 个不同主题的编程问题。

所有模型的任务都是生成 Python 解决方案。在 SLM 中，PHI-4 14B 表现最佳，其通过率@3 达到了 63.6%，接近专有的 O3-MINI-HIGH（86.8%）。此外，我们还对 PHI-4 14B 在 C++ 上进行了评估，发现结合 Python 和 C++ 的输出可以将其聚合通过率@3 提高到 73.6%。对 PHI-4 14B 错误输出的定性分析表明，部分失败是由于实现上的小问题（例如处理边界情况或修正变量初始化）引起的，而不是深层次的推理错误。


> Large Language Models (LLMs) have demonstrated capabilities in code generation, potentially boosting developer productivity. However, their widespread adoption remains limited by high computational costs, significant energy demands, and security risks such as data leakage and adversarial attacks. As a lighter-weight alternative, Small Language Models (SLMs) offer faster inference, lower deployment overhead, and better adaptability to domain-specific tasks, making them an attractive option for real-world applications. While prior research has benchmarked LLMs on competitive programming tasks, such evaluations often focus narrowly on metrics like Elo scores or pass rates, overlooking deeper insights into model behavior, failure patterns, and problem diversity. Furthermore, the potential of SLMs to tackle complex tasks such as competitive programming remains underexplored. In this study, we benchmark five open SLMs - LLAMA 3.2 3B, GEMMA 2 9B, GEMMA 3 12B, DEEPSEEK-R1 14B, and PHI-4 14B - across 280 Codeforces problems spanning Elo ratings from 800 to 2100 and covering 36 distinct topics. All models were tasked with generating Python solutions. PHI-4 14B achieved the best performance among SLMs, with a pass@3 of 63.6%, approaching the proprietary O3-MINI-HIGH (86.8%). In addition, we evaluated PHI-4 14B on C++ and found that combining outputs from both Python and C++ increases its aggregated pass@3 to 73.6%. A qualitative analysis of PHI-4 14B's incorrect outputs revealed that some failures were due to minor implementation issues - such as handling edge cases or correcting variable initialization - rather than deeper reasoning flaws.

[Arxiv](https://arxiv.org/abs/2504.07343)