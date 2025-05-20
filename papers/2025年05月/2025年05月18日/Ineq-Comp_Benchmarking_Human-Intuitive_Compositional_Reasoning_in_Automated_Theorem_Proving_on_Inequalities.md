# # **Ineq-Comp：评估人类直观的组合推理在不等式自动定理证明中的基准**

发布时间：2025年05月18日

`LLM应用` `人工智能`

> Ineq-Comp: Benchmarking Human-Intuitive Compositional Reasoning in Automated Theorem Proving on Inequalities

# 摘要

> 基于LLM的正式证明助手（如Lean）在自动化数学发现方面展现出巨大潜力。但除了语义正确性，这些系统是否真正像人类一样理解数学结构？我们通过数学不等式这一跨领域重要工具来探讨这一问题。尽管现代证明器能够解决基础不等式问题，但我们深入探究了它们在处理人类直观组合性方面的表现。我们引入了Ineq-Comp基准测试，通过系统性变换构建而成，包括变量复制、代数重写和多步组合等操作。虽然这些问题对人类来说仍然简单，但实验结果显示大多数证明器（包括Goedel、STP和Kimina-7B）都面临显著挑战。DeepSeek-Prover-V2-7B则表现相对稳健——可能得益于其训练过程中将问题分解为子问题的能力——但仍出现了20%的性能下降（pass@32）。令人惊讶的是，即使在上下文中提供了组成部分的正式证明，所有模型的表现仍然不尽如人意，这表明其薄弱环节确实源于组合推理能力。我们的研究结果揭示了当前AI证明器与人类数学直觉之间的持久差距。


> LLM-based formal proof assistants (e.g., in Lean) hold great promise for automating mathematical discovery. But beyond syntactic correctness, do these systems truly understand mathematical structure as humans do? We investigate this question through the lens of mathematical inequalities -- a fundamental tool across many domains. While modern provers can solve basic inequalities, we probe their ability to handle human-intuitive compositionality. We introduce Ineq-Comp, a benchmark built from elementary inequalities through systematic transformations, including variable duplication, algebraic rewriting, and multi-step composition. Although these problems remain easy for humans, we find that most provers -- including Goedel, STP, and Kimina-7B -- struggle significantly. DeepSeek-Prover-V2-7B shows relative robustness -- possibly because it is trained to decompose the problems into sub-problems -- but still suffers a 20\% performance drop (pass@32). Strikingly, performance remains poor for all models even when formal proofs of the constituent parts are provided in context, revealing that the source of weakness is indeed in compositional reasoning. Our results expose a persisting gap between the generalization behavior of current AI provers and human mathematical intuition.

[Arxiv](https://arxiv.org/abs/2505.12680)