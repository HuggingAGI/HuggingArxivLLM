# $	exttt{SEM-CTRL}$: 语义控制的解码方法

发布时间：2025年03月03日

`LLM应用` `人工智能`

> $\texttt{SEM-CTRL}$: Semantically Controlled Decoding

# 摘要

> 尽管语法和语义的正确性对大型语言模型 (LLM) 的实际应用至关重要，但要在输出中同时确保这两者的正确性仍然是一个重大挑战。本文提出了一种名为 $	exttt{SEM-CTRL}$ 的统一方法，能够在 LLM 解码器上直接施加丰富的上下文敏感约束以及任务和实例特定的语义。该方法结合了基于特定语法和语义约束引导的基于token的MCTS技术。通过答案集文法（一种逻辑形式化方法，能够推广上下文敏感文法，并结合背景知识来表示任务特定语义）来表达对期望输出的约束。我们的方法能够保证任何现成 LLM 的正确完成，而无需进行微调。我们在合成语法规则生成、组合推理和规划等多种任务上对 $	exttt{SEM-CTRL}$ 进行了评估。实验结果表明，$	exttt{SEM-CTRL}$ 使小型预训练 LLM 能够高效地超越更大规模的变体和最先进的推理模型（例如 o1-preview），同时保证解决方案的正确性。

> Ensuring both syntactic and semantic correctness in Large Language Model (LLM) outputs remains a significant challenge, despite being critical for real-world deployment. In this paper, we introduce $\texttt{SEM-CTRL}$, a unified approach that enforces rich context-sensitive constraints and task- and instance-specific semantics directly on an LLM decoder. Our approach integrates token-level MCTS, which is guided by specific syntactic and semantic constraints. The constraints over the desired outputs are expressed using Answer Set Grammars -- a logic-based formalism that generalizes context-sensitive grammars while incorporating background knowledge to represent task-specific semantics. We show that our approach guarantees correct completions for any off-the-shelf LLM without the need for fine-tuning. We evaluate $\texttt{SEM-CTRL}$ on a range of tasks, including synthetic grammar synthesis, combinatorial reasoning, and planning. Our results demonstrate that $\texttt{SEM-CTRL}$ allows small pre-trained LLMs to efficiently outperform larger variants and state-of-the-art reasoning models (e.g., o1-preview) while simultaneously guaranteeing solution correctness.

[Arxiv](https://arxiv.org/abs/2503.01804)