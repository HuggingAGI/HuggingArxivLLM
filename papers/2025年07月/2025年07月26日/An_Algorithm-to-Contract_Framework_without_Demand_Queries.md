# # 无需需求查询的算法到合同框架

发布时间：2025年07月26日

`Agent` `机制设计` `博弈论`

> An Algorithm-to-Contract Framework without Demand Queries

# 摘要

> 考虑那些对项目成功至关重要的高成本任务，代理必须在规定时间内完成这些任务。这正是经典的预算最大化问题，该问题允许近似方案（FPTAS）。假设代理代表委托人执行这些任务，若项目成功，委托人将获得奖励。那么，委托人如何设计一份合同来激励代理？在本研究中，我们致力于实现从算法到合同的转换，即将组合优化问题（如预算最大化）的算法转化为解决合同设计中的激励约束问题。与之前的工作不同，我们避免假设对需求预言机的黑箱访问。

我们通过“局部-全局”框架展示了如何将预算最大化的FPTAS“提升”为合同设计问题的最佳可能的乘法和加法FPTAS。在“局部”步骤中，我们（近似）求解一个强化的双方面需求问题的变体；在“全局”步骤中，我们利用局部步骤的结果来找到近似最优的合同。我们将这一框架成功应用于多种组合约束，包括多维预算、预算化拟阵和预算化匹配约束。在所有情况下，我们的近似效果都与纯算法问题的最佳近似效果基本一致。此外，我们还开发了一种方法来处理多代理合同设置，其中一组协作的代理必须遵守组合可行性约束。


> Consider costly tasks that add up to the success of a project, and must be fitted by an agent into a given time-frame. This is an instance of the classic budgeted maximization problem, which admits an approximation scheme (FPTAS). Now assume the agent is performing these tasks on behalf of a principal, who is the one to reap the rewards if the project succeeds. The principal must design a contract to incentivize the agent. Is there still an approximation scheme? In this work, our ultimate goal is an algorithm-to-contract transformation, which transforms algorithms for combinatorial problems (like budgeted maximization) to tackle incentive constraints that arise in contract design. Our approach diverges from previous works on combinatorial contract design by avoiding an assumption of black-box access to a demand oracle.
  We first show how to "lift" the FPTAS for budgeted maximization to obtain the best-possible multiplicative and additive FPTAS for the contract design problem. We establish this through our "local-global" framework, in which the "local" step is to (approximately) solve a two-sided strengthened variant of the demand problem. The "global" step then utilizes the local one to find the approximately optimal contract. We apply our framework to a host of combinatorial constraints including multi-dimensional budgets, budgeted matroid, and budgeted matching constraints. In all cases we achieve an approximation essentially matching the best approximation for the purely algorithmic problem. We also develop a method to tackle multi-agent contract settings, where the team of working agents must abide to combinatorial feasibility constraints.

[Arxiv](https://arxiv.org/abs/2507.20038)