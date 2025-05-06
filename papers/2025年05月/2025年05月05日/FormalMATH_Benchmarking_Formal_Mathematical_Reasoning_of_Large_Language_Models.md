# FormalMATH：评估大型语言模型的正式数学推理能力

发布时间：2025年05月05日

`LLM应用

理由：这篇论文主要探讨了如何利用大型语言模型（LLM）进行形式化数学推理，特别是通过开发一种人工智能辅助的形式化流水线来提升效率。它涉及LLM在特定任务中的应用，展示了其在数学推理中的使用和效果，属于LLM的应用层面。` `人工智能`

> FormalMATH: Benchmarking Formal Mathematical Reasoning of Large Language Models

# 摘要

> 形式化数学推理是人工智能领域的重要挑战，受限于现有基准的规模和范围限制。我们推出FormalMATH，一个基于Lean4的大规模基准数据集，包含涵盖高中奥数到大学定理的5,560个形式化验证问题，涉及代数、应用数学、微积分、数论和离散数学等多个领域。为提升效率，我们开发了一种人工智能辅助形式化流水线，整合了：(1) 专门用于自动形式化的大型语言模型，(2) 多模型语义验证，以及(3) 基于否定的反证过滤策略。该方法在人工验证前保留72.09%的陈述，有效降低了标注成本，同时保持与原问题的一致性。评估显示，现有模型在实际应用中仅16.46%的成功率，存在领域偏差和策略依赖问题。此外，我们在链式推理中发现，自然语言指导与证明成功率呈负相关，表明人类非正式推理可能增加噪音。FormalMATH为形式化数学推理提供了重要基准。


> Formal mathematical reasoning remains a critical challenge for artificial intelligence, hindered by limitations of existing benchmarks in scope and scale. To address this, we present FormalMATH, a large-scale Lean4 benchmark comprising 5,560 formally verified problems spanning from high-school Olympiad challenges to undergraduate-level theorems across diverse domains (e.g., algebra, applied mathematics, calculus, number theory, and discrete mathematics). To mitigate the inefficiency of manual formalization, we introduce a novel human-in-the-loop autoformalization pipeline that integrates: (1) specialized large language models (LLMs) for statement autoformalization, (2) multi-LLM semantic verification, and (3) negation-based disproof filtering strategies using off-the-shelf LLM-based provers. This approach reduces expert annotation costs by retaining 72.09% of statements before manual verification while ensuring fidelity to the original natural-language problems. Our evaluation of state-of-the-art LLM-based theorem provers reveals significant limitations: even the strongest models achieve only 16.46% success rate under practical sampling budgets, exhibiting pronounced domain bias (e.g., excelling in algebra but failing in calculus) and over-reliance on simplified automation tactics. Notably, we identify a counterintuitive inverse relationship between natural-language solution guidance and proof success in chain-of-thought reasoning scenarios, suggesting that human-written informal reasoning introduces noise rather than clarity in the formal reasoning settings. We believe that FormalMATH provides a robust benchmark for benchmarking formal mathematical reasoning.

[Arxiv](https://arxiv.org/abs/2505.02735)