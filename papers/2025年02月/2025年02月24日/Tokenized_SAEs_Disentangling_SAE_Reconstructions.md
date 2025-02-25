# 分解 SAE 重构，探索 Tokenized SAEs 的奥秘

发布时间：2025年02月24日

`LLM理论

理由：这篇论文探讨了稀疏自动编码器（SAEs）在解释语言模型内部机制中的作用，分析了特征对应的问题，并提出了改进方法。这属于对模型内部机制的理论分析，因此归类为LLM理论。` `计算机科学`

> Tokenized SAEs: Disentangling SAE Reconstructions

# 摘要

> 稀疏自动编码器（SAEs）已经成为解释语言模型内部机制的重要工具。然而，目前尚不清楚 SAE 特征与模型中计算上重要的方向有多大的对应关系。本研究通过实证发现，许多 RES-JB SAE 特征主要对应于简单的输入统计信息。我们推测，这是由于训练数据中存在大规模类别不平衡，同时缺乏复杂的错误信号所导致。为了减少这种现象，我们提出了一种方法，通过分离令牌重建与特征重建来改进模型。这一改进通过引入每个令牌的偏差实现，为有趣的重建提供了增强的基线。结果表明，在稀疏环境中，显著更多有趣的特征和改进的重建被学习到了。

> Sparse auto-encoders (SAEs) have become a prevalent tool for interpreting language models' inner workings. However, it is unknown how tightly SAE features correspond to computationally important directions in the model. This work empirically shows that many RES-JB SAE features predominantly correspond to simple input statistics. We hypothesize this is caused by a large class imbalance in training data combined with a lack of complex error signals. To reduce this behavior, we propose a method that disentangles token reconstruction from feature reconstruction. This improvement is achieved by introducing a per-token bias, which provides an enhanced baseline for interesting reconstruction. As a result, significantly more interesting features and improved reconstruction in sparse regimes are learned.

[Arxiv](https://arxiv.org/abs/2502.17332)