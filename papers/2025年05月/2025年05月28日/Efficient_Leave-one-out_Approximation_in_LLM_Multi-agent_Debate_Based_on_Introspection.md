# 基于内省的 LLM 多智能体辩论中的高效留一近似方法研究。

发布时间：2025年05月28日

`Agent` `人工智能`

> Efficient Leave-one-out Approximation in LLM Multi-agent Debate Based on Introspection

# 摘要

> 基于大型语言模型（LLMs）的多智能体系统正在推动多个领域自动任务完成的进步，其中辩论是智能体解决复杂问题的一种常见合作形式，通过推理和相互审查来巩固答案。评估这些辩论中每个智能体的个体贡献对于系统优化和结果可靠性至关重要。传统的留一法（LOO）方法提供了一个明确的框架来评估每个智能体的作用，但在基于LLM的系统中面临挑战，主要是由于高计算成本和相关的财务影响。本文提出了一种名为IntrospecLOO的简单而有效的提示方法，用于在LLM驱动的多智能体辩论中近似实现LOO。IntrospecLOO在标准辩论后引入了一个额外的查询轮次，提示智能体在忽略指定智能体的响应时更新他们的答案。这种方法有效地隔离并衡量了每个参与者的影响力，与原始的LOO方法相比，降低了查询复杂度。通过在三个基准数据集上的实验验证，证实了IntrospecLOO的有效性。

> Multi-agent systems based on large language models (LLMs) advance automatic task completion in various fields, where debate is a common cooperation form for agents to solve complicated problems with reasoning and cross-review to solidify answers. Assessing the individual contributions of agents within these debates is crucial for system refinement and outcome reliability. Traditional leave-one-out (LOO) method offers a clear framework for evaluating each agent's role but face challenges in LLM-based systems due to high computational costs and associated financial implications. This paper presents introspective-leave-one-out (IntrospecLOO), a simple yet effective prompting for approximation of LOO in LLM-powered multi-agent debates. IntrospecLOO introduces an additional querying round after standard debates, prompting agents to update their answers while ignoring responses from a designated agent. This strategy effectively isolates and gauges each participant's influence at a reduced query complexity compared to the original LOO approaches. Validation through experiments on three benchmark datasets confirms the effectiveness of IntrospecLOO.

[Arxiv](https://arxiv.org/abs/2505.22192)