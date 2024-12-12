# 通过交错文本和数字嵌入来解决数学问题

发布时间：2024年10月25日

`LLM应用` `语言模型`

> Interleaving Text and Number Embeddings to Solve Mathemathics Problems

# 摘要

> 有效地融合文本与数字，是提升大型语言模型（LLMs）辅助科学任务能力的关键一步。当前多数方法依赖于对数字进行离散标记化，比如转化为科学记数法或十进制分解，而近期有方法提出将连续数字编码作为归纳偏差。在本文中，我们基于此引入了更具表现力的数字嵌入。我们的方法解决了一些关键缺陷，包括消除数字伪影以及能够在不截断的情况下处理各种量级。
  我们的工作有两大关键贡献。其一，我们运用多层感知机（MLP）为嵌入空间中的不同数字赋予不同方向。其二，我们引入了一个路由层，用于区分数字和文本嵌入。我们推测这种组合方式能让模型区分文本和数字分布，同时保持其算术运算能力。
  仅使用 45 M 参数的编码器 - 解码器架构，我们的方法在广泛量级（$10^{-3},10^{8}$）范围内实现了$R^2$=0.9988。此外，通过实践观察，相较于基线，数字伪影和偏差有所减少。

> Integrating text and numbers effectively is a crucial step towards enhancing Large Language Models (LLMs) capabilities in assisting in scientific tasks. While most current approaches rely on discrete tokenization of numbers, for instance, conversion to scientific notation or base 10-decomposition, a recent approach proposed a continuous numerical encoding as an inductive bias. In this paper, we build upon this approach by introducing more expressive numerical embeddings. Our method addresses key shortcomings, including the elimination of numerical artefacts and the ability to handle a wide range of magnitudes without clipping.
  Our work presents two key contributions. First, we employ an MLP to assign distinct directions in the embedding space to different numbers. Our second contribution is the introduction of a routing layer that differentiates between numerical and text embeddings. We hypothesise that this combined approach enables the model to distinguish between text and number distributions while maintaining its capacity for arithmetic operations.
  Using only a 45 M parameter encoder-decoder architecture our method achieves a $R^2$=0.9988 over a wide range of magnitude ($10^{-3},10^{8}$). In addition, we empirically observe a reduction of the numerical artefacts and biases observed compared to the baselines.

[Arxiv](https://arxiv.org/abs/2410.19353)