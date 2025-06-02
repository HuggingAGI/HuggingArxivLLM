# # CLaSp: 上下文层跳过自推测解码

发布时间：2025年05月30日

`LLM应用` `计算机科学`

> CLaSp: In-Context Layer Skip for Self-Speculative Decoding

# 摘要

> Speculative Decoding（SD）是一种加速大型语言模型（LLMs）解码过程的有前景方法。其效率主要依赖于草稿模型与验证模型的一致性。然而，现有草稿方法通常需要额外模块训练，这在实现和跨LLMs兼容性方面面临挑战。本文提出CLaSp，一种用于自我推测解码的上下文层跳过策略。与传统方法不同，CLaSp无需额外草稿模块或训练，而是通过跳过验证模型的中间层，采用即插即用机制构建压缩草稿模型。具体而言，我们开发了一种动态规划算法，利用上一验证阶段完整的隐藏状态作为目标，优化层跳过过程。这使CLaSp能够动态调整层跳过策略，无需依赖预先优化的跳过层集合。实验结果表明，CLaSp在LLaMA3系列模型上实现了1.3倍至1.7倍的速度提升，同时保持了生成文本的原始分布。

> Speculative decoding (SD) is a promising method for accelerating the decoding process of Large Language Models (LLMs). The efficiency of SD primarily hinges on the consistency between the draft model and the verify model. However, existing drafting approaches typically require additional modules to be trained, which can be challenging to implement and ensure compatibility across various LLMs. In this paper, we propose CLaSp, an in-context layer-skipping strategy for self-speculative decoding. Unlike prior methods, CLaSp does not require additional drafting modules or extra training. Instead, it employs a plug-and-play mechanism by skipping intermediate layers of the verify model to construct a compressed draft model. Specifically, we develop a dynamic programming algorithm that optimizes the layer-skipping process by leveraging the complete hidden states from the last verification stage as an objective. This enables CLaSp to dynamically adjust its layer-skipping strategy after each verification stage, without relying on pre-optimized sets of skipped layers. Experimental results across diverse downstream tasks demonstrate that CLaSp achieves a speedup of 1.3x ~ 1.7x on LLaMA3 series models without altering the original distribution of the generated text.

[Arxiv](https://arxiv.org/abs/2505.24196)