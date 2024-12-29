# 关于按需多模态 3D 自动配送系统的联盟博弈

发布时间：2024年12月22日

`Agent`

> A Coalition Game for On-demand Multi-modal 3D Automated Delivery System

# 摘要

> 我们引入一个多模态自主配送优化框架，将其视作在两个重叠网络中运行的无人机和 ADR 车队的联盟博弈，旨在解决城市环境（包括高密度区域）中的最后一英里配送难题，以及道路路线规划和实际运营挑战。此问题被界定为受车辆电池限制、优先时间窗和建筑物阻碍等运营限制且具有时间窗约束的多仓库取送货。接着，运用联盟博弈理论探究各模式间的合作结构，以明晰车辆间的战略协作如何提升整体路线效率。为此，设计了一个广义强化学习模型，用于评估不同联盟的成本分担与分配，其中存在次可加性和非空核心。我们的方法借助端到端的深度多智能体策略梯度方法，该方法通过新颖的时空邻接邻域图注意力网络和采用异构边缘增强注意力模型的变压器架构得以增强。针对最后一英里配送应用开展了数次数值实验，密西沙加市的案例研究结果显示，尽管在图中为两种模式纳入了广泛的网络以及复杂的训练结构，但与现有的基于变压器的方法和启发式方法相比，该模型解决了实际运营限制，实现了高质量的解决方案，在非均匀数据分布上表现出色，在不同规模和配置上泛化良好，在风速和风向等随机场景下性能强劲。

> We introduce a multi-modal autonomous delivery optimization framework as a coalition game for a fleet of UAVs and ADRs operating in two overlaying networks to address last-mile delivery in urban environments, including high-density areas, road-based routing, and real-world operational challenges. The problem is defined as multiple depot pickup and delivery with time windows constrained over operational restrictions, such as vehicle battery limitation, precedence time window, and building obstruction. Subsequently, the coalition game theory is applied to investigate cooperation structures among the modes to capture how strategic collaboration among vehicles can improve overall routing efficiency. To do so, a generalized reinforcement learning model is designed to evaluate the cost-sharing and allocation to different coalitions for which sub-additive property and non-empty core exist. Our methodology leverages an end-to-end deep multi-agent policy gradient method augmented by a novel spatio-temporal adjacency neighbourhood graph attention network and transformer architecture using a heterogeneous edge-enhanced attention model. Conducting several numerical experiments on last-mile delivery applications, the result from the case study in the city of Mississauga shows that despite the incorporation of an extensive network in the graph for two modes and a complex training structure, the model addresses realistic operational constraints and achieves high-quality solutions compared with the existing transformer-based and heuristics methods and can perform well on non-homogeneous data distribution, generalizes well on the different scale and configuration, and demonstrate a robust performance under stochastic scenarios subject to wind speed and direction.

[Arxiv](https://arxiv.org/abs/2412.17252)