# SWE-MERA：动态评估大型语言模型在软件工程任务中的智能基准测试工具

发布时间：2025年07月15日

`LLM应用` `软件工程`

> SWE-MERA: A Dynamic Benchmark for Agenticly Evaluating Large Language Models on Software Engineering Tasks

# 摘要

> 大型语言模型（LLMs）在软件工程中的快速发展揭示了现有基准的关键局限性，尤其是广泛使用的SWE-bench数据集。近期研究表明，该数据集存在严重问题，例如32.67%的成功补丁涉及直接解决方案泄露，31.08%的通过案例是由于测试用例不足。为此，我们引入了SWE-MERA，这是一个动态、持续更新的基准，通过自动化收集真实世界的GitHub问题和严格的质量验证来解决这些根本性挑战。我们的方法实施了一个可靠的管道，在确保质量的同时最大限度地降低污染风险。目前，我们生成了约10,000个潜在任务，其中300个样本可供使用。使用Aider编码代理进行的评估展示了在最先进的模型中强大的区分能力。我们在2024年9月至2025年6月期间收集的任务上对十几个近期LLM进行了评估，并报告了其性能表现。


> The rapid advancement of Large Language Models (LLMs) in software engineering has revealed critical limitations in existing benchmarks, particularly the widely used SWE-bench dataset. Recent studies have uncovered severe data contamination issues, e.g. SWE-bench reports 32.67% of successful patches involve direct solution leakage and 31.08\% pass due to inadequate test cases. We introduce SWE-MERA, a dynamic, continuously updated benchmark designed to address these fundamental challenges through an automated collection of real-world GitHub issues and rigorous quality validation. Our approach implements a reliable pipeline that ensures quality while minimizing contamination risks, resulting in approximately 10,000 potential tasks with 300 samples currently available. Evaluation using the Aider coding agent demonstrates strong discriminative power in state-of-the-art models. We report performance across a dozen recent LLMs evaluated on tasks collected between September 2024 and June 2025.

[Arxiv](https://arxiv.org/abs/2507.11059)