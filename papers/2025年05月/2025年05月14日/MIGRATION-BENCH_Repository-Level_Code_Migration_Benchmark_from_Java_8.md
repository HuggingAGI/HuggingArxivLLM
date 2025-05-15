# MIGRATION-BENCH: 代码迁移基准测试：基于 Java 8 的仓库级别代码迁移评测

发布时间：2025年05月14日

`LLM应用` `软件工程` `代码迁移`

> MIGRATION-BENCH: Repository-Level Code Migration Benchmark from Java 8

# 摘要

> 近年来，随着大型语言模型（LLMs）的迅猛发展，它们在软件工程领域的应用日益广泛，显著提升了生产效率和可扩展性。尽管已有众多基准数据集用于评估LLMs的编程能力，但这些数据集主要聚焦于问题解决和修复任务。为填补这一空白，我们推出了全新的编码基准测试MIGRATION-BENCH，专注于代码迁移这一独特领域。该基准测试旨在为从Java 8迁移到最新长期支持版本（Java 17、21）提供全面的评估工具，包含完整数据集和精选子集，分别涵盖5,102个和300个仓库。精选子集经过精心整理，代表了不同复杂度和难度的迁移任务，为代码迁移研究提供了灵活多样的资源支持。此外，我们还开发了一套全面的评估框架，以确保对LLMs在这一复杂任务上的评估既严格又标准化。我们进一步提出SD-Feedback方法，并通过实验验证，LLMs能够有效处理代码仓库级别的迁移任务。在精选子集上，使用Claude-3.5-Sonnet-v2时，SD-Feedback分别在最小迁移和最大迁移场景下实现了62.33%和27.00%的成功率（pass@1）。MIGRATION-BENCH的数据集和源代码现已开放，访问链接为：https://huggingface.co/collections/AmazonScience 和 https://github.com/amazon-science/self_debug。

> With the rapid advancement of powerful large language models (LLMs) in recent years, a wide range of software engineering tasks can now be addressed using LLMs, significantly enhancing productivity and scalability. Numerous benchmark datasets have been developed to evaluate the coding capabilities of these models, while they primarily focus on problem-solving and issue-resolution tasks. In contrast, we introduce a new coding benchmark MIGRATION-BENCH with a distinct focus: code migration. MIGRATION-BENCH aims to serve as a comprehensive benchmark for migration from Java 8 to the latest long-term support (LTS) versions (Java 17, 21), MIGRATION-BENCH includes a full dataset and its subset selected with $5,102$ and $300$ repositories respectively. Selected is a representative subset curated for complexity and difficulty, offering a versatile resource to support research in the field of code migration. Additionally, we provide a comprehensive evaluation framework to facilitate rigorous and standardized assessment of LLMs on this challenging task. We further propose SD-Feedback and demonstrate that LLMs can effectively tackle repository-level code migration to Java 17. For the selected subset with Claude-3.5-Sonnet-v2, SD-Feedback achieves 62.33% and 27.00% success rate (pass@1) for minimal and maximal migration respectively. The benchmark dataset and source code are available at: https://huggingface.co/collections/AmazonScience and https://github.com/amazon-science/self_debug respectively.

[Arxiv](https://arxiv.org/abs/2505.09569)