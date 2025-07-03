# 重新审视离散标记：将其作为连续自回归图像生成的关键条件

发布时间：2025年07月02日

`其他

摘要讨论了视觉生成模型的改进，特别是通过自回归框架预测连续令牌的方法，属于视觉生成技术的范畴，而非直接涉及大型语言模型的应用或理论。因此，归类为其他。` `计算机视觉` `图像生成`

> Rethinking Discrete Tokens: Treating Them as Conditions for Continuous Autoregressive Image Synthesis

# 摘要

> 大型语言模型的最新进展激发了将图像编码为离散令牌并借助自回归框架进行视觉生成的研究热潮。然而，基于AR的视觉生成模型在量化过程中不可避免地造成信息损失，从而降低了图像质量。针对这一问题，研究者们提出了一种新的自回归预测连续令牌的方法。与存在于结构化且有限空间的离散令牌不同，连续表示存在于无界、高维空间中，这使得密度估计更加困难，并提高了生成异常样本的风险。基于这一发现，本研究提出了一种创新性的DisCon（离散条件连续自回归模型）框架，将离散令牌重新定义为条件信号，而非直接的生成目标。通过建模连续表示在离散令牌条件下的概率分布，DisCon不仅克服了连续令牌建模的优化难题，还成功避免了量化过程中的信息损失。实验结果显示，DisCon在ImageNet 256×256图像生成任务中达到了1.38的gFID分数，显著超越现有自回归方法的性能。

> Recent advances in large language models (LLMs) have spurred interests in encoding images as discrete tokens and leveraging autoregressive (AR) frameworks for visual generation. However, the quantization process in AR-based visual generation models inherently introduces information loss that degrades image fidelity. To mitigate this limitation, recent studies have explored to autoregressively predict continuous tokens. Unlike discrete tokens that reside in a structured and bounded space, continuous representations exist in an unbounded, high-dimensional space, making density estimation more challenging and increasing the risk of generating out-of-distribution artifacts. Based on the above findings, this work introduces DisCon (Discrete-Conditioned Continuous Autoregressive Model), a novel framework that reinterprets discrete tokens as conditional signals rather than generation targets. By modeling the conditional probability of continuous representations conditioned on discrete tokens, DisCon circumvents the optimization challenges of continuous token modeling while avoiding the information loss caused by quantization. DisCon achieves a gFID score of 1.38 on ImageNet 256$\times$256 generation, outperforming state-of-the-art autoregressive approaches by a clear margin.

[Arxiv](https://arxiv.org/abs/2507.01756)