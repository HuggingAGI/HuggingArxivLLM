# TURB-Smoke：一个点源拉格朗日污染物在湍流中扩散的数据库

发布时间：2025年07月30日

`其他

理由：虽然论文提到了移动代理，但其主要研究内容是关于湍流环境中污染源定位的数据集构建和数值模拟，与智能体（Agent）的核心理论或应用无直接关联，因此归类为其他。` `环境监测` `数值模拟`

> TURB-Smoke. A database of Lagrangian pollutants emitted from point-sources and dispersed in turbulent flows

# 摘要

> 湍流环境中污染源的定位与特性识别极具挑战性，尤其是在环境监测和应急响应领域，这主要源于线索检测的稀疏、随机且不频繁特性。即使在理想化条件下，准确建模这些现象仍具有高度复杂性，通常仅能通过实验或模拟数据实现。我们推出TURB-Smoke，这是一个专为研究湍流环境中气味及污染物扩散而设计的前沿数值数据集，适用于有无平均风的场景。TURB-Smoke通过直接数值模拟三维Navier-Stokes方程生成，追踪了数亿个从五个不同点源释放的拉格朗日粒子，在完全发展的湍流中运动，从而为利用静止传感器或移动代理开发和评估源追踪策略提供了可靠的基准框架。每个粒子的轨迹在多个湍流特征时间尺度上被连续追踪，记录了其位置和局部流速。此外，我们还提供了三维及包含污染源的准二维板中的粗粒化浓度场，非常适合在不同流动条件下快速测试和优化搜索算法。

> Identifying the location and characteristics of pollution sources in turbulent flows is challenging, especially for environmental monitoring and emergency response, due to sparse, stochastic, and infrequent cue detection. Even in idealized settings, accurately modeling these phenomena remains highly complex, with realistic representations typically achievable only through experimental or simulation-based data. We introduce TURB-Smoke, a cutting-edge numerical dataset designed for investigating odor and contaminant dispersion in turbulent environments with and without mean wind. Generated via direct numerical simulations of the fully resolved three-dimensional Navier-Stokes equations, TURB-Smoke tracks hundreds of millions of Lagrangian particles released from five distinct point sources in fully developed turbulence, thus providing a reliable ground-truth framework for developing and evaluating source-tracking strategies using stationary sensors or mobile agents in realistic flows. Each particle's trajectory is continuously tracked on many characteristic turbulence timescales, recording both the position and the local flow velocity. Additionally, we provide coarse-grained concentration fields in 3D and in quasi-2D slabs containing the source, ideal for quickly testing and optimizing search algorithms under varying flow conditions.

[Arxiv](https://arxiv.org/abs/2507.22749)