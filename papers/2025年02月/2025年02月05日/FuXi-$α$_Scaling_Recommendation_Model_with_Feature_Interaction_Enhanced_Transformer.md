# FuXi-$α$: 基于特征交互增强 Transformer 的推荐模型扩展

发布时间：2025年02月05日

`LLM应用

**理由**：这篇论文主要讨论了如何通过扩展序列推荐模型来构建大规模推荐模型，并提出了FuXi-$α$模型来改进现有模型的性能。虽然论文中提到了大型语言模型（LLM）的启发，但核心内容集中在推荐系统的应用上，特别是如何通过改进模型架构来提升推荐效果。因此，这篇论文更适合归类为“LLM应用”，因为它展示了如何将LLM的思想应用于推荐系统的实际场景中。` `推荐系统`

> FuXi-$α$: Scaling Recommendation Model with Feature Interaction Enhanced Transformer

# 摘要

> # 摘要
受扩展法则和大型语言模型的启发，大规模推荐模型的研究备受瞩目。最新研究表明，将序列推荐模型扩展为大规模推荐模型是一种有效策略。当前顶尖的序列推荐模型主要依赖自注意力机制实现物品间的显式特征交互，而隐式交互则由前馈网络（FFNs）处理。然而，这些模型往往未能充分融合时间和位置信息，通常只是将其添加到注意力权重或与潜在表示混合，从而限制了模型的表达能力。近期提出的HSTU模型进一步弱化了隐式特征交互，导致性能受限。为此，我们提出了FuXi-$α$模型，引入自适应多通道自注意力机制，分别建模时间、位置和语义特征，并结合多阶段FFN增强隐式特征交互。离线实验表明，该模型优于现有模型，且随着模型规模增大，性能持续提升。此外，我们在华为音乐应用中进行的在线A/B测试显示，每位用户的平均播放歌曲数增加了$4.76\%$，平均收听时长增加了$5.10\%$。代码已开源：https://github.com/USTC-StarTeam/FuXi-alpha。

> Inspired by scaling laws and large language models, research on large-scale recommendation models has gained significant attention. Recent advancements have shown that expanding sequential recommendation models to large-scale recommendation models can be an effective strategy. Current state-of-the-art sequential recommendation models primarily use self-attention mechanisms for explicit feature interactions among items, while implicit interactions are managed through Feed-Forward Networks (FFNs). However, these models often inadequately integrate temporal and positional information, either by adding them to attention weights or by blending them with latent representations, which limits their expressive power. A recent model, HSTU, further reduces the focus on implicit feature interactions, constraining its performance. We propose a new model called FuXi-$α$ to address these issues. This model introduces an Adaptive Multi-channel Self-attention mechanism that distinctly models temporal, positional, and semantic features, along with a Multi-stage FFN to enhance implicit feature interactions. Our offline experiments demonstrate that our model outperforms existing models, with its performance continuously improving as the model size increases. Additionally, we conducted an online A/B test within the Huawei Music app, which showed a $4.76\%$ increase in the average number of songs played per user and a $5.10\%$ increase in the average listening duration per user. Our code has been released at https://github.com/USTC-StarTeam/FuXi-alpha.

[Arxiv](https://arxiv.org/abs/2502.03036)