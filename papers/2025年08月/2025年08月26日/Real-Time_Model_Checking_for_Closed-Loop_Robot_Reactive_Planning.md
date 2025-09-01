# 闭环机器人反应式规划的实时模型检查

发布时间：2025年08月26日

`Agent` `交通运输`

> Real-Time Model Checking for Closed-Loop Robot Reactive Planning

# 摘要

> 我们提出了模型检查的一项新应用，实现了真实自主机器人的实时多步规划与避障。我们研发了一种小型专用模型检查算法，借鉴生物智能体的“核心”知识与注意力机制，现场生成规划——在低功耗设备上无需预计算数据，即可实时完成。该方法通过链接临时控制系统实现：这些系统被动态生成，用以抵消局部环境中的干扰，防止自主智能体偏离其首选动作（或静止状态）。我们还采用了对局部环境有界变化敏感的新颖二维激光雷达数据离散化方法。此外，我们将基于前向深度优先搜索的模型检查多步规划应用于死胡同和游乐场场景。两个基本属性的实证结果与非正式证明表明，模型检查可生成高效的局部避障多步规划，性能优于仅能规划单步的反应式智能体。该研究为自动驾驶车辆领域开发安全、可靠且可解释的规划提供了指导性案例。

> We present a new application of model checking which achieves real-time multi-step planning and obstacle avoidance on a real autonomous robot. We have developed a small, purpose-built model checking algorithm which generates plans in situ based on "core" knowledge and attention as found in biological agents. This is achieved in real-time using no pre-computed data on a low-powered device. Our approach is based on chaining temporary control systems which are spawned to counteract disturbances in the local environment that disrupt an autonomous agent from its preferred action (or resting state). A novel discretization of 2D LiDAR data sensitive to bounded variations in the local environment is used. Multi-step planning using model checking by forward depth-first search is applied to cul-de-sac and playground scenarios. Both empirical results and informal proofs of two fundamental properties of our approach demonstrate that model checking can be used to create efficient multi-step plans for local obstacle avoidance, improving on the performance of a reactive agent which can only plan one step. Our approach is an instructional case study for the development of safe, reliable and explainable planning in the context of autonomous vehicles.

[Arxiv](https://arxiv.org/abs/2508.19186)