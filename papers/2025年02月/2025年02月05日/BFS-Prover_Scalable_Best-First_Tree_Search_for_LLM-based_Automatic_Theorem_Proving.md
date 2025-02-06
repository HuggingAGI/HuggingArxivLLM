# BFS-Prover: 基于LLM的自动定理证明的可扩展最佳优先树搜索

发布时间：2025年02月05日

`LLM应用

理由：这篇论文探讨了如何使用大型语言模型（LLMs）在自动定理证明任务中改进树搜索方法，特别是最佳优先搜索（BFS）。论文提出了一个名为 \texttt{BFS-Prover} 的框架，结合了LLM的策略优化和数据过滤技术，以提高定理证明的效率。这属于LLM在实际应用中的使用，因此归类为“LLM应用”。` `自动定理证明` `人工智能`

> BFS-Prover: Scalable Best-First Tree Search for LLM-based Automatic Theorem Proving

# 摘要

> # 摘要
最近大型语言模型（LLMs）的进展激发了使用Lean4进行自动定理证明的兴趣，其中高效的树搜索方法对导航证明搜索空间至关重要。尽管现有方法主要依赖价值函数和蒙特卡罗树搜索（MCTS），但像最佳优先搜索（BFS）这样更简单方法的潜力尚未被充分挖掘。本文探讨了BFS是否能在大规模定理证明任务中取得竞争力。我们提出了	exttt{BFS-Prover}，一个可扩展的专家迭代框架，包含三大创新：首先，我们在每轮专家迭代中进行战略数据过滤，排除可通过波束搜索节点扩展解决的问题，专注于更难的案例；其次，我们通过直接偏好优化（DPO）提升BFS的样本效率，优化LLM的策略，优先考虑有成效的扩展；第三，我们在BFS中采用长度归一化，鼓励探索更深的证明路径。	exttt{BFS-Prover}在MiniF2F测试集上取得了$71.31$的分数，挑战了复杂树搜索方法的必要性，证明了BFS在适当扩展时也能表现出色。

> Recent advancements in large language models (LLMs) have spurred growing interest in automatic theorem proving using Lean4, where effective tree search methods are crucial for navigating proof search spaces. While the existing approaches primarily rely on value functions and Monte Carlo Tree Search (MCTS), the potential of simpler methods like Best-First Search (BFS) remains underexplored. This paper investigates whether BFS can achieve competitive performance in large-scale theorem proving tasks. We present \texttt{BFS-Prover}, a scalable expert iteration framework, featuring three key innovations. First, we implement strategic data filtering at each expert iteration round, excluding problems solvable via beam search node expansion to focus on harder cases. Second, we improve the sample efficiency of BFS through Direct Preference Optimization (DPO) applied to state-tactic pairs automatically annotated with compiler error feedback, refining the LLM's policy to prioritize productive expansions. Third, we employ length normalization in BFS to encourage exploration of deeper proof paths. \texttt{BFS-Prover} achieves a score of $71.31$ on the MiniF2F test set and therefore challenges the perceived necessity of complex tree search methods, demonstrating that BFS can achieve competitive performance when properly scaled.

[Arxiv](https://arxiv.org/abs/2502.03438)