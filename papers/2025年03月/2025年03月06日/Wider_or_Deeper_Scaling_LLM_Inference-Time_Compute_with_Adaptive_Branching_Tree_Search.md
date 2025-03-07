# 更宽还是更深？采用自适应分叉树搜索，探讨如何扩展 LLM 推理计算规模

发布时间：2025年03月06日

`LLM应用

理由：这篇论文专注于改进大型语言模型（LLMs）的推理过程，提出了一种新的推理框架（AB-MCTS），旨在通过结合外部反馈和多轮优化来提升模型的推理能力。研究内容集中在如何更有效地利用模型的输出和反馈信号，属于对LLM应用的优化和改进，因此归类为LLM应用。` `软件工程`

> Wider or Deeper? Scaling LLM Inference-Time Compute with Adaptive Branching Tree Search

# 摘要

> 近期研究显示，提升推理时间计算能够显著增强大型语言模型（LLMs）的推理能力。虽然重复采样（即生成多个候选输出）是一种高效的策略，但它未能充分利用外部反馈信号进行优化，而这类反馈在编码等任务中往往唾手可得。本研究提出了一种全新的推理时间框架——$	extit{自适应分支蒙特卡洛树搜索 (AB-MCTS)}$，该框架通过有原则的多轮探索与利用，将重复采样的能力进行了扩展。在搜索树的每个节点，AB-MCTS会根据外部反馈信号，动态决定是“拓宽”搜索范围（通过扩展新的候选响应）还是“加深”探索（通过重新审视现有响应）。我们采用前沿模型在复杂的编码和工程任务中对这一方法进行了评估。实验结果表明，AB-MCTS在推理时间扩展方面表现优异，显著超越了重复采样和标准MCTS，充分证明了将LLMs的响应多样性与多轮解优化相结合的重要性。

> Recent advances demonstrate that increasing inference-time computation can significantly boost the reasoning capabilities of large language models (LLMs). Although repeated sampling (i.e., generating multiple candidate outputs) is a highly effective strategy, it does not leverage external feedback signals for refinement, which are often available in tasks like coding. In this work, we propose $\textit{Adaptive Branching Monte Carlo Tree Search (AB-MCTS)}$, a novel inference-time framework that generalizes repeated sampling with principled multi-turn exploration and exploitation. At each node in the search tree, AB-MCTS dynamically decides whether to "go wider" by expanding new candidate responses or "go deeper" by revisiting existing ones based on external feedback signals. We evaluate our method on complex coding and engineering tasks using frontier models. Empirical results show that AB-MCTS consistently outperforms both repeated sampling and standard MCTS, underscoring the importance of combining the response diversity of LLMs with multi-turn solution refinement for effective inference-time scaling.

[Arxiv](https://arxiv.org/abs/2503.04412)