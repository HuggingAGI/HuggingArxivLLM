# 面向鲁棒多智能体机器人系统的可解释AI增强监督控制

发布时间：2025年09月18日

`Agent` `工业与制造`

> Explainable AI-Enhanced Supervisory Control for Robust Multi-Agent Robotic Systems

# 摘要

> 我们提出了一种可解释AI增强的多智能体机器人监督控制框架，该框架整合了三部分核心技术：（i）时序自动机监督器，确保模式切换安全且可审计；（ii）鲁棒连续控制算法，包括用于大角度机动的李雅普诺夫控制器，以及带边界层的滑模控制器（SMC）以提升精度和抗干扰能力；（iii）可解释预测器，能根据任务上下文映射出控制增益及预期性能指标（如能量消耗、误差）。通过蒙特卡洛驱动的优化生成训练数据，该框架可实现透明的实时性能权衡。
  我们在两个差异显著的领域验证了该方法：航天器编队飞行和自主水下航行器（AUVs）。尽管两者所处环境迥异（太空的重力/执行器偏差与水下的水动力阻力/海流），但均涉及不确定的六自由度（6-DOF）刚体动力学、相对运动控制及严格的跟踪精度要求，因此可作为通用机器人系统的典型代表。在太空任务中，监督逻辑能自动选择符合任务要求的参数；在AUV领航-跟随测试中，相同的SMC结构在随机海流下仍能保持固定偏移量，且稳态误差有界。航天器验证结果显示，与传统比例-微分（PD）控制器相比，SMC控制器实现了亚毫米级对准精度，跟踪误差降低21.7%，能耗减少81.4%；而在AUV测试中，SMC同样在随机海流下维持误差有界。这些结果充分证明，该方法在安全关键、资源受限的多智能体机器人系统中兼具可移植性和可解释性。

> We present an explainable AI-enhanced supervisory control framework for multi-agent robotics that combines (i) a timed-automata supervisor for safe, auditable mode switching, (ii) robust continuous control (Lyapunov-based controller for large-angle maneuver; sliding-mode controller (SMC) with boundary layers for precision and disturbance rejection), and (iii) an explainable predictor that maps mission context to gains and expected performance (energy, error). Monte Carlo-driven optimization provides the training data, enabling transparent real-time trade-offs.
  We validated the approach in two contrasting domains, spacecraft formation flying and autonomous underwater vehicles (AUVs). Despite different environments (gravity/actuator bias vs. hydrodynamic drag/currents), both share uncertain six degrees of freedom (6-DOF) rigid-body dynamics, relative motion, and tight tracking needs, making them representative of general robotic systems. In the space mission, the supervisory logic selects parameters that meet mission criteria. In AUV leader-follower tests, the same SMC structure maintains a fixed offset under stochastic currents with bounded steady error. In spacecraft validation, the SMC controller achieved submillimeter alignment with 21.7% lower tracking error and 81.4% lower energy consumption compared to Proportional-Derivative PD controller baselines. At the same time, in AUV tests, SMC maintained bounded errors under stochastic currents. These results highlight both the portability and the interpretability of the approach for safety-critical, resource-constrained multi-agent robotics.

[Arxiv](https://arxiv.org/abs/2509.15491)