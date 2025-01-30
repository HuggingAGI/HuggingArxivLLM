# 指数族注意力

发布时间：2025年01月28日

`LLM理论

理由：这篇论文主要讨论了自注意力机制的扩展——指数族注意力（EFA），这是一种概率生成模型，用于处理高维序列、空间或时空数据。虽然论文没有直接提到大型语言模型（LLM），但自注意力机制是Transformer架构的核心，而Transformer是大多数LLM的基础。因此，这篇论文属于LLM理论的范畴，因为它探讨了自注意力机制的扩展和改进，这对于理解和改进LLM的理论基础具有重要意义。` `机器学习`

> Exponential Family Attention

# 摘要

> 自注意力机制是大多数大型语言模型背后的Transformer神经网络的核心，能够捕捉自然语言中的复杂词汇模式和长距离依赖关系。本文提出了指数族注意力（EFA），这是一种概率生成模型，扩展了自注意力机制，能够处理高维序列、空间或时空数据，涵盖离散和连续观测。EFA的核心思想是将每个观测值建模为依赖于所有其他观测值（即上下文）的条件概率，其相关性通过基于注意力的潜在因子模型以数据驱动的方式学习。与静态潜在嵌入不同，EFA利用自注意力机制捕捉上下文中的动态交互，每个上下文观测值的相关性取决于其他观测值。我们证明了EFA的可识别性，并提供了关于超额损失的泛化保证。在美国城市温度、Instacart购物篮和MovieLens评分等真实世界和合成数据集中，EFA在捕捉复杂潜在结构和重建保留数据方面始终优于现有模型。

> The self-attention mechanism is the backbone of the transformer neural network underlying most large language models. It can capture complex word patterns and long-range dependencies in natural language. This paper introduces exponential family attention (EFA), a probabilistic generative model that extends self-attention to handle high-dimensional sequence, spatial, or spatial-temporal data of mixed data types, including both discrete and continuous observations. The key idea of EFA is to model each observation conditional on all other existing observations, called the context, whose relevance is learned in a data-driven way via an attention-based latent factor model. In particular, unlike static latent embeddings, EFA uses the self-attention mechanism to capture dynamic interactions in the context, where the relevance of each context observations depends on other observations. We establish an identifiability result and provide a generalization guarantee on excess loss for EFA. Across real-world and synthetic data sets -- including U.S. city temperatures, Instacart shopping baskets, and MovieLens ratings -- we find that EFA consistently outperforms existing models in capturing complex latent structures and reconstructing held-out data.

[Arxiv](https://arxiv.org/abs/2501.16790)