# # 差异性隐私剪裁SGD：任意剪裁水平下的高概率收敛

发布时间：2025年07月31日

`LLM理论` `机器学习`

> Differentially Private Clipped-SGD: High-Probability Convergence with Arbitrary Clipping Level

# 摘要

> 梯度裁剪是深度学习中的重要工具，它在训练大型语言模型时常见的重尾噪声环境下，提升随机一阶方法（如SGD、AdaGrad和Adam）的高概率收敛性。同时，它也是差分隐私（DP）机制的关键组成部分。然而，现有的高概率收敛分析通常要求裁剪阈值随着优化步骤的增加而增加，这与标准的DP机制（如高斯机制）不兼容。在这项研究中，我们填补了这一空白，首次为具有固定裁剪水平的DP-Clipped-SGD提供了高概率收敛分析，适用于具有重尾噪声的凸和非凸光滑优化问题，其特征是中心α阶矩有界，α∈(1,2]。我们的结果显示，通过固定裁剪水平，该方法能够以比现有方法更快的速率收敛到最优解的邻域。该邻域可以与DP引入的噪声相平衡，从而在收敛速度和隐私保证之间提供一个更精细的权衡。

> Gradient clipping is a fundamental tool in Deep Learning, improving the high-probability convergence of stochastic first-order methods like SGD, AdaGrad, and Adam under heavy-tailed noise, which is common in training large language models. It is also a crucial component of Differential Privacy (DP) mechanisms. However, existing high-probability convergence analyses typically require the clipping threshold to increase with the number of optimization steps, which is incompatible with standard DP mechanisms like the Gaussian mechanism. In this work, we close this gap by providing the first high-probability convergence analysis for DP-Clipped-SGD with a fixed clipping level, applicable to both convex and non-convex smooth optimization under heavy-tailed noise, characterized by a bounded central $α$-th moment assumption, $α\in (1,2]$. Our results show that, with a fixed clipping level, the method converges to a neighborhood of the optimal solution with a faster rate than the existing ones. The neighborhood can be balanced against the noise introduced by DP, providing a refined trade-off between convergence speed and privacy guarantees.

[Arxiv](https://arxiv.org/abs/2507.23512)