# Agent-SafetyBench：对 LLM 代理的安全性进行评估

发布时间：2024年12月18日

`Agent` `语言模型` `代理安全`

> Agent-SafetyBench: Evaluating the Safety of LLM Agents

# 摘要

> 随着大型语言模型（LLMs）愈发多地充当代理，它们融入交互环境和工具使用带来了新的安全挑战，这些挑战超出了模型自身相关的范畴。然而，缺乏评估代理安全性的综合基准，成为有效评估和进一步改进的重大阻碍。在本文中，我们推出了Agent-SafetyBench，这是一个专为评估LLM代理安全性而设的综合基准。Agent-SafetyBench涵盖349个交互环境和2000个测试案例，评估8类安全风险，包含了在不安全交互中常见的10种故障模式。我们对16个热门LLM代理的评估得出了令人忧心的结果：没有一个代理的安全分数能超过60%。这凸显了LLM代理存在显著的安全挑战，也强调了极大的改进需求。通过定量分析，我们明确了关键的故障模式，并总结出当前LLM代理的两个基本安全缺陷：缺乏稳健性和缺乏风险意识。此外，我们的发现表明，仅依赖防御提示无法解决这些安全问题，强调需要更先进、更强大的策略。我们在url{https://github.com/thu-coai/Agent-SafetyBench}发布了Agent-SafetyBench，以推动代理安全评估和改进方面的进一步研究与创新。

> As large language models (LLMs) are increasingly deployed as agents, their integration into interactive environments and tool use introduce new safety challenges beyond those associated with the models themselves. However, the absence of comprehensive benchmarks for evaluating agent safety presents a significant barrier to effective assessment and further improvement. In this paper, we introduce Agent-SafetyBench, a comprehensive benchmark designed to evaluate the safety of LLM agents. Agent-SafetyBench encompasses 349 interaction environments and 2,000 test cases, evaluating 8 categories of safety risks and covering 10 common failure modes frequently encountered in unsafe interactions. Our evaluation of 16 popular LLM agents reveals a concerning result: none of the agents achieves a safety score above 60%. This highlights significant safety challenges in LLM agents and underscores the considerable need for improvement. Through quantitative analysis, we identify critical failure modes and summarize two fundamental safety detects in current LLM agents: lack of robustness and lack of risk awareness. Furthermore, our findings suggest that reliance on defense prompts alone is insufficient to address these safety issues, emphasizing the need for more advanced and robust strategies. We release Agent-SafetyBench at url{https://github.com/thu-coai/Agent-SafetyBench} to facilitate further research and innovation in agent safety evaluation and improvement.

[Arxiv](https://arxiv.org/abs/2412.14470)