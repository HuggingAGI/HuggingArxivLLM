# 带有重尾噪声的随机双层优化

发布时间：2025年09月18日

`其他` `基础理论`

> Stochastic Bilevel Optimization with Heavy-Tailed Noise

# 摘要

> 本文探讨平滑双层优化问题：下层为强凸问题，上层则可能非凸。我们重点关注随机场景——算法可获取带重尾噪声的无偏随机梯度估计，这种情况在训练大型语言模型、强化学习等众多机器学习任务中极为常见。为此，我们提出嵌套循环归一化随机双层近似算法（N²SBA），用于求解ε-平稳点，其随机一阶预言机（SFO）复杂度为【数学公式】（其中κ为条件数，p∈(1,2]为噪声的中心矩阶数，σ为噪声水平）。进一步，我们将该方法专门用于非凸-强凹极小极大优化问题，可得到ε-平稳点，对应SFO复杂度为【数学公式】。值得注意的是，在有界方差（即p=2）这一特殊情形下，上述所有复杂度上界均与现有最优结果一致。

> This paper considers the smooth bilevel optimization in which the lower-level problem is strongly convex and the upper-level problem is possibly nonconvex. We focus on the stochastic setting that the algorithm can access the unbiased stochastic gradient evaluation with heavy-tailed noise, which is prevalent in many machine learning applications such as training large language models and reinforcement learning. We propose a nested-loop normalized stochastic bilevel approximation (N$^2$SBA) for finding an $ε$-stationary point with the stochastic first-order oracle (SFO) complexity of $\tilde{\mathcal{O}}\big(κ^{\frac{7p-3}{p-1}} σ^{\frac{p}{p-1}} ε^{-\frac{4 p - 2}{p-1}}\big)$, where $κ$ is the condition number, $p\in(1,2]$ is the order of central moment for the noise, and $σ$ is the noise level. Furthermore, we specialize our idea to solve the nonconvex-strongly-concave minimax optimization problem, achieving an $ε$-stationary point with the SFO complexity of $\tilde{\mathcal O}\big(κ^{\frac{2p-1}{p-1}} σ^{\frac{p}{p-1}} ε^{-\frac{3p-2}{p-1}}\big)$. All above upper bounds match the best-known results under the special case of the bounded variance setting, i.e., $p=2$.

[Arxiv](https://arxiv.org/abs/2509.14952)