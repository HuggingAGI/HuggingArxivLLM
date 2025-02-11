# Jakiro：利用 MoE 解耦多头机制，提升投机性解码性能

发布时间：2025年02月10日

`LLM应用

理由：这篇论文专注于优化大型语言模型的推理过程，提出了一种新的方法 Jakiro 来提升Speculative Decoding的效率和准确性。它属于将LLM应用于实际任务并进行优化的范畴，因此归类为LLM应用。` `人工智能` `模型优化`

> Jakiro: Boosting Speculative Decoding with Decoupled Multi-Head via MoE

# 摘要

> Speculative Decoding（SD）通过较小的草稿模型预测多个token，再由较大的目标模型并行验证，从而加速大型语言模型的推理。然而，草稿模型容量有限，通常需要基于树的采样来提高预测准确性，每一步生成多个候选。我们发现这种方法的关键限制：同一步骤中的候选来自相同的表示，导致多样性和整体效果受限。为解决此问题，我们提出了 Jakiro，利用专家混合（MoE），独立专家生成多样化预测，有效解耦候选间的相关性。此外，我们引入了混合推理策略，结合自回归解码用于初始token，以及并行解码用于后续阶段，并通过特征对比机制增强后者以提高准确性。我们的方法显著提升了预测准确性和推理速度。跨多种模型的广泛实验验证了方法的有效性和鲁棒性，树立了Speculative Decoding的新SOTA。代码已开源：https://github.com/haiduo/Jakiro。

> Speculative decoding (SD) accelerates large language model inference by using a smaller draft model to predict multiple tokens, which are then verified in parallel by the larger target model. However, the limited capacity of the draft model often necessitates tree-based sampling to improve prediction accuracy, where multiple candidates are generated at each step. We identify a key limitation in this approach: the candidates at the same step are derived from the same representation, limiting diversity and reducing overall effectiveness. To address this, we propose Jakiro, leveraging Mixture of Experts (MoE), where independent experts generate diverse predictions, effectively decoupling correlations among candidates. Furthermore, we introduce a hybrid inference strategy, combining autoregressive decoding for initial tokens with parallel decoding for subsequent stages, and enhance the latter with contrastive mechanism in features to improve accuracy. Our method significantly boosts prediction accuracy and achieves higher inference speedups. Extensive experiments across diverse models validate the effectiveness and robustness of our approach, establishing a new SOTA in speculative decoding. Our codes are available at https://github.com/haiduo/Jakiro.

[Arxiv](https://arxiv.org/abs/2502.06282)