# 从 LLM 群到 PDDL 赋能的 HIVE：于多模态丛林中规划自我执行的指令

发布时间：2024年12月17日

`Agent` `代理系统`

> From An LLM Swarm To A PDDL-Empowered HIVE: Planning Self-Executed Instructions In A Multi-Modal Jungle

# 摘要

> 为响应利用深度模型生态系统日益强大能力的基于代理的解决方案的需求，我们推出了 Hive——这是一个能选择合适模型并规划一系列原子动作以满足终端用户指令的综合性解决方案。Hive 基于模型集合运作，收到自然语言指令（即用户查询）后，会安排并执行可解释的原子动作规划。这些动作可能会用到一个或多个可用模型来完成整体任务，同时遵循终端用户的特定约束。值得一提的是，Hive 能够处理涉及多模态输入和输出的任务，从而能够应对复杂的现实世界查询。我们的系统能够规划复杂的动作链，同时确保可解释性，借助基于 LLM 且由 PDDL 操作支持的形式逻辑框架。为全面评估代理系统的多模态能力，我们引入了 MuSE 基准。我们的发现表明，我们的框架重新定义了任务选择的前沿水平，在规划跨多个模型的操作方面优于其他竞争系统，同时提供透明度保证，且完全符合用户约束。

> In response to the call for agent-based solutions that leverage the ever-increasing capabilities of the deep models' ecosystem, we introduce Hive -- a comprehensive solution for selecting appropriate models and subsequently planning a set of atomic actions to satisfy the end-users' instructions. Hive operates over sets of models and, upon receiving natural language instructions (i.e. user queries), schedules and executes explainable plans of atomic actions. These actions can involve one or more of the available models to achieve the overall task, while respecting end-users specific constraints. Notably, Hive handles tasks that involve multi-modal inputs and outputs, enabling it to handle complex, real-world queries. Our system is capable of planning complex chains of actions while guaranteeing explainability, using an LLM-based formal logic backbone empowered by PDDL operations. We introduce the MuSE benchmark in order to offer a comprehensive evaluation of the multi-modal capabilities of agent systems. Our findings show that our framework redefines the state-of-the-art for task selection, outperforming other competing systems that plan operations across multiple models while offering transparency guarantees while fully adhering to user constraints.

[Arxiv](https://arxiv.org/abs/2412.12839)