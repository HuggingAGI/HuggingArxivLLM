# 探索经典与量子空间里的复杂词嵌入

发布时间：2024年12月18日

`LLM应用` `量子计算`

> Learning Complex Word Embeddings in Classical and Quantum Spaces

# 摘要

> 我们给出了基于经典 Skip-gram 模型训练复数值词嵌入的多种方法，只需将实数值向量简单替换为任意复数向量即可直接适配。在更具“物理启发”的方式中，向量由参数化量子电路（PQCs）生成，这是一种产生具有概率解释的归一化向量的酉变换。我们开发了高度优化的 Skip-gram 的 C 代码的复数值版本，借此能够轻松为词汇量超 40 万的 38 亿词语料库生成复嵌入，进而能为每个词训练单独的 PQC。我们在一组标准的相似性和相关性数据集上对复嵌入进行评估，某些模型取得了与经典基线相当的结果。我们发现，直接训练 PQCs 往往会损害性能，而两阶段过程中的量子词嵌入表现与参数数量相当的经典 Skip-gram 嵌入一样出色。这为在复杂空间中学习嵌入开辟了一条高度可扩展的路径，其随词汇量大小而非训练语料库大小扩展。总之，我们展示了如何为复数值和量子启发的 NLP 模型生成大量高质量词嵌入，并探索量子 NLP 模型的潜在优势。

> We present a variety of methods for training complex-valued word embeddings, based on the classical Skip-gram model, with a straightforward adaptation simply replacing the real-valued vectors with arbitrary vectors of complex numbers. In a more "physically-inspired" approach, the vectors are produced by parameterised quantum circuits (PQCs), which are unitary transformations resulting in normalised vectors which have a probabilistic interpretation. We develop a complex-valued version of the highly optimised C code version of Skip-gram, which allows us to easily produce complex embeddings trained on a 3.8B-word corpus for a vocabulary size of over 400k, for which we are then able to train a separate PQC for each word. We evaluate the complex embeddings on a set of standard similarity and relatedness datasets, for some models obtaining results competitive with the classical baseline. We find that, while training the PQCs directly tends to harm performance, the quantum word embeddings from the two-stage process perform as well as the classical Skip-gram embeddings with comparable numbers of parameters. This enables a highly scalable route to learning embeddings in complex spaces which scales with the size of the vocabulary rather than the size of the training corpus. In summary, we demonstrate how to produce a large set of high-quality word embeddings for use in complex-valued and quantum-inspired NLP models, and for exploring potential advantage in quantum NLP models.

[Arxiv](https://arxiv.org/abs/2412.13745)