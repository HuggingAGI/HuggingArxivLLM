# # 冬日战士：预训练阶段通过间接数据投毒植入后门

发布时间：2025年06月17日

`LLM理论` `数据安全` `模型安全`

> Winter Soldier: Backdooring Language Models at Pre-Training with Indirect Data Poisoning

# 摘要

> 大规模语言模型的预训练依赖于从多样且难以整理的来源获取的海量文本数据集。虽然成员推断攻击和隐藏的警示器可用于追踪数据使用，但这些方法依赖于模型对训练数据的记忆，而这正是模型提供商试图限制的。在此工作中，我们展示了间接数据投毒（目标行为未出现在训练数据中）不仅可行，还能有效保护数据集并追踪其使用。通过基于梯度的优化提示微调，我们使模型学习任意秘密序列：对秘密提示的 secret responses，而这些序列在训练语料库中并不存在。我们在从头预训练的语言模型上验证了我们的方法，并表明不到 0.005% 的投毒标记就足以秘密地让一个 LM 学习一个秘密，并通过一个理论上可验证的方案以极高的置信度（【数学公式】）检测到它。至关重要的是，这在不降低模型性能（在 LM 基准测试中）的情况下发生，尽管秘密从未出现在训练集中。

> The pre-training of large language models (LLMs) relies on massive text datasets sourced from diverse and difficult-to-curate origins. Although membership inference attacks and hidden canaries have been explored to trace data usage, such methods rely on memorization of training data, which LM providers try to limit. In this work, we demonstrate that indirect data poisoning (where the targeted behavior is absent from training data) is not only feasible but also allow to effectively protect a dataset and trace its use. Using gradient-based optimization prompt-tuning, we make a model learn arbitrary secret sequences: secret responses to secret prompts that are absent from the training corpus. We validate our approach on language models pre-trained from scratch and show that less than 0.005% of poisoned tokens are sufficient to covertly make a LM learn a secret and detect it with extremely high confidence ($p < 10^{-55}$) with a theoretically certifiable scheme. Crucially, this occurs without performance degradation (on LM benchmarks) and despite secrets never appearing in the training set.

[Arxiv](https://arxiv.org/abs/2506.14913)