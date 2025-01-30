# 稀疏自编码器在相同数据上训练，却学到了不同的特征

发布时间：2025年01月27日

`LLM理论

理由：这篇论文主要探讨了稀疏自编码器（SAEs）在大型语言模型（LLMs）中的应用，特别是关于SAEs在不同初始化权重下识别出的特征集的差异。研究涉及LLMs的激活特征和SAEs的训练过程，属于对LLMs内部机制的理论性探讨，因此归类为“LLM理论”。` `人工智能` `机器学习`

> Sparse Autoencoders Trained on the Same Data Learn Different Features

# 摘要

> 稀疏自编码器（SAEs）是揭示大型语言模型（LLMs）激活中人类可解释特征的有力工具。尽管有人期望SAEs能发现模型使用的真实底层特征，但我们的研究发现，相同模型和数据上训练的SAEs，仅因初始化权重的随机种子不同，便会识别出不同的特征集。例如，在Llama 3 8B的前馈网络上训练的131K潜在变量SAE中，不同种子间仅共享30%的特征。这一现象在三个不同LLMs的多个层、两个数据集和多种SAE架构中均有体现。使用L1稀疏损失训练的ReLU SAEs在不同种子间表现出更高的稳定性，而采用TopK激活函数的SAEs则对种子更为敏感，即便在稀疏水平相同的情况下。我们的结果表明，SAE揭示的特征集应被视为激活空间的一种实用分解，而非模型“真正使用”的详尽且通用的特征列表。

> Sparse autoencoders (SAEs) are a useful tool for uncovering human-interpretable features in the activations of large language models (LLMs). While some expect SAEs to find the true underlying features used by a model, our research shows that SAEs trained on the same model and data, differing only in the random seed used to initialize their weights, identify different sets of features. For example, in an SAE with 131K latents trained on a feedforward network in Llama 3 8B, only 30% of the features were shared across different seeds. We observed this phenomenon across multiple layers of three different LLMs, two datasets, and several SAE architectures. While ReLU SAEs trained with the L1 sparsity loss showed greater stability across seeds, SAEs using the state-of-the-art TopK activation function were more seed-dependent, even when controlling for the level of sparsity. Our results suggest that the set of features uncovered by an SAE should be viewed as a pragmatically useful decomposition of activation space, rather than an exhaustive and universal list of features "truly used" by the model.

[Arxiv](https://arxiv.org/abs/2501.16615)