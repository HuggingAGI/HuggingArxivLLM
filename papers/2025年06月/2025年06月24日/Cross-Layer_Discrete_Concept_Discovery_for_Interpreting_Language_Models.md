# 用于解释语言模型的跨层离散概念发现

发布时间：2025年06月24日

`LLM理论`

> Cross-Layer Discrete Concept Discovery for Interpreting Language Models

# 摘要

> 揭示 transformer 各层中涌现的概念仍是一个重大挑战，因为残差流以线性方式混合和复制信息，模糊了大型语言模型中特征演变的机制。当前研究主要关注单一层的神经表征，忽视了跨层叠加及其冗余。这些表征通常用于分析激活模式或映射到有限的预定义概念。为了解决这些限制，我们提出了\gls{clvqvae}，一个通过向量量化跨层映射表征的框架，在此过程中将冗余的残差流特征压缩为紧凑且可解释的概念向量。我们的方法结合了基于 top-$k$ 温度的采样和EMA代码本更新，平衡了离散潜在空间的探索与代码本多样性。我们还通过缩放球形 k-means++ 增强框架，根据方向相似性而非幅度进行聚类，更好地与词嵌入空间中的语义结构对齐。

> Uncovering emergent concepts across transformer layers remains a significant challenge because the residual stream linearly mixes and duplicates information, obscuring how features evolve within large language models. Current research efforts primarily inspect neural representations at single layers, thereby overlooking this cross-layer superposition and the redundancy it introduces. These representations are typically either analyzed directly for activation patterns or passed to probing classifiers that map them to a limited set of predefined concepts. To address these limitations, we propose \gls{clvqvae}, a framework that uses vector quantization to map representations across layers and in the process collapse duplicated residual-stream features into compact, interpretable concept vectors. Our approach uniquely combines top-$k$ temperature-based sampling during quantization with EMA codebook updates, providing controlled exploration of the discrete latent space while maintaining code-book diversity. We further enhance the framework with scaled-spherical k-means++ for codebook initialization, which clusters by directional similarity rather than magnitude, better aligning with semantic structure in word embedding space.

[Arxiv](https://arxiv.org/abs/2506.20040)