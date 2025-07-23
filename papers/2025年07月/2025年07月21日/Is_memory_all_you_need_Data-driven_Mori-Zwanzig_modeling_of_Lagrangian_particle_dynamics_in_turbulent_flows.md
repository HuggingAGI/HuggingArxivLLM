# 记忆是否是您所需要的全部？基于数据驱动的 Mori-Zwanzig 模型研究湍流中拉格朗日粒子动力学

发布时间：2025年07月21日

`其他` `流体力学` `机器学习`

> Is memory all you need? Data-driven Mori-Zwanzig modeling of Lagrangian particle dynamics in turbulent flows

# 摘要

> 在复杂流动中，拉格朗日粒子的湍流动力学对混合、传输和分散过程至关重要。这些粒子的轨迹展现出高度非平凡的统计特性，这促使研究者们开发代理模型，以在避免完整欧拉场直接数值模拟的高昂计算成本的同时，重现这些轨迹。然而，构建这样的模型极具挑战性，因为降阶模型通常无法获取与底层湍流场的全部交互作用。新型数据驱动的机器学习技术在捕获和重现降阶/代理动力学的复杂统计特性方面表现出巨大潜力。

在这项研究中，我们展示了一种学习代理动力学系统的方法，该系统能够以点态准确的方式进行短期预测（相对于柯尔莫哥洛夫时间），并在长期预测中保持稳定和统计上的准确性。这一方法基于摩里-赞茨格形式主义，该形式主义将完整的动力学系统分解为两部分：一部分是依赖于当前状态和一组简化的可观测量的过去历史的可解析动力学，另一部分是由于初始状态未解析自由度而导致的不可解析正交动力学。通过在短期预测的点态误差度量上训练这个降阶模型，我们成功地学习了拉格朗日湍流的动力学特性，使得在测试时也能稳定地恢复长期的统计行为。这一突破为多种新应用开辟了可能性，例如在湍流环境中对主动拉格朗日代理的控制。

> The dynamics of Lagrangian particles in turbulence play a crucial role in mixing, transport, and dispersion processes in complex flows. Their trajectories exhibit highly non-trivial statistical behavior, motivating the development of surrogate models that can reproduce these trajectories without incurring the high computational cost of direct numerical simulations of the full Eulerian field. This task is particularly challenging because reduced-order models typically lack access to the full set of interactions with the underlying turbulent field. Novel data-driven machine learning techniques can be very powerful in capturing and reproducing complex statistics of the reduced-order/surrogate dynamics. In this work, we show how one can learn a surrogate dynamical system that is able to evolve a turbulent Lagrangian trajectory in a way that is point-wise accurate for short-time predictions (with respect to Kolmogorov time) and stable and statistically accurate at long times. This approach is based on the Mori--Zwanzig formalism, which prescribes a mathematical decomposition of the full dynamical system into resolved dynamics that depend on the current state and the past history of a reduced set of observables and the unresolved orthogonal dynamics due to unresolved degrees of freedom of the initial state. We show how by training this reduced order model on a point-wise error metric on short time-prediction, we are able to correctly learn the dynamics of the Lagrangian turbulence, such that also the long-time statistical behavior is stably recovered at test time. This opens up a range of new applications, for example, for the control of active Lagrangian agents in turbulence.

[Arxiv](https://arxiv.org/abs/2507.16058)