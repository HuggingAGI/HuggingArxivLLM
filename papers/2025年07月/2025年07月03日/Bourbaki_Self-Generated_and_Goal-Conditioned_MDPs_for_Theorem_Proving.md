# 布尔巴基：用于定理证明的自生成且目标导向的马尔可夫决策过程

发布时间：2025年07月03日

`LLM应用

理由：这篇论文探讨了大型语言模型在复杂推理任务中的应用，特别是通过结合强化学习和蒙特卡洛树搜索算法来提升其自动定理证明的能力。虽然提到了代理的概念，但核心内容围绕如何应用LLMs解决特定任务，因此归类为LLM应用。` `自动定理证明`

> Bourbaki: Self-Generated and Goal-Conditioned MDPs for Theorem Proving

# 摘要

> 推理对于大型语言模型（LLMs）来说仍然是一项具有挑战性的任务，尤其是在自动定理证明（ATP）的逻辑约束环境中，这主要归因于稀疏奖励和庞大的证明规模。这些挑战在包含复杂多步骤推理问题的大学水平基准测试PutnamBench中尤为突出。为了解决这一难题，我们提出了自动生成的目标条件马尔可夫决策过程（sG-MDPs）框架，其中代理能够根据不断演变的证明状态生成并追求子目标。这种结构化的目标生成使得问题更易于搜索。随后，我们采用蒙特卡洛树搜索（MCTS）类算法解决sG-MDP，并在模块化系统Bourbaki（7B）中实现这一方法，该系统能够整合多个7B LLMs进行子目标生成和策略合成。在PutnamBench上，Bourbaki（7B）成功解决了26个问题，以该规模模型实现了新的最先进结果。

> Reasoning remains a challenging task for large language models (LLMs), especially within the logically constrained environment of automated theorem proving (ATP), due to sparse rewards and the vast scale of proofs. These challenges are amplified in benchmarks like PutnamBench, which contains university-level problems requiring complex, multi-step reasoning. To address this, we introduce self-generated goal-conditioned MDPs (sG-MDPs), a new framework in which agents generate and pursue their subgoals based on the evolving proof state. Given this more structured generation of goals, the resulting problem becomes more amenable to search. We then apply Monte Carlo Tree Search (MCTS)-like algorithms to solve the sG-MDP, instantiating our approach in Bourbaki (7B), a modular system that can ensemble multiple 7B LLMs for subgoal generation and tactic synthesis. On PutnamBench, Bourbaki (7B) solves 26 problems, achieving new state-of-the-art results with models at this scale.

[Arxiv](https://arxiv.org/abs/2507.02726)