# 只有大权重（而非跳跃连接的机制）才能避免秩坍缩的风险

发布时间：2025年05月22日

`LLM理论` `计算机科学`

> Only Large Weights (And Not Skip Connections) Can Prevent the Perils of Rank Collapse

# 摘要

> 注意力机制是现代大型语言模型 (LLMs) 的核心。用于前向和后向传播的简单算法具有二次时间复杂度，而从 [Alman 和 Song NeurIPS 2023] 以及 [Alman 和 Song NeurIPS 2024] 开始的一系列研究表明，除非模型权重很小，否则二次时间复杂度是不可避免的，这种情况下几乎线性时间的算法才有可能实现。本文中，我们证明了大权重是避免一种名为层坍塌（layer collapse）的强烈表示能力限制的必要条件，这意味着整个网络可以很好地被仅有一层的网络近似。因此，注意力机制的二次运行时间对于表达能力强的 Transformer 来说是不可避免的。

我们引入的层坍塌概念是 [Dong, Cordonnier, 和 Loukas ICML 2021] 的工作中秩坍塌（rank collapse）概念的一种变体。他们证明，在具有小权重和跳跃连接的自注意力网络中，秩坍塌必然发生。这通常被解释为在表达能力强的网络中跳跃连接的必要性提供了依据。然而，我们的结果显示，即使有跳跃连接，如果权重很小，层坍塌仍然会发生。因此，只有大权重，而不是跳跃连接，才能防止这些表示能力上的弱点。

> Attention mechanisms lie at the heart of modern large language models (LLMs). Straightforward algorithms for forward and backward (gradient) computation take quadratic time, and a line of work initiated by [Alman and Song NeurIPS 2023] and [Alman and Song NeurIPS 2024] has shown that quadratic time is necessary unless the model weights are small, in which case almost linear time algorithms are possible. In this paper, we show that large weights are necessary to avoid a strong preclusion to representational strength we call layer collapse, which means that the entire network can be approximated well by a network with only a single layer. Thus, the quadratic running time of attention is unavoidable for expressive transformers.
  The notion of layer collapse that we introduce is a variant on the notion of rank collapse from the work of [Dong, Cordonnier, and Loukas ICML 2021]. They showed that in Self Attention Networks with small weights and with skip connections, rank collapse must occur. This is typically interpreted as justifying the necessity of skip connections in expressive networks. However, our result shows that even with skip connections, if the weights are small, then layer collapse still occurs. Thus, only large weights, and not skip connections, can prevent these representational weaknesses.

[Arxiv](https://arxiv.org/abs/2505.16284)