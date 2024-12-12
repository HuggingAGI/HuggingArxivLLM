# 借助扩散模型迈向接近全局最优的非线性模型预测控制

发布时间：2024年12月11日

`其他` `控制工程` `模型预测控制`

> Toward Near-Globally Optimal Nonlinear Model Predictive Control via Diffusion Models

# 摘要

> 在非线性模型预测控制（NMPC）中达成全局最优颇具挑战，原因在于其底层优化问题的非凸特性。常见的局部优化技术依赖精心挑选的初始猜测，这种非凸性常致使因局部最优而产生次优性能。为突破此限制，我们提出一种基于新型扩散模型的近全局最优 NMPC 方法，包含离线和在线两个阶段。离线阶段借助局部优化器，通过随机初始猜测对生成系统轨迹上的最优 NMPC 控制序列分布进行采样。接着，用生成的多样数据集训练扩散模型，以反映最优值的多模态分布。在线阶段，利用训练好的模型高效执行随机射击优化的变体，获取近全局最优控制序列，无需依赖任何初始猜测或在线 NMPC 求解。数值模拟表明，我们的方法效果显著，与 NMPC 的直接神经网络近似相比性能优势明显，且计算时间大幅低于使用全局优化器在线求解 NMPC。

> Achieving global optimality in nonlinear model predictive control (NMPC) is challenging due to the non-convex nature of the underlying optimization problem. Since commonly employed local optimization techniques depend on carefully chosen initial guesses, this non-convexity often leads to suboptimal performance resulting from local optima. To overcome this limitation, we propose a novel diffusion model-based approach for near-globally optimal NMPC consisting of an offline and an online phase. The offline phase employs a local optimizer to sample from the distribution of optimal NMPC control sequences along generated system trajectories through random initial guesses. Subsequently, the generated diverse data set is used to train a diffusion model to reflect the multi-modal distribution of optima. In the online phase, the trained model is leveraged to efficiently perform a variant of random shooting optimization to obtain near-globally optimal control sequences without relying on any initial guesses or online NMPC solving. The effectiveness of our approach is illustrated in a numerical simulation indicating high performance benefits compared to direct neural network approximations of NMPC and significantly lower computation times than online solving NMPC using global optimizers.

[Arxiv](https://arxiv.org/abs/2412.08278)