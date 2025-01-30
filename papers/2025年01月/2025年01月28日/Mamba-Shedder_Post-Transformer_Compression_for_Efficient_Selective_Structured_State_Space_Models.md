# Mamba-Shedder: 后Transformer压缩技术，助力高效选择性结构化状态空间模型

发布时间：2025年01月28日

`LLM理论

理由：这篇论文主要讨论了大型预训练模型（如Transformer）的架构优化问题，特别是针对选择性结构化状态空间模型（SSM）的压缩和效率提升。这属于对大型语言模型（LLM）的理论研究和架构改进，因此归类为LLM理论。` `机器学习` `模型压缩`

> Mamba-Shedder: Post-Transformer Compression for Efficient Selective Structured State Space Models

# 摘要

> 大型预训练模型在序列建模中表现卓越，其中 Transformer 模块及其注意力机制功不可没。然而，Transformer 的低效问题催生了新的架构，如选择性结构化状态空间模型（SSMs）。本文聚焦于 SSM 模型的压缩，尤其是 Mamba 及其混合模型。我们通过在不同粒度下移除组件，研究其对模型大小和计算开销的影响，旨在提升效率而不失准确性。提出的 Mamba-Shedder 方案在推理中实现了 1.4 倍的加速，证明通过精简冗余可在几乎不影响性能的前提下提升效率。代码已开源：https://github.com/IntelLabs/Hardware-Aware-Automated-Machine-Learning。

> Large pre-trained models have achieved outstanding results in sequence modeling. The Transformer block and its attention mechanism have been the main drivers of the success of these models. Recently, alternative architectures, such as Selective Structured State Space Models (SSMs), have been proposed to address the inefficiencies of Transformers. This paper explores the compression of SSM-based models, particularly Mamba and its hybrids. We study the sensitivity of these models to the removal of selected components at different granularities to reduce the model size and computational overhead, thus improving their efficiency while maintaining accuracy. The proposed solutions, collectively referred to as Mamba-Shedder, achieve a speedup of up to 1.4x during inference, demonstrating that model efficiency can be improved by eliminating several redundancies with minimal impact on the overall model performance. The code is available at https://github.com/IntelLabs/Hardware-Aware-Automated-Machine-Learning.

[Arxiv](https://arxiv.org/abs/2501.17088)