# 贝叶斯逆问题的稳定无导数高斯混合变分推断

发布时间：2025年01月07日

`其他

理由：这篇论文主要讨论的是概率分布近似问题，特别是科学计算中的贝叶斯推断方法。虽然涉及了一些数学和计算方法，但内容与Agent、RAG、LLM应用或LLM理论没有直接关联。因此，将其分类为“其他”更为合适。` `科学计算` `贝叶斯推断`

> Stable Derivative Free Gaussian Mixture Variational Inference for Bayesian Inverse Problems

# 摘要

> 本文聚焦于已知归一化常数的概率分布近似问题，特别是科学计算中大规模反问题的贝叶斯推断。面对前向模型的高成本重复评估、多模态性和不可访问梯度等挑战，我们提出了一个结合Fisher-Rao自然梯度和专门积分规则的变分推断框架，实现了高斯混合变分族的无导数更新。这一方法，即无导数高斯混合变分推断（DF-GMVI），确保了协方差的正定性和仿射不变性，为复杂后验分布的近似提供了一个稳定高效的框架。DF-GMVI的有效性通过数值实验在多个挑战性场景中得到了验证，包括多模态、无限模态和高维空间中的弯曲模态分布。此外，该方法在一个大规模应用中成功恢复了Navier-Stokes方程的初始条件，进一步证明了其实用性。

> This paper is concerned with the approximation of probability distributions known up to normalization constants, with a focus on Bayesian inference for large-scale inverse problems in scientific computing. In this context, key challenges include costly repeated evaluations of forward models, multimodality, and inaccessible gradients for the forward model. To address them, we develop a variational inference framework that combines Fisher-Rao natural gradient with specialized quadrature rules to enable derivative free updates of Gaussian mixture variational families. The resulting method, termed Derivative Free Gaussian Mixture Variational Inference (DF-GMVI), guarantees covariance positivity and affine invariance, offering a stable and efficient framework for approximating complex posterior distributions. The effectiveness of DF-GMVI is demonstrated through numerical experiments on challenging scenarios, including distributions with multiple modes, infinitely many modes, and curved modes in spaces with up to hundreds of dimensions. The method's practicality is further demonstrated in a large-scale application, where it successfully recovers the initial conditions of the Navier-Stokes equations from solution data at positive times.

[Arxiv](https://arxiv.org/abs/2501.04259)