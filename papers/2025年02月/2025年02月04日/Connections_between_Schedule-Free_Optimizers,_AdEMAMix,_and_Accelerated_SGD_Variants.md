# 无调度优化器、AdEMAMix 与加速 SGD 变体之间的关联

发布时间：2025年02月04日

`其他

理由：这篇论文主要讨论的是深度学习优化算法（如 Schedule-Free 优化器、AdEMAMix、MARS 和 Lion）的改进和理论分析，特别是与随机梯度下降（SGD）的关系。虽然论文提到了语言建模任务，但其核心内容并不直接涉及大型语言模型（LLM）的应用、理论、Agent 或 RAG（Retrieval-Augmented Generation）。因此，这篇论文更适合归类为“其他”。` `优化算法`

> Connections between Schedule-Free Optimizers, AdEMAMix, and Accelerated SGD Variants

# 摘要

> # 摘要
深度学习优化领域的最新进展带来了诸如 Schedule-Free 优化器、AdEMAMix、MARS 和 Lion 等新算法，它们革新了传统的动量机制。与此同时，通过解耦动量系数与当前梯度的权重，随机梯度下降（SGD）在噪声主导的机制中实现了理论加速。本文在这两项工作之间建立了明确的联系，并通过 150m 语言建模任务的初步实验验证了理论发现。结果显示，AdEMAMix 最接近加速版的 SGD，表现尤为出色。基于此，我们提出了 Simplified-AdEMAMix，它在大小批量设置下保持了与 AdEMAMix 相同的性能，同时简化了动量项的使用。Simplified-AdEMAMix 的代码已开源：https://github.com/DepenM/Simplified-AdEMAMix/。

> Recent advancements in deep learning optimization have introduced new algorithms, such as Schedule-Free optimizers, AdEMAMix, MARS and Lion which modify traditional momentum mechanisms. In a separate line of work, theoretical acceleration of stochastic gradient descent (SGD) in noise-dominated regime has been achieved by decoupling the momentum coefficient from the current gradient's weight. In this paper, we establish explicit connections between these two lines of work. We substantiate our theoretical findings with preliminary experiments on a 150m language modeling task. We find that AdEMAMix, which most closely resembles accelerated versions of stochastic gradient descent, exhibits superior performance. Building on these insights, we introduce a modification to AdEMAMix, termed Simplified-AdEMAMix, which maintains the same performance as AdEMAMix across both large and small batch-size settings while eliminating the need for two different momentum terms. The code for Simplified-AdEMAMix is available on the repository: https://github.com/DepenM/Simplified-AdEMAMix/.

[Arxiv](https://arxiv.org/abs/2502.02431)