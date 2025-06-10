# 基于语言的分层规划与多机器人三维场景图执行

发布时间：2025年06月09日

`LLM应用` `机器人` `自主导航`

> Language-Grounded Hierarchical Planning and Execution with Multi-Robot 3D Scene Graphs

# 摘要

> 本文提出了一种集成地图、定位和任务运动规划（TAMP）的多机器人系统，该系统借助3D场景图来执行自然语言表达的复杂指令。系统构建了一个包含开放集对象地图的共享3D场景图，用于多机器人场景图融合。这种表示支持实时、视图不变的重新定位和规划，使机器人团队能够推理环境并执行复杂任务。此外，我们提出了一种基于大型语言模型（LLM）的规划方法，通过共享的3D场景图和机器人能力，将操作意图转化为规划领域定义语言（PDDL）目标。我们在大规模户外环境中对系统性能进行了实验评估。

> In this paper, we introduce a multi-robot system that integrates mapping, localization, and task and motion planning (TAMP) enabled by 3D scene graphs to execute complex instructions expressed in natural language. Our system builds a shared 3D scene graph incorporating an open-set object-based map, which is leveraged for multi-robot 3D scene graph fusion. This representation supports real-time, view-invariant relocalization (via the object-based map) and planning (via the 3D scene graph), allowing a team of robots to reason about their surroundings and execute complex tasks. Additionally, we introduce a planning approach that translates operator intent into Planning Domain Definition Language (PDDL) goals using a Large Language Model (LLM) by leveraging context from the shared 3D scene graph and robot capabilities. We provide an experimental assessment of the performance of our system on real-world tasks in large-scale, outdoor environments.

[Arxiv](https://arxiv.org/abs/2506.07454)