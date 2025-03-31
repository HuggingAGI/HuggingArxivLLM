# LLMs 中大规模激活的精细分析

发布时间：2025年03月28日

`LLM理论

理由：这篇论文深入探讨了大型语言模型（LLMs）中的大规模激活值，分析了不同模型架构中的问题，并提出了新的理论和缓解策略，属于理论研究的范畴。` `人工智能` `机器学习`

> A Refined Analysis of Massive Activations in LLMs

# 摘要

> 由于其在低精度训练和量化中的重要性，大型语言模型（LLMs）中的大规模激活值成为研究焦点。然而，现有研究在范围和跨架构适用性上存在局限。本文通过对多种架构（包括基于GLU和非基于GLU的模型）中的大规模激活值进行分析，填补了这一研究空白。我们的研究结果挑战了先前的假设：(1)并非所有大规模激活值都是有害的，抑制它们并不一定会导致困惑度爆炸或任务性能崩溃；(2)如注意力KV偏置等缓解策略具有模型特异性，在某些情况下效果不佳。因此，我们探索了新型混合缓解策略；特别是将目标方差重缩放（TVR）与注意力KV偏置或动态Tanh（DyT）相结合，在我们研究的场景中成功实现了大规模激活值缓解与下游模型性能保留之间的平衡。我们的代码可在以下链接获取：https://github.com/bluorion-com/refine_massive_activations。

> Motivated in part by their relevance for low-precision training and quantization, massive activations in large language models (LLMs) have recently emerged as a topic of interest. However, existing analyses are limited in scope, and generalizability across architectures is unclear. This paper helps address some of these gaps by conducting an analysis of massive activations across a broad range of LLMs, including both GLU-based and non-GLU-based architectures. Our findings challenge several prior assumptions, most importantly: (1) not all massive activations are detrimental, i.e. suppressing them does not lead to an explosion of perplexity or a collapse in downstream task performance; (2) proposed mitigation strategies such as Attention KV bias are model-specific and ineffective in certain cases. We consequently investigate novel hybrid mitigation strategies; in particular pairing Target Variance Rescaling (TVR) with Attention KV bias or Dynamic Tanh (DyT) successfully balances the mitigation of massive activations with preserved downstream model performance in the scenarios we investigated. Our code is available at: https://github.com/bluorion-com/refine_massive_activations.

[Arxiv](https://arxiv.org/abs/2503.22329)