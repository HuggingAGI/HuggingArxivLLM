# 增强成本蒙特卡洛树搜索助力LLM辅助规划

发布时间：2025年05月20日

`LLM应用` `人工智能` `规划算法`

> Cost-Augmented Monte Carlo Tree Search for LLM-Assisted Planning

# 摘要

> 尽管LLMs在开放性推理方面表现出色，但在成本敏感规划方面常常表现不佳，要么将所有动作视为等价成本，要么无法在严格预算内运作。本文中，我们引入了成本增强型蒙特卡洛树搜索（CATS），一种将显式成本意识引入LLM引导规划的全新方法。严格的成本限制促使规划器迅速识别不可行的解决方案，而较为宽松的限制则鼓励优化以实现最低成本。我们对GPT-4.1、Claude-3.7-Sonnet 和 DeepSeek-R1 等顶级LLMs与我们的CATS规划器进行了对比测试，评估它们在成本敏感场景下的表现。实验结果表明，像GPT-4.1这样的原生LLMs在严格预算下常常表现欠佳，而CATS则始终表现出色，实现了更高的任务成功率和更好的成本效率。通过将LLMs的推理能力与结构化搜索相结合，CATS为预算意识决策提供了一种有效的解决方案。

> While LLMs excel at open-ended reasoning, they often struggle with cost-sensitive planning, either treating all actions as having equal cost or failing to stay within strict budgets. In this paper, we introduce Cost-Augmented Monte Carlo Tree Search (CATS), a novel approach that brings explicit cost-awareness into LLM-guided planning. Tight cost constraints push the planner to quickly identify infeasible solutions, while looser constraints encourage optimization for minimal cost. We benchmark top LLMs such as GPT-4.1, Claude-3.7-Sonnet, and DeepSeek-R1, against our CATS planner to evaluate their performance in cost-sensitive scenarios. Our experiments suggest that raw LLMs such as GPT-4.1 often falter under tight budgets, whereas CATS consistently delivers strong performance, achieving higher task success rates and better cost efficiency. CATS provides an effective solution for budget-aware decision-making by combining the reasoning power of LLMs with structured search.

[Arxiv](https://arxiv.org/abs/2505.14656)