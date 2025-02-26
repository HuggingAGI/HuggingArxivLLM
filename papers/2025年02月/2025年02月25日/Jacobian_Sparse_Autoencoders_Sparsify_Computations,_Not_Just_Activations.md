# Jacobian稀疏自动编码器：让计算更稀疏，不只是激活层

发布时间：2025年02月25日

`LLM理论` `机器学习`

> Jacobian Sparse Autoencoders: Sparsify Computations, Not Just Activations

# 摘要

> 稀疏自动编码器（SAEs）在发现大型语言模型（LLMs）潜在激活的稀疏且可解释表示方面表现出色。然而，我们真正关心的是理解LLMs的计算过程，而不仅仅是它们的表示形式。SAEs在帮助我们理解计算方面的能力尚不明确，因为它们的设计初衷仅限于“稀疏化”潜在激活，而非计算本身。为解决这一问题，我们提出了Jacobian稀疏自动编码器（JSAEs），它不仅能在模型组件的输入和输出激活中实现稀疏性，还能在连接它们的计算（雅可比矩阵）中实现稀疏性。由于LLMs中雅可比矩阵的规模，直接计算会导致不可行。因此，我们的一个关键贡献是找到了一种高效计算雅可比矩阵的方法。实验表明，JSAEs能够提取较高程度的计算稀疏性，同时保持与传统SAEs相当的下游模型性能。此外，我们发现雅可比矩阵是计算稀疏性的合理替代，因为MLPs在JSAE基下近似线性。最后，我们发现JSAEs在预训练LLMs上实现了比随机LLMs更高的计算稀疏性。这表明，计算图的稀疏性可能是LLMs通过训练学习到的特性，因此JSAEs可能比标准SAEs更适合理解学习到的Transformer计算过程。

> Sparse autoencoders (SAEs) have been successfully used to discover sparse and human-interpretable representations of the latent activations of LLMs. However, we would ultimately like to understand the computations performed by LLMs and not just their representations. The extent to which SAEs can help us understand computations is unclear because they are not designed to "sparsify" computations in any sense, only latent activations. To solve this, we propose Jacobian SAEs (JSAEs), which yield not only sparsity in the input and output activations of a given model component but also sparsity in the computation (formally, the Jacobian) connecting them. With a naïve implementation, the Jacobians in LLMs would be computationally intractable due to their size. One key technical contribution is thus finding an efficient way of computing Jacobians in this setup. We find that JSAEs extract a relatively large degree of computational sparsity while preserving downstream LLM performance approximately as well as traditional SAEs. We also show that Jacobians are a reasonable proxy for computational sparsity because MLPs are approximately linear when rewritten in the JSAE basis. Lastly, we show that JSAEs achieve a greater degree of computational sparsity on pre-trained LLMs than on the equivalent randomized LLM. This shows that the sparsity of the computational graph appears to be a property that LLMs learn through training, and suggests that JSAEs might be more suitable for understanding learned transformer computations than standard SAEs.

[Arxiv](https://arxiv.org/abs/2502.18147)