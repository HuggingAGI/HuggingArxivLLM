# MultiChallenge: 一个真实且具有挑战性的多轮对话评估基准，专为前沿大型语言模型（LLMs）设计

发布时间：2025年01月28日

`LLM应用

理由：这篇论文主要讨论了大型语言模型（LLMs）在多轮对话中的能力评估，并提出了一个新的基准测试MultiChallenge。论文的重点在于评估LLMs在实际应用中的表现，特别是多轮对话中的指令遵循、上下文分配和推理能力。因此，这篇论文属于LLM应用的范畴。` `对话系统`

> MultiChallenge: A Realistic Multi-Turn Conversation Evaluation Benchmark Challenging to Frontier LLMs

# 摘要

> 我们推出了MultiChallenge，这是一个开创性的基准测试，旨在评估大型语言模型（LLMs）与人类进行多轮对话的能力，这是其应用中的关键但尚未充分研究的能力。MultiChallenge识别了多轮对话中的四类挑战，这些挑战不仅在当前人类与LLM的交互中常见且现实，而且对所有前沿LLMs都具有挑战性。所有挑战都需要同时具备准确的指令遵循、上下文分配和上下文推理能力。我们还开发了LLM作为评委，并制定了实例级别的评分标准，以促进一种与经验丰富的人类评分者具有公平一致性的自动评估方法。尽管在现有的多轮评估基准测试中取得了接近完美的分数，但所有前沿模型在MultiChallenge上的准确率都不到50%，表现最好的Claude 3.5 Sonnet（2024年6月）仅达到了41.4%的平均准确率。

> We present MultiChallenge, a pioneering benchmark evaluating large language models (LLMs) on conducting multi-turn conversations with human users, a crucial yet underexamined capability for their applications. MultiChallenge identifies four categories of challenges in multi-turn conversations that are not only common and realistic among current human-LLM interactions, but are also challenging to all current frontier LLMs. All 4 challenges require accurate instruction-following, context allocation, and in-context reasoning at the same time. We also develop LLM as judge with instance-level rubrics to facilitate an automatic evaluation method with fair agreement with experienced human raters. Despite achieving near-perfect scores on existing multi-turn evaluation benchmarks, all frontier models have less than 50% accuracy on MultiChallenge, with the top-performing Claude 3.5 Sonnet (June 2024) achieving just a 41.4% average accuracy.

[Arxiv](https://arxiv.org/abs/2501.17399)