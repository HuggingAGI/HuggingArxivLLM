# 双层优化驱动的平均场博弈中轨迹与障碍物的联合推断

发布时间：2025年07月25日

`Agent

这篇论文主要探讨均场博弈（MFG）框架及其逆问题，涉及智能体轨迹的恢复和障碍建模，属于智能体行为建模和优化的研究领域。` `自动驾驶`

> Joint Inference of Trajectory and Obstacle in Mean-Field Games via Bilevel Optimization

# 摘要

> 均场博弈（MFG）是一种强大的建模框架，适用于具有连续相互作用主体的系统。尽管在解决正向MFG方面已有诸多方法，但对其逆问题的研究却十分有限。本研究致力于根据部分观测数据，恢复最优主体轨迹和未见的空间障碍。为此，我们采用归一化流这一特殊生成模型来表示轨迹，并创新性地将逆MFG问题建模为双层优化（BLO）问题。我们通过多种MFG场景验证了方法的有效性，包括多模态和不相连障碍的情况，充分展现了其在障碍复杂度和维度方面的鲁棒性。此外，我们的方法也可视为通过MFG假设对最大似然轨迹学习进行正则化，尤其在训练数据稀缺时，显著提升了模型的泛化性能。值得一提的是，即使在数据量极低的情况下，我们的方法仍能高保真地恢复隐藏障碍。

> Mean field game (MFG) is an expressive modeling framework for systems with a continuum of interacting agents. While many approaches exist for solving the forward MFG, few have studied its \textit{inverse} problem. In this work, we seek to recover optimal agent trajectories and the unseen spatial obstacle given partial observation on the former. To this end, we use a special type of generative models, normalizing flow, to represent the trajectories and propose a novel formulation of inverse MFG as a bilevel optimization (BLO) problem. We demonstrate the effectiveness of our approach across various MFG scenarios, including those involving multi-modal and disjoint obstacles, highlighting its robustness with respect to obstacle complexity and dimensionality. Alternatively, our formulation can be interpreted as regularizing maximum likelihood trajectory learning with MFG assumptions, which improves generalization performance especially with scarce training data. Impressively, our method also recovers the hidden obstacle with high fidelity in this low-data regime.

[Arxiv](https://arxiv.org/abs/2507.19344)