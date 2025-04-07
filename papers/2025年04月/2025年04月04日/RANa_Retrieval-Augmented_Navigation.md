# RANa: 检索增强型导航

发布时间：2025年04月04日

`Agent` `机器人技术` `人工智能`

> RANa: Retrieval-Augmented Navigation

# 摘要

> 传统的基于大规模学习的导航方法通常将每个任务视为独立的问题，智能体在未知环境中以清空记忆的状态开始。虽然这种在未知环境中的一般化能力非常重要，但在现实场景中，智能体应该能够利用之前机器人操作中收集的信息。为此，我们引入了一种新的检索增强型智能体，通过强化学习训练，能够查询同一环境中之前任务收集的数据库，并学习如何整合这些额外的上下文信息。我们为通用导航任务设计了一种独特的智能体架构，并在ObjectNav、ImageNav和Instance-ImageNav上进行了评估。我们的检索和上下文编码方法是数据驱动的，并且充分利用视觉基础模型（FM）来进行语义和几何理解。我们为这些设置提出了新的基准测试，并展示了检索不仅能够实现跨任务和环境的零样本迁移，还显著提高了性能。

> Methods for navigation based on large-scale learning typically treat each episode as a new problem, where the agent is spawned with a clean memory in an unknown environment. While these generalization capabilities to an unknown environment are extremely important, we claim that, in a realistic setting, an agent should have the capacity of exploiting information collected during earlier robot operations. We address this by introducing a new retrieval-augmented agent, trained with RL, capable of querying a database collected from previous episodes in the same environment and learning how to integrate this additional context information. We introduce a unique agent architecture for the general navigation task, evaluated on ObjectNav, ImageNav and Instance-ImageNav. Our retrieval and context encoding methods are data-driven and heavily employ vision foundation models (FM) for both semantic and geometric understanding. We propose new benchmarks for these settings and we show that retrieval allows zero-shot transfer across tasks and environments while significantly improving performance.

[Arxiv](https://arxiv.org/abs/2504.03524)