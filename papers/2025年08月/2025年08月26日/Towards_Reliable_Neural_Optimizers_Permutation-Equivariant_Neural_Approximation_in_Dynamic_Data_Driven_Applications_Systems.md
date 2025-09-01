# 迈向可靠的神经优化器：动态数据驱动应用系统中的置换等变神经近似

发布时间：2025年08月26日

`其他` `能源与环保`

> Towards Reliable Neural Optimizers: Permutation-Equivariant Neural Approximation in Dynamic Data Driven Applications Systems

# 摘要

> 动态数据驱动应用系统（DDDAS）催生了能适应传感器网络中流式、异构及异步数据的优化方法。许多成熟的优化求解器（如分支定界法、梯度下降法和牛顿-拉夫逊法）依赖迭代算法，其逐步收敛特性导致在实时多传感器环境中速度欠佳。在近期研究中，我们提出了LOOP-PE（学习优化优化过程，置换等变版本）——一种集成了可行性恢复函数的前馈神经近似模型。LOOP-PE能以任意顺序处理可变数量传感器的输入，因此对传感器掉线、通信延迟及系统扩展均具备鲁棒性。其置换等变架构确保输入数据重排时，相应的调度决策也会一致重排，且无需重新训练或预对齐。借助广义规范映射保障可行性，确保输出符合物理及操作约束。我们在一个受DDDAS启发的虚拟电厂（VPP）案例研究中对该方法进行了验证：该VPP管理多个分布式发电主体（DERs），在遵守系统限制的前提下最大化可再生能源利用率。结果显示，LOOP-PE在动态、无序及分布式传感条件下，能生成近最优、可行且高度自适应的决策，在速度和灵活性方面均显著优于基于迭代算法的求解器。本文通过对LOOP-PE的设计与运行机制进行额外分析和阐释，扩展了我们早期的研究，尤其着重阐述了其可行性保证与置换等变特性。

> Dynamic Data Driven Applications Systems (DDDAS) motivate the development of optimization approaches capable of adapting to streaming, heterogeneous, and asynchronous data from sensor networks. Many established optimization solvers, such as branch-and-bound, gradient descent, and Newton-Raphson methods, rely on iterative algorithms whose step-by-step convergence makes them too slow for real-time, multi-sensor environments. In our recent work, we introduced LOOP-PE (Learning to Optimize the Optimization Process, Permutation Equivariance version), a feed-forward neural approximation model with an integrated feasibility recovery function. LOOP-PE processes inputs from a variable number of sensors in arbitrary order, making it robust to sensor dropout, communication delays, and system scaling. Its permutation-equivariant architecture ensures that reordering the input data reorders the corresponding dispatch decisions consistently, without retraining or pre-alignment. Feasibility is enforced via a generalized gauge map, guaranteeing that outputs satisfy physical and operational constraints. We illustrate the approach in a DDDAS-inspired case study of a Virtual Power Plant (VPP) managing multiple distributed generation agents (DERs) to maximize renewable utilization while respecting system limits. Results show that LOOP-PE produces near-optimal, feasible, and highly adaptable decisions under dynamic, unordered, and distributed sensing conditions, significantly outperforming iterative algorithm based solvers in both speed and flexibility. Here, we extend our earlier work by providing additional analysis and explanation of LOOP-PE design and operation, with particular emphasis on its feasibility guarantee and permutation equivariance feature.

[Arxiv](https://arxiv.org/abs/2508.19364)