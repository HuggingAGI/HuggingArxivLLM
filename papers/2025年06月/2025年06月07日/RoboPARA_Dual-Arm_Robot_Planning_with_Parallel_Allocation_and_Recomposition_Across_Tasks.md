# # 机器人PARA：结合并行分配与跨任务重组的双臂机器人规划

发布时间：2025年06月07日

`LLM应用` `机器人`

> RoboPARA: Dual-Arm Robot Planning with Parallel Allocation and Recomposition Across Tasks

# 摘要

> 双臂机器人在复杂多任务场景中对提升效率和灵活性至关重要。尽管现有方法在任务规划中取得了显著成果，但它们往往未能充分发挥任务并行性，限制了双臂协作的潜力。为解决这一问题，我们提出了RoboPARA——一个基于大型语言模型（LLM）的双臂任务并行规划新框架。RoboPARA采用两阶段流程：首先通过构建有向无环图（DAG）进行基于依赖图的规划候选生成，以建模任务依赖关系并消除冗余；其次通过基于图重遍历的双臂并行规划，优化DAG遍历以最大化并行性同时保持任务连贯性。此外，我们推出了首个专门用于评估双臂任务并行性的跨场景数据集X-DAPT，覆盖多种场景和难度级别。在X-DAPT数据集上的实验表明，RoboPARA显著优于现有方法，尤其在复杂任务组合中展现了更高的效率和可靠性。代码和数据集将在接受后公开。

> Dual-arm robots play a crucial role in improving efficiency and flexibility in complex multitasking scenarios. While existing methods have achieved promising results in task planning, they often fail to fully optimize task parallelism, limiting the potential of dual-arm collaboration. To address this issue, we propose RoboPARA, a novel large language model (LLM)-driven framework for dual-arm task parallelism planning. RoboPARA employs a two-stage process: (1) Dependency Graph-based Planning Candidates Generation, which constructs directed acyclic graphs (DAGs) to model task dependencies and eliminate redundancy, and (2) Graph Re-Traversal-based Dual-Arm Parallel Planning, which optimizes DAG traversal to maximize parallelism while maintaining task coherence. In addition, we introduce the Cross-Scenario Dual-Arm Parallel Task dataset (X-DAPT dataset), the first dataset specifically designed to evaluate dual-arm task parallelism across diverse scenarios and difficulty levels. Extensive experiments on the X-DAPT dataset demonstrate that RoboPARA significantly outperforms existing methods, achieving higher efficiency and reliability, particularly in complex task combinations. The code and dataset will be released upon acceptance.

[Arxiv](https://arxiv.org/abs/2506.06683)