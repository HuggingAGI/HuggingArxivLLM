# 四旋翼无人机多目标优化PID控制器设计方法

发布时间：2025年09月22日

`强化学习` `交通运输`

> Methods for Multi-objective Optimization PID Controller for quadrotor UAVs

# 摘要

> 要让无人机融入日常生活，控制器必须确保飞行稳定、能耗高效且噪音更低。比例-积分-微分（PID）控制器虽仍是主流，但对增益选择极为敏感，手动调谐常难以实现最优平衡。本文研究了四旋翼PID增益自动调谐的多种优化技术，并在统一仿真环境中对其进行验证。该仿真系统融合了基于叶素动量理论的气动模型、快速深度神经网络代理模型、六自由度刚体动力学、湍流效应，以及数据驱动的声学代理模型——后者能预测1/3倍频程谱并将其传播至地面接收器。我们对比了三类无梯度优化算法：元启发式算法、贝叶斯优化和深度强化学习。候选控制器的性能通过综合成本函数评估，该函数同时考量噪音影响范围、功耗等多项指标。元启发式算法的性能表现稳定提升，其中灰狼优化算法效果最优。贝叶斯优化虽样本效率高，但单轮迭代成本较高，且受设计域限制。在现有配置下，强化学习智能体的表现未能超越基线，说明问题设定需进一步优化。在未知任务中，经最优调谐的控制器不仅能精准跟踪轨迹，还减少了振荡、能耗及噪音排放。这些结果表明，借助黑盒搜索实现的噪声感知PID调谐，无需改动硬件即可让飞行更安静、更高效。

> Integrating unmanned aerial vehicles into daily use requires controllers that ensure stable flight, efficient energy use, and reduced noise. Proportional integral derivative controllers remain standard but are highly sensitive to gain selection, with manual tuning often yielding suboptimal trade-offs. This paper studies different optimization techniques for the automated tuning of quadrotor proportional integral derivative gains under a unified simulation that couples a blade element momentum based aerodynamic model with a fast deep neural network surrogate, six degrees of freedom rigid body dynamics, turbulence, and a data driven acoustic surrogate model that predicts third octave spectra and propagates them to ground receivers. We compare three families of gradient-free optimizers: metaheuristics, Bayesian optimization, and deep reinforcement learning. Candidate controllers are evaluated using a composite cost function that incorporates multiple metrics, such as noise footprint and power consumption, simultaneously. Metaheuristics improve performance consistently, with Grey Wolf Optimization producing optimal results. Bayesian optimization is sample efficient but carries higher per iteration overhead and depends on the design domain. The reinforcement learning agents do not surpass the baseline in the current setup, suggesting the problem formulation requires further refinement. On unseen missions the best tuned controller maintains accurate tracking while reducing oscillations, power demand, and acoustic emissions. These results show that noise aware proportional integral derivative tuning through black box search can deliver quieter and more efficient flight without hardware changes.

[Arxiv](https://arxiv.org/abs/2509.17423)