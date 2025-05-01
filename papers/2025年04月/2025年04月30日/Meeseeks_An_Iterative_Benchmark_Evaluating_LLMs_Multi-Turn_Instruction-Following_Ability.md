# Meeseeks：评估大语言模型多轮指令遵循能力的迭代基准测试

发布时间：2025年04月30日

`LLM应用` `人工智能`

> Meeseeks: An Iterative Benchmark Evaluating LLMs Multi-Turn Instruction-Following Ability

# 摘要

> 准确遵循指令的能力是大型语言模型 (LLMs) 成为可靠代理的基础。现有的指令遵循基准测试要么是单轮对话，要么在每轮中引入新要求却不允许自我修正，而 Meeseeks 通过迭代反馈过程模拟了现实的人机交互。这种设计使模型能够根据特定要求的失败进行自我修正，更好地反映现实世界中用户的使用模式。该基准测试构建了一个全面的评估系统，包含 38 个能力标签，分布在三个维度：意图识别、细粒度内容验证和输出结构验证。通过对 LLMs 进行严格的评估，Meeseeks 为 LLMs 在实际应用中的指令遵循能力提供了深刻的见解。

> The ability to follow instructions accurately is fundamental for Large Language Models (LLMs) to serve as reliable agents in real-world applications. While existing instruction-following benchmarks are either single-turn or introduce new requirements in each turn without allowing self-correction, Meeseeks simulates realistic human-LLM interactions through an iterative feedback process. This design enables models to self-correct based on specific requirement failures, better reflecting real-world user-end usage patterns. The benchmark implements a comprehensive evaluation system with 38 capability tags organized across three dimensions: Intent Recognition, Granular Content Validation, and Output Structure Validation. Through rigorous evaluation across LLMs, Meeseeks provides valuable insights into LLMs' instruction-following capabilities in practical applications.

[Arxiv](https://arxiv.org/abs/2504.21625)