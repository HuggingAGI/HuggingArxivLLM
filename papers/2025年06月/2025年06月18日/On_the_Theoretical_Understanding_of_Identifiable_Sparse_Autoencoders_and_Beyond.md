# 可识别稀疏自动编码器的理论解析与拓展研究

发布时间：2025年06月18日

`LLM理论` `机器学习`

> On the Theoretical Understanding of Identifiable Sparse Autoencoders and Beyond

# 摘要

> 稀疏自动编码器（SAEs）作为一种强大的工具，已在解释大型语言模型（LLMs）学习的特征方面崭露头角。它通过稀疏激活的神经网络进行特征重构，旨在将复杂的叠加多义特征恢复为可解释的单义特征。尽管 SAEs 已经得到了广泛应用，但目前尚不清楚在何种条件下，SAEs 能够从叠加的多义特征中完全恢复出真实的单义特征。本文通过理论分析，首次提出了可识别 SAEs（即能够学习到唯一且真实的单义特征的 SAEs）的必要且充分条件，包括 1）真实特征的极度稀疏性，2）SAEs 的稀疏激活，以及 3）SAEs 足够的隐藏维度。此外，当可识别条件未能完全满足时，我们提出了一种重新加权策略来提升可识别性。具体而言，遵循理论建议的权重选择原则，我们证明了 SAE 重构与单义特征重构之间的损失函数差距可以被缩小，从而使得重新加权后的 SAEs 在重构真实单义特征方面优于均匀加权的 SAEs。实验中，我们验证了理论发现，并表明我们的加权 SAE 显著提高了特征的单义性和可解释性。

> Sparse autoencoders (SAEs) have emerged as a powerful tool for interpreting features learned by large language models (LLMs). It aims to recover complex superposed polysemantic features into interpretable monosemantic ones through feature reconstruction via sparsely activated neural networks. Despite the wide applications of SAEs, it remains unclear under what conditions an SAE can fully recover the ground truth monosemantic features from the superposed polysemantic ones. In this paper, through theoretical analysis, we for the first time propose the necessary and sufficient conditions for identifiable SAEs (SAEs that learn unique and ground truth monosemantic features), including 1) extreme sparsity of the ground truth feature, 2) sparse activation of SAEs, and 3) enough hidden dimensions of SAEs. Moreover, when the identifiable conditions are not fully met, we propose a reweighting strategy to improve the identifiability. Specifically, following the theoretically suggested weight selection principle, we prove that the gap between the loss functions of SAE reconstruction and monosemantic feature reconstruction can be narrowed, so that the reweighted SAEs have better reconstruction of the ground truth monosemantic features than the uniformly weighted ones. In experiments, we validate our theoretical findings and show that our weighted SAE significantly improves feature monosemanticity and interpretability.

[Arxiv](https://arxiv.org/abs/2506.15963)