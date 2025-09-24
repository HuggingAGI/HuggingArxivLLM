# 提出一种用于基于活动的交通模型的新型位置分配算法：CARLA

发布时间：2025年09月19日

`Agent` `交通运输`

> Introducing a novel Location-Assignment Algorithm for Activity-Based Transport Models: CARLA

# 摘要

> 本文提出了CARLA（基于空间约束锚点的递归位置分配）算法，这是一种用于在基于活动的出行模型中分配次要或其他活动位置的递归方法。CARLA在整合位置潜力的同时最小化距离偏差，从而实现更贴合实际的活动分布。该算法将出行链分解为更小的子段，借助几何约束和可配置的启发式策略高效搜索解空间。与当前最先进的松弛-离散化方法相比，CARLA的平均偏差显著降低，即便在运行时间有限的情况下依然如此。该算法对现实数据中的不一致性（如距离不可行）具有较强鲁棒性，还能灵活适配不同优先级需求，例如侧重位置吸引力或距离准确性。凭借多功能性和高效性，CARLA成为提升基于活动的出行模型及智能体交通模拟空间精度的得力工具。相关实现可访问https://github.com/tnoud/carla获取。

> This paper introduces CARLA (spatially Constrained Anchor-based Recursive Location Assignment), a recursive algorithm for assigning secondary or any activity locations in activity-based travel models. CARLA minimizes distance deviations while integrating location potentials, ensuring more realistic activity distributions. The algorithm decomposes trip chains into smaller subsegments, using geometric constraints and configurable heuristics to efficiently search the solution space. Compared to a state-of-the-art relaxation-discretization approach, CARLA achieves significantly lower mean deviations, even under limited runtimes. It is robust to real-world data inconsistencies, such as infeasible distances, and can flexibly adapt to various priorities, such as emphasizing location attractiveness or distance accuracy. CARLA's versatility and efficiency make it a valuable tool for improving the spatial accuracy of activity-based travel models and agent-based transport simulations. Our implementation is available at https://github.com/tnoud/carla.

[Arxiv](https://arxiv.org/abs/2509.18191)