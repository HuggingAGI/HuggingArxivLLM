# 与模型齐头并进：大规模LLMs的在线部署与路由

发布时间：2025年06月08日

`其他` `系统优化` `资源管理`

> Keeping Up with the Models: Online Deployment and Routing of LLMs at Scale

# 摘要

> 新型大型语言模型 (LLMs) 的快速迭代与旧模型的迅速淘汰，促使 LLM 服务提供商在严格的部署容量和每查询成本预算下，不断调整和管理流动的模型库存。我们将这一现实建模为一个在线决策问题，其中分阶段部署（在固定维护窗口期间进行）与在保持活跃的模型之间进行每查询路由相结合。我们提出了一种分层算法 StageRoute，它通过以下两步实现优化：首先，使用奖励上置信界和成本下置信界乐观地为下一阶段选择最多 $M_max$ 个模型；其次，解决一个预算约束的多臂老虎机子问题以路由每个传入查询。理论分析表明，StageRoute 实现了 $T^{2/3}$ 级别的遗憾，并提供了匹配的下界，证明了其近最优性。实验结果进一步验证了这一理论，在实际应用中 StageRoute 表现接近最优。

> The rapid pace at which new large language models (LLMs) appear -- and older ones become obsolete -- forces LLM service providers to juggle a streaming inventory of models while respecting tight deployment capacity and per-query cost budgets. We cast the reality as an online decision problem that couples stage-wise deployment, made at fixed maintenance windows, with per-query routing among the models kept live. We introduce StageRoute, a hierarchical algorithm that (i) optimistically selects up to $M_max$ models for the next stage using reward upper-confidence and cost lower-confidence bounds, then (ii) solves a budget-constrained bandit sub-problem to route each incoming query. We prove that StageRoute achieves a regret of order $T^{2/3}$ and provide a matching lower bound, thereby establishing its near-optimality. Moreover, our experiments confirm the theory, demonstrating that StageRoute performs close to the optimum in practical settings.

[Arxiv](https://arxiv.org/abs/2506.17254)