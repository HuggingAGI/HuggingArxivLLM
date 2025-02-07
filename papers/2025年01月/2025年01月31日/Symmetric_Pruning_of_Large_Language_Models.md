# 大型语言模型的对称剪枝

发布时间：2025年01月31日

`其他

理由：这篇论文主要讨论的是训练后剪枝方法的理论基础和优化策略，特别是Wanda和RIA方法的理论分析和改进。虽然这些方法可能与大型语言模型（LLM）相关，但论文的核心内容并不直接涉及LLM的应用、理论、Agent或RAG（Retrieval-Augmented Generation）。因此，将其分类为“其他”更为合适。` `机器学习` `模型优化`

> Symmetric Pruning of Large Language Models

# 摘要

> # 摘要
Wanda和RIA等流行的训练后剪枝方法以其简洁高效的设计著称，展现了卓越的实证性能。Wanda通过剪枝时的激活校准优化性能，RIA则注重权重元素的相对重要性。尽管这些方法在实践中表现出色，但缺乏解释其成功的全面理论基础。本文提出新的理论见解，重新定义了剪枝的最小化目标，深入剖析了其成功的关键因素。我们不仅限于理论分析，还提出了综合考虑输入激活和权重重要性的补充策略，并通过严格实验验证了这些方法的显著优势。此外，我们创新性地提出了一种无需训练的微调方法$R^2$-DSnoT，该方法在动态剪枝与生长框架中融合了相对权重重要性和正则化决策边界，大幅超越现有基线，树立了新的技术标杆。

> Popular post-training pruning methods such as Wanda and RIA are known for their simple, yet effective, designs that have shown exceptional empirical performance. Wanda optimizes performance through calibrated activations during pruning, while RIA emphasizes the relative, rather than absolute, importance of weight elements. Despite their practical success, a thorough theoretical foundation explaining these outcomes has been lacking. This paper introduces new theoretical insights that redefine the standard minimization objective for pruning, offering a deeper understanding of the factors contributing to their success. Our study extends beyond these insights by proposing complementary strategies that consider both input activations and weight significance. We validate these approaches through rigorous experiments, demonstrating substantial enhancements over existing methods. Furthermore, we introduce a novel training-free fine-tuning approach $R^2$-DSnoT that incorporates relative weight importance and a regularized decision boundary within a dynamic pruning-and-growing framework, significantly outperforming strong baselines and establishing a new state of the art.

[Arxiv](https://arxiv.org/abs/2501.18980)