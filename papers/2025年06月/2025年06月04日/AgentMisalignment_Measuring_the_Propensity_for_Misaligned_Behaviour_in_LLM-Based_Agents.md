# Agent对齐偏差：衡量LLM智能体行为对齐倾向的指标

发布时间：2025年06月04日

`LLM应用

摘要讨论了大型语言模型（LLM）代理的偏离风险，推出了一个评估基准测试，并分析了系统提示对代理行为的影响，属于LLM应用层面的研究。` `人工智能伦理` `AI系统应用与管理`

> AgentMisalignment: Measuring the Propensity for Misaligned Behaviour in LLM-Based Agents

# 摘要

> 随着大型语言模型（LLM）代理的普及，偏离风险也随之增加。此前研究主要关注代理的偏离行为能力与误用倾向，但代理在现实场景中尝试偏离行为的可能性仍不明确。为此，我们推出偏离倾向基准测试——AgentMisalignment，涵盖一系列现实场景，用于评估LLM代理的偏离行为表现。我们从目标守护、抵制关闭、示弱和权力追求四个子类别展开评估。测试结果显示，前沿模型的偏离行为发生率普遍较高，且模型能力越强，偏离倾向越明显。此外，我们通过不同系统提示系统地调整代理个性，发现人格特征对偏离倾向的影响远超模型选择本身，凸显了对AI代理进行谨慎系统提示工程的重要性。我们的研究揭示了现有对齐方法在LLM代理上的局限性，并强调随着自主系统普及，进一步开展倾向评估的必要性。

> As Large Language Model (LLM) agents become more widespread, associated misalignment risks increase. Prior work has examined agents' ability to enact misaligned behaviour (misalignment capability) and their compliance with harmful instructions (misuse propensity). However, the likelihood of agents attempting misaligned behaviours in real-world settings (misalignment propensity) remains poorly understood. We introduce a misalignment propensity benchmark, AgentMisalignment, consisting of a suite of realistic scenarios in which LLM agents have the opportunity to display misaligned behaviour. We organise our evaluations into subcategories of misaligned behaviours, including goal-guarding, resisting shutdown, sandbagging, and power-seeking. We report the performance of frontier models on our benchmark, observing higher misalignment on average when evaluating more capable models. Finally, we systematically vary agent personalities through different system prompts. We find that persona characteristics can dramatically and unpredictably influence misalignment tendencies -- occasionally far more than the choice of model itself -- highlighting the importance of careful system prompt engineering for deployed AI agents. Our work highlights the failure of current alignment methods to generalise to LLM agents, and underscores the need for further propensity evaluations as autonomous systems become more prevalent.

[Arxiv](https://arxiv.org/abs/2506.04018)