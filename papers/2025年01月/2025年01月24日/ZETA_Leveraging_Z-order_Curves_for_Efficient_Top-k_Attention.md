# ZETA: 基于 Z-order 曲线的高效 Top-k 注意力机制

发布时间：2025年01月24日

`LLM理论

理由：这篇论文主要讨论了Transformer架构中的自注意力机制及其计算效率问题，提出了ZETA方法来解决top-$k$注意力的并行化问题。虽然论文涉及了Transformer和注意力机制，但这些内容更偏向于对大型语言模型（LLM）的理论改进和优化，而不是具体的应用或代理（Agent）系统。因此，将其归类为“LLM理论”更为合适。` `机器学习`

> ZETA: Leveraging Z-order Curves for Efficient Top-k Attention

# 摘要

> 近年来，Transformer 已成为序列建模的核心架构。然而，其自注意力机制的内存和计算成本随序列长度 $N$ 呈二次方增长，导致处理长序列时成本过高。top-$k$ 注意力是一种有前景的解决方案，它仅选择 $k$ 个最相关的 token，在显著降低计算需求的同时，性能与普通自注意力相当。然而，因果掩码要求当前查询 token 只能关注过去的 token，这限制了现有 top-$k$ 注意力方法并行搜索最相关 token 的能力，从而影响了训练效率。为此，我们提出了 ZETA，利用 	extbf{Z}-Order 曲线实现 	extbf{E}fficient 	extbf{T}op-$k$ 	extbf{A}ttention，支持对整个序列的过去 token 进行并行查询。% 其空间和时间复杂度均为 $\mathcal{O}(N \log N)$。我们首先从理论上分析了键和查询维度选择中的维度灾难与投影后相对距离保持之间的权衡，并提出了减少键和查询维度的策略。通过 $Z$-order 曲线将低维键和查询映射到一维空间，实现了并行排序，显著提升了 top-$k$ token 选择的效率。实验表明，ZETA 在 	extsc{Multi-Query Associative Recall} 任务上表现与标准注意力相当，并在 	extsc{Long Range Arena} 和 	extsc{WikiText-103} 语言建模任务上优于注意力和其变体。

> Over recent years, the Transformer has become a fundamental building block for sequence modeling architectures. Yet at its core is the use of self-attention, whose memory and computational cost grow quadratically with the sequence length $N$, rendering it prohibitively expensive for long sequences. A promising approach is top-$k$ attention, which selects only the $k$ most relevant tokens and achieves performance comparable to vanilla self-attention while significantly reducing space and computational demands. However, causal masks require the current query token to only attend to past tokens, preventing the existing top-$k$ attention method from efficiently searching for the most relevant tokens in parallel, thereby limiting training efficiency. In this work, we propose ZETA, leveraging \textbf{Z}-Order Curves for \textbf{E}fficient \textbf{T}op-$k$ \textbf{A}ttention, to enable parallel querying of past tokens for entire sequences. % in both space and time complexity of $\mathcal{O}(N \log N)$. We first theoretically show that the choice of key and query dimensions involves a trade-off between the curse of dimensionality and the preservation of relative distances after projection. In light of this insight, we propose reducing the dimensionality of keys and queries in contrast to values and further leverage $Z$-order curves to map low-dimensional keys and queries into \emph{one}-dimensional space, which permits parallel sorting, thereby largely improving the efficiency for top-$k$ token selection. Experimental results demonstrate that ZETA matches the performance of standard attention on the synthetic \textsc{Multi-Query Associative Recall} task and outperforms attention and its variants on \textsc{Long Range Arena} and \textsc{WikiText-103} language modeling.

[Arxiv](https://arxiv.org/abs/2501.14577)