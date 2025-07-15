# # 环形结构上的鲁棒信号分解

发布时间：2025年07月09日

`Agent` `机器人技术` `自动化控制`

> Robust signal decompositions on the circle

# 摘要

> 我们探讨将定义在圆上的分段常数函数分解为平面上若干个闭合圆形区域指示函数之和的问题，其中区域的数量和位置事先未知。这一问题对应于一个在圆上移动的智能体感知其与地标接近程度的情景，目标是估计地标数量及其位置，从而实现运动规划与避障等控制任务。值得注意的是，函数在不连续点处的精确值（对应于各指示函数的区域边界）并不为智能体所知。我们引入鲁棒性和自由度概念，以筛选出在非精确数据下更优或更可能的分解方案。我们对鲁棒分解进行了表征，并提供了一种生成所有此类分解的程序。当函数允许鲁棒分解时，我们计算可能的鲁棒分解数量，并推导出最大化自由度的分解数量的界限。

> We consider the problem of decomposing a piecewise constant function on the circle into a sum of indicator functions of closed circular disks in the plane, whose number and location are not a priori known. This represents a situation where an agent moving on the circle is able to sense its proximity to some landmarks, and the goal is to estimate the number of these landmarks and their possible locations -- which can in turn enable control tasks such as motion planning and obstacle avoidance. Moreover, the exact values of the function at its discontinuities (which correspond to disk boundaries for the individual indicator functions) are not assumed to be known to the agent. We introduce suitable notions of robustness and degrees of freedom to single out those decompositions that are more desirable, or more likely, given this non-precise data collected by the agent. We provide a characterization of robust decompositions and give a procedure for generating all such decompositions. When the given function admits a robust decomposition, we compute the number of possible robust decompositions and derive bounds for the number of decompositions maximizing the degrees of freedom.

[Arxiv](https://arxiv.org/abs/2507.07007)