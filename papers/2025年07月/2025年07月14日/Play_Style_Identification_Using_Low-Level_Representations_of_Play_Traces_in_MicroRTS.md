# 基于游戏轨迹低级特征的游戏风格识别：以MicroRTS为例

发布时间：2025年07月14日

`LLM应用` `机器学习`

> Play Style Identification Using Low-Level Representations of Play Traces in MicroRTS

# 摘要

> 游戏风格识别不仅能够为游戏设计提供独到的见解，还能支持自适应游戏体验，同时有望提升游戏代理的表现。传统方法依赖领域知识，通过手工设计特征构建游戏轨迹表示。近期方法虽融入了游戏轨迹的序列结构，但仍需一定领域抽象。本研究采用无监督CNN-LSTM自编码器模型，直接从MicroRTS的低级游戏轨迹数据中提取潜在表示。我们证明，这种方法能在潜在空间中有效区分不同游戏代理，从而减少对领域专业知识的依赖及其相关偏见。这一潜在空间随后被用于引导所研究AI玩家中多样化游戏风格的探索。

> Play style identification can provide valuable game design insights and enable adaptive experiences, with the potential to improve game playing agents. Previous work relies on domain knowledge to construct play trace representations using handcrafted features. More recent approaches incorporate the sequential structure of play traces but still require some level of domain abstraction. In this study, we explore the use of unsupervised CNN-LSTM autoencoder models to obtain latent representations directly from low-level play trace data in MicroRTS. We demonstrate that this approach yields a meaningful separation of different game playing agents in the latent space, reducing reliance on domain expertise and its associated biases. This latent space is then used to guide the exploration of diverse play styles within studied AI players.

[Arxiv](https://arxiv.org/abs/2507.10172)