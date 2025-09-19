# 面向高效MLLM评估的多对一访谈范式

发布时间：2025年09月18日

`LLM应用` `基础理论`

> A Multi-To-One Interview Paradigm for Efficient MLLM Evaluation

# 摘要

> 多模态大型语言模型（MLLMs）的飞速发展催生了大量基准测试。然而，传统的全覆盖问答评估存在冗余度高、效率低的问题。受人类面试流程的启发，我们提出了一种多对一面试范式，以实现对MLLM的高效评估。该框架包含三个核心部分：（i）两阶段面试策略，分为预面试与正式面试阶段；（ii）动态调整面试官权重以保障公平性；（iii）问题难度级别的自适应选择机制。在多个基准测试上的实验显示，该范式与全覆盖评估结果的相关性显著优于随机抽样，PLCC和SRCC分别提升了17.6%和16.7%，同时大幅减少了所需问题数量。这些结果表明，该范式为大规模MLLM基准测试提供了可靠高效的替代方案。

> The rapid progress of Multi-Modal Large Language Models (MLLMs) has spurred the creation of numerous benchmarks. However, conventional full-coverage Question-Answering evaluations suffer from high redundancy and low efficiency. Inspired by human interview processes, we propose a multi-to-one interview paradigm for efficient MLLM evaluation. Our framework consists of (i) a two-stage interview strategy with pre-interview and formal interview phases, (ii) dynamic adjustment of interviewer weights to ensure fairness, and (iii) an adaptive mechanism for question difficulty-level chosen. Experiments on different benchmarks show that the proposed paradigm achieves significantly higher correlation with full-coverage results than random sampling, with improvements of up to 17.6% in PLCC and 16.7% in SRCC, while reducing the number of required questions. These findings demonstrate that the proposed paradigm provides a reliable and efficient alternative for large-scale MLLM benchmarking.

[Arxiv](https://arxiv.org/abs/2509.14886)