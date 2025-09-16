# 湍流动力学的自主实时控制

发布时间：2025年09月13日

`强化学习` `交通运输` `能源与环保`

> Autonomous real-time control of turbulent dynamics

# 摘要

> 掌控湍流一直是物理学中最棘手的难题之一，其混沌无序、多尺度的动态特性在交通与能源系统中造成了大量能量耗散。在此，我们提出REACT（用于环境适应与湍流控制的强化学习）——一个完全自主的强化学习框架，可在真实环境中实现实时、自适应的闭环湍流控制。REACT部署在一款仅搭载车载传感器与伺服驱动表面的道路车辆模型上，直接通过风洞环境中的稀疏实验数据进行学习，省去了复杂的直接数值模拟和经验性湍流模型。该智能体自主形成了一套控制策略，在降低气动阻力的同时实现了净能量节约。在不依赖流体物理学先验知识的情况下，它发现通过动态抑制车辆尾迹中的时空相干流结构可最大化能量效率，性能较基于模型的基准控制器提升了两到四倍。借助物理知情训练（将数据重构为无量纲物理群与参数化输入空间），REACT离线生成了一个具备泛化能力的智能体，无需重新训练就能适应不同速度场景。这些成果将智能体学习从模拟层面推向对高雷诺数湍流的稳健、可解释的实际控制，为交通、能源及环境流动领域的自优化物理系统铺平了道路。

> Mastering turbulence remains one of physics' most intractable challenges, with its chaotic, multi-scale dynamics driving energy dissipation across transport and energy systems. Here we report REACT (Reinforcement Learning for Environmental Adaptation and Control of Turbulence), a fully autonomous reinforcement learning framework that achieves real-time, adaptive, closed-loop turbulence control in real-world environments. Deployed on a road vehicle model equipped solely with onboard sensors and servo-actuated surfaces, REACT learns directly from sparse experimental measurements in a wind tunnel environment, bypassing intractable direct numerical simulations and empirical turbulence models. The agent autonomously converges to a policy that reduces aerodynamic drag while achieving net energy savings. Without prior knowledge of flow physics, it discovers that dynamically suppressing spatio-temporally coherent flow structures in the vehicle wake maximizes energy efficiency, achieving two to four times greater performance than model-based baseline controllers. Through a physics-informed training that recasts data in terms of dimensionless physical groups and parametric input spaces, REACT synthesizes offline a single generalizable agent that transfers across speeds without retraining. These results move agentic learning beyond simulation to robust, interpretable real-world control of high-Reynolds turbulence, opening a path to self-optimizing physical systems in transport, energy and environmental flows.

[Arxiv](https://arxiv.org/abs/2509.11002)