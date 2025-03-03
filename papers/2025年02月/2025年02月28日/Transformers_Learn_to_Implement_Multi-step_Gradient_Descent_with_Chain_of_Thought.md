# Transformer模型掌握运用链式思维实现多步梯度下降。

发布时间：2025年02月28日

`LLM理论` `机器学习`

> Transformers Learn to Implement Multi-step Gradient Descent with Chain of Thought

# 摘要

> 链式思维（CoT）提示能显著提升大型语言模型（LLMs）的表现，尤其在算术和推理任务中，通过引导模型生成中间推理步骤。尽管CoT在经验上表现优异，并在提升模型表达能力方面具有理论优势，但其训练机制仍 largely 未被深入研究。本文聚焦于线性回归任务中的上下文权重预测，探讨transformer在基于CoT目标下的训练动态。我们证明，没有CoT的一层线性transformer只能实现单步梯度下降（GD），且无法恢复真实权重向量；而带有CoT提示的transformer能够自回归地执行多步GD，实现近似精确的恢复。此外，我们发现训练后的transformer在未见数据上表现优异，具备良好的泛化能力。通过我们的技术，我们还发现，在线性回归的上下文学习中，循环transformer相较于无循环transformer能显著提升最终性能。经验结果进一步证实了CoT提示带来的显著性能提升。


> Chain of Thought (CoT) prompting has been shown to significantly improve the performance of large language models (LLMs), particularly in arithmetic and reasoning tasks, by instructing the model to produce intermediate reasoning steps. Despite the remarkable empirical success of CoT and its theoretical advantages in enhancing expressivity, the mechanisms underlying CoT training remain largely unexplored. In this paper, we study the training dynamics of transformers over a CoT objective on an in-context weight prediction task for linear regression. We prove that while a one-layer linear transformer without CoT can only implement a single step of gradient descent (GD) and fails to recover the ground-truth weight vector, a transformer with CoT prompting can learn to perform multi-step GD autoregressively, achieving near-exact recovery. Furthermore, we show that the trained transformer effectively generalizes on the unseen data. With our technique, we also show that looped transformers significantly improve final performance compared to transformers without looping in the in-context learning of linear regression. Empirically, we demonstrate that CoT prompting yields substantial performance improvements.

[Arxiv](https://arxiv.org/abs/2502.21212)