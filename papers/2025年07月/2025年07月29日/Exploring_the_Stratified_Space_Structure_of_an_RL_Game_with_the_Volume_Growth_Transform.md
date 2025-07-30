# 探究强化学习游戏中分层空间结构的体积增长变换方法

发布时间：2025年07月29日

`LLM理论` `机器学习`

> Exploring the Stratified Space Structure of an RL Game with the Volume Growth Transform

# 摘要

> 本研究探索了用于特定强化学习（RL）游戏的Transformer模型的嵌入空间结构。具体而言，我们分析了基于Transformer的近端策略优化（PPO）模型在简单环境中如何嵌入视觉输入，其中代理需在避开“聚光灯”障碍的同时收集“硬币”。通过将Robinson等人对大型语言模型（LLMs）的体积增长变换研究扩展至RL领域，我们发现视觉硬币收集任务的标记嵌入空间并非流形，而是更适合建模为分层空间，其中局部维度可随点变化。我们进一步通过证明分层空间能实现相当一般的体积增长曲线，从而增强了Robinson的方法。最后，我们的分析表明，RL代理在采取行动时，其潜在表示会在遵循固定子策略的低局部维度时期与实现子目标（如收集物体）或环境复杂性增加（如障碍增多）时的高局部维度爆发之间交替。因此，本研究提出，分层潜在空间中维度的分布可能为RL游戏提供一个新的复杂性几何指标。

> In this work, we explore the structure of the embedding space of a transformer model trained for playing a particular reinforcement learning (RL) game. Specifically, we investigate how a transformer-based Proximal Policy Optimization (PPO) model embeds visual inputs in a simple environment where an agent must collect "coins" while avoiding dynamic obstacles consisting of "spotlights." By adapting Robinson et al.'s study of the volume growth transform for LLMs to the RL setting, we find that the token embedding space for our visual coin collecting game is also not a manifold, and is better modeled as a stratified space, where local dimension can vary from point to point. We further strengthen Robinson's method by proving that fairly general volume growth curves can be realized by stratified spaces. Finally, we carry out an analysis that suggests that as an RL agent acts, its latent representation alternates between periods of low local dimension, while following a fixed sub-strategy, and bursts of high local dimension, where the agent achieves a sub-goal (e.g., collecting an object) or where the environmental complexity increases (e.g., more obstacles appear). Consequently, our work suggests that the distribution of dimensions in a stratified latent space may provide a new geometric indicator of complexity for RL games.

[Arxiv](https://arxiv.org/abs/2507.22010)