# # 只有大权重（而非跳跃连接）才能避免秩坍塌的危险

发布时间：2025年05月22日

`LLM理论` `语言模型`

> Only Large Weights (And Not Skip Connections) Can Prevent the Perils of Rank Collapse

# 摘要

> 注意力机制是现代大型语言模型 (LLMs) 的核心。前向和后向 (梯度) 计算的直接算法需要二次时间复杂度，而由 [Alman 和 Song NeurIPS 2023] 与 [Alman 和 Song NeurIPS 2024] 开启的一系列研究工作表明，除非模型权重较小，否则二次时间复杂度是不可避免的，这种情况下几乎线性时间的算法才有可能实现。本文中，我们证明了大权重是避免我们所说的层坍缩（layer collapse）这一强表现力限制的必要条件，这意味着整个网络可以被一个仅含单层的网络很好地近似。因此，对于具有强表现力的 Transformer 来说，注意力机制的二次运行时间是不可避免的。

我们引入的层坍缩概念是对 [Dong, Cordonnier, 和 Loukas ICML 2021] 的秩坍缩（rank collapse）概念的一种变体。他们证明，在具有小权重和跳跃连接的自注意力网络中，秩坍缩必然发生。这通常被解释为证明了在具有强表现力的网络中跳跃连接的必要性。然而，我们的结果显示，即使存在跳跃连接，如果权重较小，层坍缩仍然会发生。因此，只有大权重，而非跳跃连接，才能避免这些表示上的弱点。

> Attention mechanisms lie at the heart of modern large language models (LLMs). Straightforward algorithms for forward and backward (gradient) computation take quadratic time, and a line of work initiated by [Alman and Song NeurIPS 2023] and [Alman and Song NeurIPS 2024] has shown that quadratic time is necessary unless the model weights are small, in which case almost linear time algorithms are possible. In this paper, we show that large weights are necessary to avoid a strong preclusion to representational strength we call layer collapse, which means that the entire network can be approximated well by a network with only a single layer. Thus, the quadratic running time of attention is unavoidable for expressive transformers.
  The notion of layer collapse that we introduce is a variant on the notion of rank collapse from the work of [Dong, Cordonnier, and Loukas ICML 2021]. They showed that in Self Attention Networks with small weights and with skip connections, rank collapse must occur. This is typically interpreted as justifying the necessity of skip connections in expressive networks. However, our result shows that even with skip connections, if the weights are small, then layer collapse still occurs. Thus, only large weights, and not skip connections, can prevent these representational weaknesses.

[Arxiv](https://arxiv.org/abs/2505.16284)