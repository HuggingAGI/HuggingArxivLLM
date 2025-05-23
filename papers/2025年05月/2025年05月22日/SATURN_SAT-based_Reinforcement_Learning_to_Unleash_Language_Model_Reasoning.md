# # SATURN：基于 SAT 的强化学习，解锁语言模型推理潜能

发布时间：2025年05月22日

`LLM应用`

> SATURN: SAT-based Reinforcement Learning to Unleash Language Model Reasoning

# 摘要

> 如何设计强化学习（RL）任务以充分发挥大型语言模型（LLMs）的推理能力，仍是一个开放性问题。现有的 RL 任务（如数学、编程和推理任务）面临三大关键挑战：(1) 数据扩展性不足，严重依赖人工标注或昂贵的 LLM 合成；(2) 输出验证困难，难以自动可靠地验证 LLMs 的结果；(3) 难度控制缺失，大多数任务缺乏精细的难度分级，难以有效训练 LLM 从简单到复杂逐步提升推理能力。

为了解决这些难题，我们提出了 Saturn，一个基于布尔可满足性（SAT）问题的 RL 框架，用于训练和评估 LLM 的推理能力。Saturn 具备三大优势：可扩展的任务构建、基于规则的验证机制和精确的难度控制。通过设计一个课程学习管道，Saturn 能够从简单到复杂逐步提升 LLM 的推理能力。同时，我们设计了一种系统性的机制，确保训练过程中的难度过渡平稳可控。

我们发布了 Saturn-2.6k 数据集，包含 2,660 个难度各异的 SAT 问题，支持研究 LLM 推理能力随问题难度的变化。我们将 Saturn 应用于 DeepSeek-R1-Distill-Qwen 模型，得到了 Saturn-1.5B 和 Saturn-7B 两个版本。实验结果表明：(1) 在 SAT 问题上，Saturn-1.5B 和 Saturn-7B 的平均通过率分别提升了 +14.0 和 +28.1；(2) 在数学和编程任务上，Saturn-1.5B 和 Saturn-7B 在 AIME、LiveCodeBench 等基准测试中的平均分数分别提高了 +4.9 和 +1.8；(3) 与现有最佳方法相比，Saturn 的性能提升了 +8.8%。我们开源了 Saturn 的源代码、数据集和模型，以支持相关领域的进一步研究。

> How to design reinforcement learning (RL) tasks that effectively unleash the reasoning capability of large language models (LLMs) remains an open question. Existing RL tasks (e.g., math, programming, and constructing reasoning tasks) suffer from three key limitations: (1) Scalability. They rely heavily on human annotation or expensive LLM synthesis to generate sufficient training data. (2) Verifiability. LLMs' outputs are hard to verify automatically and reliably. (3) Controllable Difficulty. Most tasks lack fine-grained difficulty control, making it hard to train LLMs to develop reasoning ability from easy to hard.
  To address these limitations, we propose Saturn, a SAT-based RL framework that uses Boolean Satisfiability (SAT) problems to train and evaluate LLM reasoning. Saturn enables scalable task construction, rule-based verification, and precise difficulty control. Saturn designs a curriculum learning pipeline that continuously improves LLMs' reasoning capability by constructing SAT tasks of increasing difficulty and training LLMs from easy to hard. To ensure stable training, we design a principled mechanism to control difficulty transitions.
  We introduce Saturn-2.6k, a dataset of 2,660 SAT problems with varying difficulty. It supports the evaluation of how LLM reasoning changes with problem difficulty. We apply Saturn to DeepSeek-R1-Distill-Qwen and obtain Saturn-1.5B and Saturn-7B. We achieve several notable results: (1) On SAT problems, Saturn-1.5B and Saturn-7B achieve average pass@3 improvements of +14.0 and +28.1, respectively. (2) On math and programming tasks, Saturn-1.5B and Saturn-7B improve average scores by +4.9 and +1.8 on benchmarks (e.g., AIME, LiveCodeBench). (3) Compared to the state-of-the-art (SOTA) approach in constructing RL tasks, Saturn achieves further improvements of +8.8%. We release the source code, data, and models to support future research.

[Arxiv](https://arxiv.org/abs/2505.16368)