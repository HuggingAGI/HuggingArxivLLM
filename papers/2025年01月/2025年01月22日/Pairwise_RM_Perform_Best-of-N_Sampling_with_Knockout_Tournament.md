# Pairwise RM: 通过淘汰赛实现最佳N采样

发布时间：2025年01月22日

`LLM应用

理由：这篇论文主要讨论了如何改进奖励模型（Reward Model）以优化LLM（大型语言模型）的生成结果选择策略。具体来说，它提出了一种新的成对奖励模型（Pairwise RM），并通过实验验证了其在数学问题生成任务中的有效性。这属于LLM在实际应用中的优化和改进，因此归类为LLM应用。`

> Pairwise RM: Perform Best-of-N Sampling with Knockout Tournament

# 摘要

> Best-of-N (BoN) 采样是 LLMs 测试扩展的常用策略，它依赖奖励模型从多个生成结果中选出最佳方案。然而，传统奖励模型常给出随意且不一致的评分，效果有限。为此，我们提出了一种结合淘汰赛的成对奖励模型（Pairwise RM）。不同于传统方法，Pairwise RM 在给定数学问题时，同时评估两个候选方案的正确性，避免了随意评分，并通过并行比较实现交叉验证。在淘汰赛中，Pairwise RM 对候选方案进行成对比较，逐步淘汰错误方案。我们构建了 \ourdataset，一个包含 443K 成对比较的大规模数据集，数据源自 NumiaMath 并使用 	exttt{gemini-1.5-flash} 标注，通过监督微调训练 Pairwise RM。实验表明，在 MATH-500 和 Olympiad Bench 上，Pairwise RM 显著优于传统判别式奖励模型，在最难的 50\% 问题上，相对改进达到 40\% 到 60\%。

> Best-of-N (BoN) sampling, a common strategy for test-time scaling of Large Language Models (LLMs), relies on reward models to select the best candidate solution from multiple generations. However, traditional reward models often assign arbitrary and inconsistent scores, limiting their effectiveness. To address this, we propose a Pairwise Reward Model (Pairwise RM) combined with a knockout tournament for BoN sampling. Instead of assigning absolute scores, given one math problem, Pairwise RM evaluates two candidate solutions' correctness simultaneously. This approach eliminates the need for arbitrary scoring and enables cross-validation of solutions through parallel comparison. In the knockout tournament, Pairwise RM conducts pairwise comparisons between candidate solutions and eliminates the incorrect ones iteratively. We construct \ourdataset, a large-scale dataset of 443K pairwise comparisons derived from NumiaMath and annotated using \texttt{gemini-1.5-flash}, and train the Pairwise RM via supervised fine-tuning. Experiments on MATH-500 and the Olympiad Bench demonstrate significant improvements over traditional discriminative reward models. And a 40\% to 60\% relative improvement is achieved on the top 50\% challenging problems.

[Arxiv](https://arxiv.org/abs/2501.13007)