# 基于Actor-Critic的在线数据混合方法用于语言模型预训练

发布时间：2025年05月29日

`LLM理论

理由：这篇论文讨论了如何优化预训练大型语言模型的数据混合策略，使用强化学习方法来动态调整数据采样策略，以提高模型的泛化能力和训练效率。这属于大型语言模型的训练理论和方法，因此归类为LLM理论。` `数据混合` `预训练模型`

> Actor-Critic based Online Data Mixing For Language Model Pre-Training

# 摘要

> 预训练数据的覆盖范围和组成结构对大型语言模型 (LLMs) 的泛化能力有着重要影响。为了降低训练过程中的碳足迹和财务成本，一些数据混合方法被提出，这些方法通过将优化后的领域权重应用于小型代理模型，进而训练更大的模型。然而，这些方法未能随着训练动态而演变。现有的在线数据混合 (ODM) 方法通过采用多臂老虎机算法作为数据采样策略，解决了这一局限性。然而，它并未考虑领域内部的交互作用。本文中，我们开发了一种基于演员-评论家的在线数据混合 (AC-ODM) 方法，该方法通过辅助演员-评论家网络捕捉变化的领域权重，并通过奖励函数考虑领域内部的交互作用。在构建用于预训练大型目标 LLM 的数据集时，我们直接应用经过训练的演员（以小型代理 LLM 作为环境），作为采样策略。采样策略的迁移不仅可以确保动态数据混合的效率，还能加速目标 LLM 预训练的收敛。数值结果表明，AC-ODM-410M（调用由具有 410M 参数的代理 LLM 得到的采样策略）比 ODM 提前 71% 达到最优验证困惑度，并在零-shot MMLU 基准测试中的准确率提高了 27.5%，在 HumanEval 基准测试中的 pass@1 表现提升了约 2.23 倍。

> The coverage and composition of pretraining data significantly impacts the generalization ability of Large Language Models (LLMs). To reduce the carbon footprint and financial costs of training, some data mixing methods, which applied the optimized domain weights of a small proxy model to train a larger one, were proposed. However, these methods did not evolute with the training dynamics. The existing online data mixing (ODM) method addressed this limitation by applying the multi-armed bandit algorithm as data sampling strategy. Yet, it did not consider the intra-domain interactions. In this paper, we develop an actor-critic based online data mixing (AC-ODM) method, which captures the varying domain weights by auxiliary actor-critic networks and consider the intra-domain interactions with the reward function. While constructing the dataset to pretrain a large target LLM, we directly apply the actor, which is trained with a small proxy LLM as the environment, as the sampling strategy. The transfer of sampling strategy can not only ensure the efficiency of dynamical data mixing, but also expedite the convergence of pretraining the target LLM. Numerical results demonstrate that AC-ODM-410M, which invokes the sampling strategy obtained by a proxy LLM with 410M parameters, reaching the optimal validation perplexity of ODM 71% faster, and improves performance on the zero-shot MMLU benchmark by 27.5% of accuracy, about 2.23x better on pass@1 of HumanEval benchmark.

[Arxiv](https://arxiv.org/abs/2505.23878)