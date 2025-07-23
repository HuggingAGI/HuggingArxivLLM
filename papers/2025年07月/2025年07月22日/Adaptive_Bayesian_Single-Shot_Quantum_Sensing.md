# 单次自适应贝叶斯量子传感

发布时间：2025年07月22日

`其他` `量子传感` `量子计算`

> Adaptive Bayesian Single-Shot Quantum Sensing

# 摘要

> 量子传感凭借量子系统独特性质，突破传统传感器极限，实现对时间、磁场、电场、加速度及重力梯度等物理量的高精度测量。然而，选择合适的传感探针和测量方案在经典计算中往往难以处理，因需在高维希尔伯特空间中优化。在变分量子传感中，参数化量子电路（PQC）生成探针量子系统，通过量子信道暴露于未知物理参数，随后测量以收集经典数据。通常，PQC和测量过程基于频率主义学习准则采用离线优化策略。本文提出了一种自适应协议，利用贝叶斯推理，通过最大化主动信息增益优化传感策略。该变分方法专为非渐近场景设计，每次时间步仅部署一个探针，并扩展支持来自多个量子传感代理的估计融合。

> Quantum sensing harnesses the unique properties of quantum systems to enable precision measurements of physical quantities such as time, magnetic and electric fields, acceleration, and gravitational gradients well beyond the limits of classical sensors. However, identifying suitable sensing probes and measurement schemes can be a classically intractable task, as it requires optimizing over Hilbert spaces of high dimension. In variational quantum sensing, a probe quantum system is generated via a parameterized quantum circuit (PQC), exposed to an unknown physical parameter through a quantum channel, and measured to collect classical data. PQCs and measurements are typically optimized using offline strategies based on frequentist learning criteria. This paper introduces an adaptive protocol that uses Bayesian inference to optimize the sensing policy via the maximization of the active information gain. The proposed variational methodology is tailored for non-asymptotic regimes where a single probe can be deployed in each time step, and is extended to support the fusion of estimates from multiple quantum sensing agents.

[Arxiv](https://arxiv.org/abs/2507.16477)