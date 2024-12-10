# 利用语言模型进行查询高效规划

发布时间：2024年12月08日

`LLM应用` `智能体`

> Query-Efficient Planning with Language Models

# 摘要

> 在复杂环境中规划，要求智能体能高效查询世界模型，从而找出从起始到目标的可行动作序列。近期研究显示，拥有丰富先验知识和推理能力的大型语言模型（LLMs），有可能通过搜索有前景的状态并适应世界反馈来助力规划。本文中，我们提出并探讨了两个本质上相互竞争的框架，它们借助 LLMs 实现高效查询规划。其一在基于搜索的规划器里将 LLMs 当作启发式手段，选择有潜力的节点进行扩展并给出有希望的动作。其二把 LLMs 用作生成式规划器，提出从起始到目标的完整动作序列，查询世界模型，并依据反馈做出调整。我们发现，虽然这两种方式都优于可比较的基线，但使用 LLMs 作为生成式规划器会大幅减少交互。我们的关键发现是，作为规划器的 LLMs 相比作为启发式的 LLMs，能更迅速地依据即时反馈调整规划策略。我们在 Robotouille 和 PDDL 规划基准上开展了评估和消融实验，并讨论了与现有关于高效查询规划算法理论的联系。代码可在 https://github.com/portal-cornell/llms-for-planning 获取。

> Planning in complex environments requires an agent to efficiently query a world model to find a feasible sequence of actions from start to goal. Recent work has shown that Large Language Models (LLMs), with their rich prior knowledge and reasoning capabilities, can potentially help with planning by searching over promising states and adapting to feedback from the world. In this paper, we propose and study two fundamentally competing frameworks that leverage LLMs for query-efficient planning. The first uses LLMs as a heuristic within a search-based planner to select promising nodes to expand and propose promising actions. The second uses LLMs as a generative planner to propose an entire sequence of actions from start to goal, query a world model, and adapt based on feedback. We show that while both approaches improve upon comparable baselines, using an LLM as a generative planner results in significantly fewer interactions. Our key finding is that the LLM as a planner can more rapidly adapt its planning strategies based on immediate feedback than LLM as a heuristic. We present evaluations and ablations on Robotouille and PDDL planning benchmarks and discuss connections to existing theory on query-efficient planning algorithms. Code is available at https://github.com/portal-cornell/llms-for-planning

[Arxiv](https://arxiv.org/abs/2412.06162)