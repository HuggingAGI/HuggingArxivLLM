# L²M：长上下文语言建模中的互信息缩放法则

发布时间：2025年03月06日

`LLM理论` `大型语言模型`

> L$^2$M: Mutual Information Scaling Law for Long-Context Language Modeling

# 摘要

> 我们发现了一个自然语言中的二元互信息缩放定律，它决定了长程依赖关系的形成。这一缩放定律与传统的两点互信息不同，且独立于其进行缩放，它是理解长上下文语言建模的关键。基于此，我们提出了长上下文语言建模的L²M条件，该条件揭示了模型有效建模长上下文长度的能力与其潜在状态大小的缩放之间的关系。我们的研究通过transformers和状态空间模型的实验得到了验证，为大型语言模型向更长上下文长度的发展奠定了理论基础。

> We rigorously establish a bipartite mutual information scaling law in natural language that governs long-range dependencies. This scaling law, which we show is distinct from and scales independently of the conventional two-point mutual information, is the key to understanding long-context language modeling. Using this scaling law, we formulate the Long-context Language Modeling (L$^2$M) condition, which relates a model's capacity for effective long context length modeling to the scaling of its latent state size for storing past information. Our results are validated through experiments on both transformers and state space models. This work establishes a theoretical foundation that guides the development of large language models toward longer context lengths.

[Arxiv](https://arxiv.org/abs/2503.04725)