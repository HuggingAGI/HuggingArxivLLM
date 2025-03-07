# HybridNorm: 通过混合归一化实现稳定且高效的Transformer训练

发布时间：2025年03月06日

`LLM理论` `机器学习`

> HybridNorm: Towards Stable and Efficient Transformer Training via Hybrid Normalization

# 摘要

> Transformer 已经成为机器学习任务，尤其是大型语言模型 (LLMs) 中的事实上的架构。尽管它们表现出色，但在训练深度 Transformer 网络时，特别是关于层归一化的定位，仍存在挑战。Pre-Norm 结构虽然由于其更突出的身份路径而使训练更容易，但通常在性能上不如 Post-Norm。在本文中，我们提出了 $	extbf{HybridNorm}$，一种简单而有效的混合归一化策略，结合了 Pre-Norm 和 Post-Norm 方法的优点。具体来说，HybridNorm 在注意力机制中使用 QKV 归一化，并在每个 Transformer 块的前馈网络 (FFN) 中使用 Post-Norm。这种设计不仅稳定了训练，还提升了性能，特别是在 LLM 的背景下。在密集和稀疏架构中的全面实验表明，HybridNorm 一致优于 Pre-Norm 和 Post-Norm 方法，在各种基准测试中达到了最先进的结果。这些发现突显了 HybridNorm 作为一种更稳定和有效的方法，用于改进深度 Transformer 模型的训练和性能。

> Transformers have become the de facto architecture for a wide range of machine learning tasks, particularly in large language models (LLMs). Despite their remarkable performance, challenges remain in training deep transformer networks, especially regarding the location of layer normalization. While Pre-Norm structures facilitate easier training due to their more prominent identity path, they often yield suboptimal performance compared to Post-Norm. In this paper, we propose $\textbf{HybridNorm}$, a straightforward yet effective hybrid normalization strategy that integrates the advantages of both Pre-Norm and Post-Norm approaches. Specifically, HybridNorm employs QKV normalization within the attention mechanism and Post-Norm in the feed-forward network (FFN) of each transformer block. This design not only stabilizes training but also enhances performance, particularly in the context of LLMs. Comprehensive experiments in both dense and sparse architectures show that HybridNorm consistently outperforms both Pre-Norm and Post-Norm approaches, achieving state-of-the-art results across various benchmarks. These findings highlight the potential of HybridNorm as a more stable and effective technique for improving the training and performance of deep transformer models. %Code will be made publicly available. Code is available at https://github.com/BryceZhuo/HybridNorm.

[Arxiv](https://arxiv.org/abs/2503.04598)