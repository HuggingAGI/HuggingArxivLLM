# AbbIE：基于自回归块的迭代编码器，实现高效序列建模

发布时间：2025年07月11日

`LLM理论

理由：这篇论文提出了自回归块迭代编码器（AbbIE），这是一种改进Transformer架构的方法，旨在提升大型语言模型的性能和资源利用率。论文重点在于模型结构和训练方法的优化，属于理论层面的研究，因此归类为LLM理论。` `大型语言模型`

> AbbIE: Autoregressive Block-Based Iterative Encoder for Efficient Sequence Modeling

# 摘要

> 我们提出了自回归块迭代编码器（AbbIE），这是一种对仅编码器Transformer架构的递归泛化方法。与标准Transformer相比，AbbIE不仅在困惑度上表现更优，还支持在测试阶段动态调整计算资源。作为一种简单而递归的解决方案，AbbIE为通过参数和令牌数量提升大型语言模型（LLM）性能提供了有力补充。

与潜在推理模型不同，AbbIE在潜在空间中进行迭代，但无需依赖专门的数据集或训练协议。研究发现，AbbIE仅需在训练阶段使用2次迭代即可实现向上泛化，显著超越其他迭代方法。AbbIE能够根据任务复杂性动态调整计算消耗，使其在零-shot上下文学习任务中较其他迭代和标准方法提升了	extbf{12\%}，在语言困惑度上提升了5\%。这项研究为Transformer性能扩展提供了全新思路。所有评估均在3.5亿参数规模的模型上完成。

> We introduce the Autoregressive Block-Based Iterative Encoder (AbbIE), a novel recursive generalization of the encoder-only Transformer architecture, which achieves better perplexity than a standard Transformer and allows for the dynamic scaling of compute resources at test time. This simple, recursive approach is a complement to scaling large language model (LLM) performance through parameter and token counts. AbbIE performs its iterations in latent space, but unlike latent reasoning models, does not require a specialized dataset or training protocol. We show that AbbIE upward generalizes (ability to generalize to arbitrary iteration lengths) at test time by only using 2 iterations during train time, far outperforming alternative iterative methods. AbbIE's ability to scale its computational expenditure based on the complexity of the task gives it an up to \textbf{12\%} improvement in zero-shot in-context learning tasks versus other iterative and standard methods and up to 5\% improvement in language perplexity. The results from this study open a new avenue to Transformer performance scaling. We perform all of our evaluations on model sizes up to 350M parameters.

[Arxiv](https://arxiv.org/abs/2507.08567)