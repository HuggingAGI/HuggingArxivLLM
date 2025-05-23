# T1: 一个多轮智能规划任务的工具导向型对话数据集

发布时间：2025年05月22日

`Agent` `人工智能` `智能体`

> T1: A Tool-Oriented Conversational Dataset for Multi-Turn Agentic Planning

# 摘要

> 大型语言模型（LLMs）展示了作为智能体解决复杂问题的卓越能力。然而，在涉及API或工具调用之间依赖关系的场景中，特别是在多轮对话中，有效规划仍具挑战性。为此，我们推出了T1，一个工具增强的、多领域、多轮对话数据集，专为捕捉和管理跨领域工具间依赖关系而设计。T1支持在九个不同领域（包括4个单领域和5个多领域）中严格评估智能体协调工具使用的能力，并借助集成的缓存机制支持短期和长期记忆，同时支持动态重新规划，例如决定是否重新计算或重用缓存结果。除了促进工具使用和规划的研究，T1还作为评估开源语言模型性能的基准。我们展示了由T1-Agent提供的结果，突显了它们在复杂、依赖工具的场景中进行规划和推理的能力。

> Large Language Models (LLMs) have demonstrated impressive capabilities as intelligent agents capable of solving complex problems. However, effective planning in scenarios involving dependencies between API or tool calls-particularly in multi-turn conversations-remains a significant challenge. To address this, we introduce T1, a tool-augmented, multi-domain, multi-turn conversational dataset specifically designed to capture and manage inter-tool dependencies across diverse domains. T1 enables rigorous evaluation of agents' ability to coordinate tool use across nine distinct domains (4 single domain and 5 multi-domain) with the help of an integrated caching mechanism for both short- and long-term memory, while supporting dynamic replanning-such as deciding whether to recompute or reuse cached results. Beyond facilitating research on tool use and planning, T1 also serves as a benchmark for evaluating the performance of open-source language models. We present results powered by T1-Agent, highlighting their ability to plan and reason in complex, tool-dependent scenarios.

[Arxiv](https://arxiv.org/abs/2505.16986)