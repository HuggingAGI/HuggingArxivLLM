# 基于 LLM 推理的 CTR 可解释性预测

发布时间：2024年12月03日

`LLM应用` `推荐系统` `用户体验`

> Explainable CTR Prediction via LLM Reasoning

# 摘要

> 推荐系统已成为现代用户体验的重要组成部分，但其决策过程缺乏透明度。现有的可解释推荐方法受困于依赖事后范式，即解释生成器与底层推荐模型分开训练。这种范式需要大量人力构建数据，还让人对解释的可靠性产生担忧。在本文中，我们推出了 ExpCTR 这一新框架，它将基于大型语言模型的解释生成直接融入 CTR 预测过程。受近期强化学习进展的启发，我们采用了两种精心设计的奖励机制，即 LC 对齐（确保解释反映用户意图）和 IC 对齐（与传统基于 ID 的 CTR 模型保持一致）。我们的方法结合了带有 LoRA 的高效训练范式和一个三阶段迭代过程。ExpCTR 无需大量解释数据集，同时促进了 CTR 预测与解释生成的协同。实验结果表明，ExpCTR 在三个真实世界的数据集中显著提升了推荐的准确性和可解释性。

> Recommendation Systems have become integral to modern user experiences, but lack transparency in their decision-making processes. Existing explainable recommendation methods are hindered by reliance on a post-hoc paradigm, wherein explanation generators are trained independently of the underlying recommender models. This paradigm necessitates substantial human effort in data construction and raises concerns about explanation reliability. In this paper, we present ExpCTR, a novel framework that integrates large language model based explanation generation directly into the CTR prediction process. Inspired by recent advances in reinforcement learning, we employ two carefully designed reward mechanisms, LC alignment, which ensures explanations reflect user intentions, and IC alignment, which maintains consistency with traditional ID-based CTR models. Our approach incorporates an efficient training paradigm with LoRA and a three-stage iterative process. ExpCTR circumvents the need for extensive explanation datasets while fostering synergy between CTR prediction and explanation generation. Experimental results demonstrate that ExpCTR significantly enhances both recommendation accuracy and interpretability across three real-world datasets.

[Arxiv](https://arxiv.org/abs/2412.02588)