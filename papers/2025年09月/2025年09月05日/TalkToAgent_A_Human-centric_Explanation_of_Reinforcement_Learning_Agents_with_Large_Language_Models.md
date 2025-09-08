# TalkToAgent：基于大型语言模型的强化学习智能体的人本解释

发布时间：2025年09月05日

`Agent` `工业与制造`

> TalkToAgent: A Human-centric Explanation of Reinforcement Learning Agents with Large Language Models

# 摘要

> 可解释强化学习（XRL）作为提升强化学习（RL）智能体透明度的有效途径，展现出巨大潜力。但目前XRL结果的可理解性较差，且现有XRL方法覆盖零散，导致复杂RL策略与领域专家之间存在隔阂，用户常对工具选择感到困惑。为此，我们提出TalkToAgent——一个多智能体大型语言模型（LLM）框架，能为RL策略提供交互式自然语言解释。该框架配备五个专用LLM智能体（协调器、解释器、编码器、评估器、调试器），可自动将用户查询匹配到相关XRL工具，并从关键状态变量、预期结果或反事实解释等维度清晰阐释智能体行为。此外，我们的方法通过从定性行为描述中生成替代场景，甚至新的规则式策略，拓展了以往的反事实解释能力。我们在四容水箱过程控制问题（一个经典的非线性控制基准任务）上对TalkToAgent进行了验证。结果显示，TalkToAgent能将用户查询高精度匹配到XRL任务，且编码器-调试器的协同交互大幅降低了反事实生成的失败率。定性评估进一步证实，TalkToAgent能有效解读智能体行为，并结合问题领域背景阐释其意义。

> Explainable Reinforcement Learning (XRL) has emerged as a promising approach in improving the transparency of Reinforcement Learning (RL) agents. However, there remains a gap between complex RL policies and domain experts, due to the limited comprehensibility of XRL results and isolated coverage of current XRL approaches that leave users uncertain about which tools to employ. To address these challenges, we introduce TalkToAgent, a multi-agent Large Language Models (LLM) framework that delivers interactive, natural language explanations for RL policies. The architecture with five specialized LLM agents (Coordinator, Explainer, Coder, Evaluator, and Debugger) enables TalkToAgent to automatically map user queries to relevant XRL tools and clarify an agent's actions in terms of either key state variables, expected outcomes, or counterfactual explanations. Moreover, our approach extends previous counterfactual explanations by deriving alternative scenarios from qualitative behavioral descriptions, or even new rule-based policies. We validated TalkToAgent on quadruple-tank process control problem, a well-known nonlinear control benchmark. Results demonstrated that TalkToAgent successfully mapped user queries into XRL tasks with high accuracy, and coder-debugger interactions minimized failures in counterfactual generation. Furthermore, qualitative evaluation confirmed that TalkToAgent effectively interpreted agent's actions and contextualized their meaning within the problem domain.

[Arxiv](https://arxiv.org/abs/2509.04809)