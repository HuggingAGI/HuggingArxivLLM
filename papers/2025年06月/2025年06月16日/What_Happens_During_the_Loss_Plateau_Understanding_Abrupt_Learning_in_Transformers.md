# 损失平台期发生了什么？理解Transformer中的突然学习现象。

发布时间：2025年06月16日

`LLM理论

理由：这篇论文探讨了Transformer模型在训练过程中性能提升的机制，特别是浅层模型中的现象，分析了内部表示和注意力机制的作用，属于对大型语言模型理论的研究。`

> What Happens During the Loss Plateau? Understanding Abrupt Learning in Transformers

# 摘要

> 在算法任务中训练Transformer模型时，一个引人入胜的现象常常发生：模型性能经历一段漫长的停滞期后，会突然迎来显著提升。本研究聚焦于浅层Transformer模型，深入探究了这一动态背后的运行机制。我们发现，在性能平台期内，模型通常会发展出一种可解释的部分解决方案，同时其输出表现出强烈的重复性偏见。这种输出退化现象伴随着内部表示坍塌，即不同令牌的隐藏状态变得几乎平行。我们进一步发现，最优注意力图的缓慢学习是这一过程的关键瓶颈。在平台期内，注意力配置的隐性进展为最终的快速收敛铺平了道路。直接干预注意力机制能够显著改变平台期的持续时间以及重复偏见和表示坍塌的严重程度。我们验证了这些现象——重复偏见和表示坍塌——并非仅是简单设置下的产物，它们同样在大型语言模型（如Pythia和OLMo）的早期预训练阶段显现。

> Training Transformers on algorithmic tasks frequently demonstrates an intriguing abrupt learning phenomenon: an extended performance plateau followed by a sudden, sharp improvement. This work investigates the underlying mechanisms for such dynamics, primarily in shallow Transformers. We reveal that during the plateau, the model often develops an interpretable partial solution while simultaneously exhibiting a strong repetition bias in their outputs. This output degeneracy is accompanied by internal representation collapse, where hidden states across different tokens become nearly parallel. We further identify the slow learning of optimal attention maps as a key bottleneck. Hidden progress in attention configuration during the plateau precedes the eventual rapid convergence, and directly intervening on attention significantly alters plateau duration and the severity of repetition bias and representational collapse. We validate that these identified phenomena-repetition bias and representation collapse-are not artifacts of toy setups but also manifest in the early pre-training stage of large language models like Pythia and OLMo.

[Arxiv](https://arxiv.org/abs/2506.13688)