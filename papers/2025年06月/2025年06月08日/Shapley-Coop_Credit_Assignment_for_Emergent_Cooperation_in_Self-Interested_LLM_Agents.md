# # Shapley-Coop：在自我利益驱动的LLM智能体中实现自发合作的贡献分配方法

发布时间：2025年06月08日

`Agent` `人工智能` `多智能体系统`

> Shapley-Coop: Credit Assignment for Emergent Cooperation in Self-Interested LLM Agents

# 摘要

> 大型语言模型（LLMs）在多智能体系统中展现出强大的协作能力，尤其在具有预定义角色和工作流程的场景下表现突出。然而，在开放环境中，由于缺乏协调规则，智能体往往倾向于采取自我利益导向的行为。实现有效协调的核心挑战在于信用分配——如何公平评估每个智能体的贡献，并设计能够使其异质目标相协调的定价机制。这一问题在LLMs越来越多地参与复杂人机协作的背景下显得尤为重要，因为公平的补偿和问责制依赖于有效的定价机制。受人类社会解决类似协调挑战的方式启发（例如通过临时协作，如就业或分包），我们提出了一种名为Shapley-Coop的合作工作流。Shapley-Coop整合了Shapley链式思维——利用边际贡献作为定价的理论基础——并结合了结构化的谈判协议，以实现有效的价格匹配，使LLM智能体能够通过理性的时间任务定价和任务后奖励重新分配来进行协调。这种方法不仅统一了智能体的激励，促进了合作，还保持了其自主性。我们通过两个多智能体游戏和一个软件工程模拟对Shapley-Coop进行了全面评估，结果表明它能够显著提升LLM智能体的协作能力，并实现公平的信用分配。这些结果充分展示了Shapley-Coop定价机制的有效性，其能够在任务执行过程中准确反映个体贡献。

> Large Language Models (LLMs) show strong collaborative performance in multi-agent systems with predefined roles and workflows. However, in open-ended environments lacking coordination rules, agents tend to act in self-interested ways. The central challenge in achieving coordination lies in credit assignment -- fairly evaluating each agent's contribution and designing pricing mechanisms that align their heterogeneous goals. This problem is critical as LLMs increasingly participate in complex human-AI collaborations, where fair compensation and accountability rely on effective pricing mechanisms. Inspired by how human societies address similar coordination challenges (e.g., through temporary collaborations such as employment or subcontracting), we propose a cooperative workflow, Shapley-Coop. Shapley-Coop integrates Shapley Chain-of-Thought -- leveraging marginal contributions as a principled basis for pricing -- with structured negotiation protocols for effective price matching, enabling LLM agents to coordinate through rational task-time pricing and post-task reward redistribution. This approach aligns agent incentives, fosters cooperation, and maintains autonomy. We evaluate Shapley-Coop across two multi-agent games and a software engineering simulation, demonstrating that it consistently enhances LLM agent collaboration and facilitates equitable credit assignment. These results highlight the effectiveness of Shapley-Coop's pricing mechanisms in accurately reflecting individual contributions during task execution.

[Arxiv](https://arxiv.org/abs/2506.07388)