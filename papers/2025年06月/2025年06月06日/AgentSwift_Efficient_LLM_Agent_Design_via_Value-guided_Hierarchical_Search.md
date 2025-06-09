# AgentSwift：采用基于价值的分层搜索实现高效LLM代理设计

发布时间：2025年06月06日

`Agent` `代理系统`

> AgentSwift: Efficient LLM Agent Design via Value-guided Hierarchical Search

# 摘要

> 大型语言模型（LLM）代理在多领域展现强大能力，但设计高性能代理系统仍具挑战。现有代理搜索方法存在三大局限：(1) 过度优化工作流程而忽视人类设计组件；(2) 高昂的评估成本；(3) 大规模搜索效率低下。我们提出了一种全面框架，首先构建分层搜索空间，整合代理工作流程与可组合组件，支持更丰富设计。其次，引入预测价值模型，实现低成本高效评估。最后，采用基于不确定性的分层蒙特卡洛树搜索策略。实验显示，我们的方法在七个基准测试中平均性能提升8.34%，搜索速度更快。代码仓库地址：https://github.com/Ericccc02/AgentSwift。

> Large language model (LLM) agents have demonstrated strong capabilities across diverse domains. However, designing high-performing agentic systems remains challenging. Existing agent search methods suffer from three major limitations: (1) an emphasis on optimizing agentic workflows while under-utilizing proven human-designed components such as memory, planning, and tool use; (2) high evaluation costs, as each newly generated agent must be fully evaluated on benchmarks; and (3) inefficient search in large search space. In this work, we introduce a comprehensive framework to address these challenges. First, We propose a hierarchical search space that jointly models agentic workflow and composable functional components, enabling richer agentic system designs. Building on this structured design space, we introduce a predictive value model that estimates agent performance given agentic system and task description, allowing for efficient, low-cost evaluation during the search process. Finally, we present a hierarchical Monte Carlo Tree Search (MCTS) strategy informed by uncertainty to guide the search. Experiments on seven benchmarks, covering embodied, math, web, tool, and game, show that our method achieves an average performance gain of 8.34\% over state-of-the-art baselines and exhibits faster search progress with steeper improvement trajectories. Code repo is available at https://github.com/Ericccc02/AgentSwift.

[Arxiv](https://arxiv.org/abs/2506.06017)