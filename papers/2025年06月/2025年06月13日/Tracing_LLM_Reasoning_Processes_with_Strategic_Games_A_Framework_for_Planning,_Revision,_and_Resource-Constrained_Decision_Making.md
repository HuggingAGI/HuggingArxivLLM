# 用战略游戏解析 LLM 推理：规划、修订与资源受限决策的框架方法

发布时间：2025年06月13日

`LLM理论` `人工智能`

> Tracing LLM Reasoning Processes with Strategic Games: A Framework for Planning, Revision, and Resource-Constrained Decision Making

# 摘要

> 大型语言模型（LLMs）在复杂推理任务中的应用日益广泛，但现有评估方法往往只关注最终结果，而忽视了规划、修订和资源受限决策等关键中间推理步骤。我们提出，深入分析这些内部过程对于理解模型行为和提升可靠性至关重要。为此，我们建议将战略游戏作为理想的评估环境：这些基于规则的封闭系统具有清晰的状态、有限的资源和自动反馈机制。我们构建了一个评估框架，从规划、修订和资源受限决策三个核心维度对LLMs进行全面评估。在评估指标方面，我们不仅关注胜率，还引入了过度修正风险率、修正成功率、改进斜率和超支比例等多维度指标。通过对12个领先模型的4320轮对抗测试，ChatGPT-o3-mini以74.7%的胜率、78.6%的修正成功率和0.041的改进斜率取得最高综合得分。Qwen-Plus尽管拥有81.6%的高过度修正风险率，却仅在25.6%的对战中获胜，这主要源于其资源使用过度。我们的研究还发现，过度修正风险率与修正成功率之间存在显著负相关关系（r = -0.51，p = 0.093），表明频繁的编辑并不一定能带来更好的结果。这些发现凸显了评估LLMs不仅要关注其最终决策，更要深入考察其决策过程的重要性。


> Large language models (LLMs) are increasingly used for tasks that require complex reasoning. Most benchmarks focus on final outcomes but overlook the intermediate reasoning steps - such as planning, revision, and decision making under resource constraints. We argue that measuring these internal processes is essential for understanding model behavior and improving reliability. We propose using strategic games as a natural evaluation environment: closed, rule-based systems with clear states, limited resources, and automatic feedback. We introduce a framework that evaluates LLMs along three core dimensions: planning, revision, and resource-constrained decision making. To operationalize this, we define metrics beyond win rate, including overcorrection risk rate, correction success rate, improvement slope, and over-budget ratio. In 4320 adversarial rounds across 12 leading models, ChatGPT-o3-mini achieves the top composite score, with a win rate of 74.7 percent, a correction success rate of 78.6 percent, and an improvement slope of 0.041. By contrast, Qwen-Plus, despite an overcorrection risk rate of 81.6 percent, wins only 25.6 percent of its matches - primarily due to excessive resource use. We also observe a negative correlation between overcorrection risk rate and correction success rate (Pearson r = -0.51, p = 0.093), suggesting that more frequent edits do not always improve outcomes. Our findings highlight the value of assessing not only what LLMs decide but how they arrive at those decisions

[Arxiv](https://arxiv.org/abs/2506.12012)