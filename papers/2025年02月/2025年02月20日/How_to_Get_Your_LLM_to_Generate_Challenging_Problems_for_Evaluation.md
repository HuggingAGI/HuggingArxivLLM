# 如何让LLM生成评估用的难题

发布时间：2025年02月20日

`LLM应用`

> How to Get Your LLM to Generate Challenging Problems for Evaluation

# 摘要

> 大型语言模型 (LLMs) 的快速发展要求采用新的方法来进行严格和全面的评估。由于生成高质量、具有挑战性的问题所涉及的复杂性和成本，传统的手动标注方法越来越不切实际。在这项工作中，我们引入了 CHASE，一个无需人工参与的统一框架，用于合成生成具有挑战性的问题。对于给定的任务，我们的方法通过从更简单的组件开始，以自下而上的方式构建困难的问题。此外，我们的框架将生成过程分解为独立可验证的子任务，从而确保了高质量和正确性。我们实现了 CHASE，以在三个不同的领域创建评估基准：(1) 基于文档的问题回答，(2) 仓库级代码补全，(3) 数学推理。在这些合成基准上，当前最先进的 LLM 的性能在 40-60% 的准确率范围内，从而证明了我们的框架在生成具有挑战性问题方面的有效性。我们公开发布了我们的基准和代码。


> The pace of evolution of Large Language Models (LLMs) necessitates new approaches for rigorous and comprehensive evaluation. Traditional human annotation is increasingly impracticable due to the complexities and costs involved in generating high-quality, challenging problems. In this work, we introduce CHASE, a unified framework to synthetically generate challenging problems using LLMs without human involvement. For a given task, our approach builds a hard problem in a bottom-up manner from simpler components. Moreover, our framework decomposes the generation process into independently verifiable sub-tasks, thereby ensuring a high level of quality and correctness. We implement CHASE to create evaluation benchmarks across three diverse domains: (1) document-based question answering, (2) repository-level code completion, and (3) math reasoning. The performance of state-of-the-art LLMs on these synthetic benchmarks lies in the range of 40-60% accuracy, thereby demonstrating the effectiveness of our framework at generating challenging problems. We publicly release our benchmarks and code.

[Arxiv](https://arxiv.org/abs/2502.14678)