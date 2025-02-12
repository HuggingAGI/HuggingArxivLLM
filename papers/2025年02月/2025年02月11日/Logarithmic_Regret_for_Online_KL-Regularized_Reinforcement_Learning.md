# # 在线KL正则化强化学习的对数后悔

发布时间：2025年02月11日

`LLM理论` `机器学习` `人工智能`

> Logarithmic Regret for Online KL-Regularized Reinforcement Learning

# 摘要

> 近期强化学习从人类反馈（RLHF）领域的研究进展表明，KL正则化在提升大型语言模型（LLMs）强化学习微调效率方面具有重要作用。尽管KL正则化在经验上表现出优势，但其与标准强化学习之间的理论差异尚未得到充分探索。虽然近期有研究对KL正则化目标在决策中的理论进行了分析 \citep{xiong2024iterative, xie2024exploratory,zhao2024sharp}，但这些分析要么局限于传统强化学习场景，要么依赖于较强的覆盖假设。本文提出了一种基于乐观主义的KL正则化在线上下文多臂老虎机算法，并对其遗憾进行了全新分析。通过巧妙结合KL正则化带来的良好优化格局和乐观奖励估计，我们的算法实现了$\mathcal{O}ig(η\log (N_{\mathcal R} T)\cdot d_{\mathcal R}ig)$的对数遗憾界，其中$η, N_{\mathcal R},T,d_{\mathcal R}$分别表示KL正则化参数、奖励函数类的基数、轮数以及奖励函数类的复杂度。此外，我们还通过创新的转移步骤分解，将算法和分析扩展到强化学习领域，并获得了类似的对数遗憾界。

> Recent advances in Reinforcement Learning from Human Feedback (RLHF) have shown that KL-regularization plays a pivotal role in improving the efficiency of RL fine-tuning for large language models (LLMs). Despite its empirical advantage, the theoretical difference between KL-regularized RL and standard RL remains largely under-explored. While there is a recent line of work on the theoretical analysis of KL-regularized objective in decision making \citep{xiong2024iterative, xie2024exploratory,zhao2024sharp}, these analyses either reduce to the traditional RL setting or rely on strong coverage assumptions. In this paper, we propose an optimism-based KL-regularized online contextual bandit algorithm, and provide a novel analysis of its regret. By carefully leveraging the benign optimization landscape induced by the KL-regularization and the optimistic reward estimation, our algorithm achieves an $\mathcal{O}\big(η\log (N_{\mathcal R} T)\cdot d_{\mathcal R}\big)$ logarithmic regret bound, where $η, N_{\mathcal R},T,d_{\mathcal R}$ denote the KL-regularization parameter, the cardinality of the reward function class, number of rounds, and the complexity of the reward function class. Furthermore, we extend our algorithm and analysis to reinforcement learning by developing a novel decomposition over transition steps and also obtain a similar logarithmic regret bound.

[Arxiv](https://arxiv.org/abs/2502.07460)