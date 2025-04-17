# # GraphicBench：语言代理辅助下的图形设计规划基准测试
GraphicBench 是一个专为语言代理设计的图形设计规划基准测试，旨在全面评估和优化语言代理在图形设计任务中的规划能力。

发布时间：2025年04月15日

`LLM应用` `创意设计` `人工智能`

> GraphicBench: A Planning Benchmark for Graphic Design with Language Agents

# 摘要

> 大型语言模型（LLM）驱动的代理为自动化人类任务开辟了新可能。尽管先前研究聚焦于目标明确的任务，但代理在开放性目标创意设计任务中的潜力仍待挖掘。我们推出GraphicBench，一个涵盖四种设计类型的图形设计规划基准，包含1,079个用户查询和输入图像。我们还发布了GraphicTown，这是一个LLM代理框架，内置三位设计专家和46种可选动作（工具），用于在网页环境中执行规划工作流的每一步骤。实验结果表明，六种LLM均能生成整合用户查询中的显式设计约束和隐式常识约束的工作流。然而，这些工作流常因以下原因未能成功执行：1. 空间关系推理，2. 全局依赖关系的协调，3. 每一步骤中最合适动作的检索。我们期待GraphicBench成为推动LLM代理在创意设计任务中规划与执行能力的具挑战性 yet 有价值的测试平台。

> Large Language Model (LLM)-powered agents have unlocked new possibilities for automating human tasks. While prior work has focused on well-defined tasks with specified goals, the capabilities of agents in creative design tasks with open-ended goals remain underexplored. We introduce GraphicBench, a new planning benchmark for graphic design that covers 1,079 user queries and input images across four design types. We further present GraphicTown, an LLM agent framework with three design experts and 46 actions (tools) to choose from for executing each step of the planned workflows in web environments. Experiments with six LLMs demonstrate their ability to generate workflows that integrate both explicit design constraints from user queries and implicit commonsense constraints. However, these workflows often do not lead to successful execution outcomes, primarily due to challenges in: (1) reasoning about spatial relationships, (2) coordinating global dependencies across experts, and (3) retrieving the most appropriate action per step. We envision GraphicBench as a challenging yet valuable testbed for advancing LLM-agent planning and execution in creative design tasks.

[Arxiv](https://arxiv.org/abs/2504.11571)