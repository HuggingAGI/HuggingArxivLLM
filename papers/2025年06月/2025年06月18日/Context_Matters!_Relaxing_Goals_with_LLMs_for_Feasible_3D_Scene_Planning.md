# 上下文很重要！借助LLMs放宽目标，实现可行的3D场景规划。

发布时间：2025年06月18日

`LLM应用` `机器人`

> Context Matters! Relaxing Goals with LLMs for Feasible 3D Scene Planning

# 摘要

> 经典规划在AI和机器人领域通过从命令式方法转向声明式方法（如PDDL）来处理复杂任务。然而，这些方法在实际场景中常常失效，主要因为机器人感知能力有限，且需要将感知结果与规划谓词相结合。这通常会导致行为严重依赖硬编码，难以适应变化，即便在可以通过放宽规划实现目标的场景中也是如此。与此同时，大型语言模型（LLMs）推动了利用常识推理的规划系统的发展，但这些系统往往生成不可行和/或不安全的计划。为了解决这些问题，我们提出了一种结合经典规划与LLMs的方法，利用其提取常识知识和将动作与环境关联的能力。我们提出了一种层次化框架，通过逐步放宽目标定义，使机器人能够将不可行的任务转化为可处理的形式。这种机制支持在特定上下文中部分实现预期目标。通过基于3D场景图建模的环境进行的全面定性和定量评估，我们的方法展示了其在适应和有效执行任务方面的强大能力。我们还展示了该方法在复杂场景中的成功应用，而其他基准方法在这些场景中更容易失败。代码、数据集和额外材料已向社区开放。

> Classical planning in AI and Robotics addresses complex tasks by shifting from imperative to declarative approaches (e.g., PDDL). However, these methods often fail in real scenarios due to limited robot perception and the need to ground perceptions to planning predicates. This often results in heavily hard-coded behaviors that struggle to adapt, even with scenarios where goals can be achieved through relaxed planning. Meanwhile, Large Language Models (LLMs) lead to planning systems that leverage commonsense reasoning but often at the cost of generating unfeasible and/or unsafe plans. To address these limitations, we present an approach integrating classical planning with LLMs, leveraging their ability to extract commonsense knowledge and ground actions. We propose a hierarchical formulation that enables robots to make unfeasible tasks tractable by defining functionally equivalent goals through gradual relaxation. This mechanism supports partial achievement of the intended objective, suited to the agent's specific context. Our method demonstrates its ability to adapt and execute tasks effectively within environments modeled using 3D Scene Graphs through comprehensive qualitative and quantitative evaluations. We also show how this method succeeds in complex scenarios where other benchmark methods are more likely to fail. Code, dataset, and additional material are released to the community.

[Arxiv](https://arxiv.org/abs/2506.15828)