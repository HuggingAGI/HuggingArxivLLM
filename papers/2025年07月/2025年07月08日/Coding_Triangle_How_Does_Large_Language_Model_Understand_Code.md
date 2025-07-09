# 编码三角形：探索大型语言模型如何理解代码

发布时间：2025年07月08日

`LLM应用` `软件开发`

> Coding Triangle: How Does Large Language Model Understand Code?

# 摘要

> 大型语言模型（LLMs）在代码生成领域取得了显著进展，但其真正的编程能力仍有待深入探索。我们提出了Code Triangle框架，系统地从编辑分析、代码实现和测试用例生成三个维度对LLMs进行评估。通过对竞争性编程基准的广泛实验，我们发现尽管LLMs在这些维度上能够形成自洽的系统，但其解决方案的多样性和鲁棒性仍逊色于人类程序员。我们发现模型认知与人类专业知识之间存在显著的分布差异，且由于训练数据偏差和有限的推理迁移能力，模型错误往往集中出现。我们的研究表明，通过整合人生成的编辑内容、解决方案以及多样化测试用例，并结合模型混合方法，可以显著提升LLMs的性能和鲁棒性。此外，我们揭示了LLMs认知中的一致性和不一致性，这可能有助于促进模型的自我反思与自我改进，为开发更强大的编码模型提供了潜在的研究方向。

> Large language models (LLMs) have achieved remarkable progress in code generation, yet their true programming competence remains underexplored. We introduce the Code Triangle framework, which systematically evaluates LLMs across three fundamental dimensions: editorial analysis, code implementation, and test case generation. Through extensive experiments on competitive programming benchmarks, we reveal that while LLMs can form a self-consistent system across these dimensions, their solutions often lack the diversity and robustness of human programmers. We identify a significant distribution shift between model cognition and human expertise, with model errors tending to cluster due to training data biases and limited reasoning transfer. Our study demonstrates that incorporating human-generated editorials, solutions, and diverse test cases, as well as leveraging model mixtures, can substantially enhance both the performance and robustness of LLMs. Furthermore, we reveal both the consistency and inconsistency in the cognition of LLMs that may facilitate self-reflection and self-improvement, providing a potential direction for developing more powerful coding models.

[Arxiv](https://arxiv.org/abs/2507.06138)