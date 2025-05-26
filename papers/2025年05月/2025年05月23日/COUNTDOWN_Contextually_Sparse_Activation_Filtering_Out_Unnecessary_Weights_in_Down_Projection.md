# COUNTDOWN：通过上下文稀疏激活，在降维投影中过滤掉不必要的权重

发布时间：2025年05月23日

`LLM理论` `计算优化`

> COUNTDOWN: Contextually Sparse Activation Filtering Out Unnecessary Weights in Down Projection

# 摘要

> 大型语言模型规模的不断扩大带来了显著的计算低效问题。为解决这一挑战，我们提出了一种稀疏激活方法，在推理过程中选择性地关闭非必要参数，从而在前馈神经网络（FFNN）层中降低计算成本。与现有方法关注非线性门控机制不同，我们发现FFNN层的稀疏性以线性组合形式全局存在于其内部降维投影矩阵中。基于这一发现，我们提出了两种创新方法：M-COUNTDOWN利用间接系数，而D-COUNTDOWN则利用线性组合的直接系数。实验结果表明，D-COUNTDOWN在理想情况下可减少90%的计算量，性能损失仅为5.5%；而M-COUNTDOWN则提供了一种无需预测器的解决方案，在性能保留方面比现有方法高出29.4%。通过专用内核的高效实现，我们的方法成功地将理论优势转化为显著的实际加速效果。

> The growing size of large language models has created significant computational inefficiencies. To address this challenge, sparse activation methods selectively deactivates non-essential parameters during inference, reducing computational costs in FFNN layers. While existing methods focus on non-linear gating mechanisms, we hypothesize that the sparsity of the FFNN layer lies globally in the form of a linear combination over its internal down projection matrix. Based on this insight, we propose two methods: M-COUNTDOWN, leveraging indirect coefficients, and D-COUNTDOWN, utilizing direct coefficients of the linear combination. Experimental results demonstrate that D-COUNTDOWN can omit 90% of computations with performance loss as low as 5.5% ideally, while M-COUNTDOWN provides a predictor-free solution with up to 29.4% better performance preservation compared to existing methods. Our specialized kernel implementations effectively realize these theoretical gains into substantial real-world acceleration.

[Arxiv](https://arxiv.org/abs/2505.17701)