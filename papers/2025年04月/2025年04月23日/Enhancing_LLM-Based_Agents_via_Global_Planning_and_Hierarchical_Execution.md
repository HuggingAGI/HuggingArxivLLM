# 增强基于 LLM 的代理：全局规划与分层执行

发布时间：2025年04月23日

`Agent` `智能体系统`

> Enhancing LLM-Based Agents via Global Planning and Hierarchical Execution

# 摘要

> 基于大型语言模型（LLMs）的智能体系统在现实应用中展现了巨大潜力，但现有框架在任务规划和执行上仍有关键限制，影响了其效果和通用性。具体而言，现有规划方法常因缺乏明确全局目标而导致智能体陷入局部分支或生成不可执行计划。同时，执行机制在复杂性与稳定性间难以平衡，有限的动作空间也限制了其处理多样化任务的能力。

为解决这些问题，我们提出了 GoalAct，一个集成持续更新全局规划机制与分层执行策略的新型智能体框架。GoalAct 将任务执行分解为搜索、编码、写作等高级技能，降低了规划复杂性，同时提升了智能体在多样化任务场景中的适应能力。我们在 LegalAgentBench 基准测试上评估了 GoalAct，该基准包含多种需使用多种工具的法律任务。实验结果表明，GoalAct 达到了最先进的（SOTA）性能，成功率平均提升了 12.22%。

这些发现凸显了 GoalAct 在推动更先进智能体系统发展方面的潜力，使其在复杂现实应用中更加有效。我们的代码可在 https://github.com/cjj826/GoalAct 获取。

> Intelligent agent systems based on Large Language Models (LLMs) have shown great potential in real-world applications. However, existing agent frameworks still face critical limitations in task planning and execution, restricting their effectiveness and generalizability. Specifically, current planning methods often lack clear global goals, leading agents to get stuck in local branches, or produce non-executable plans. Meanwhile, existing execution mechanisms struggle to balance complexity and stability, and their limited action space restricts their ability to handle diverse real-world tasks. To address these limitations, we propose GoalAct, a novel agent framework that introduces a continuously updated global planning mechanism and integrates a hierarchical execution strategy. GoalAct decomposes task execution into high-level skills, including searching, coding, writing and more, thereby reducing planning complexity while enhancing the agents' adaptability across diverse task scenarios. We evaluate GoalAct on LegalAgentBench, a benchmark with multiple types of legal tasks that require the use of multiple types of tools. Experimental results demonstrate that GoalAct achieves state-of-the-art (SOTA) performance, with an average improvement of 12.22% in success rate. These findings highlight GoalAct's potential to drive the development of more advanced intelligent agent systems, making them more effective across complex real-world applications. Our code can be found at https://github.com/cjj826/GoalAct.

[Arxiv](https://arxiv.org/abs/2504.16563)