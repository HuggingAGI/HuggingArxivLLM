# # 智能体大型语言模型中的游戏工具偏好研究

发布时间：2025年05月23日

`Agent` `智能体` `工具使用`

> Gaming Tool Preferences in Agentic LLMs

# 摘要

> 大型语言模型 (LLMs) 现在可以通过模型上下文协议 (MCP) 访问广泛的外部工具，极大地扩展了它们作为各类智能体的能力。然而，LLMs 完全依赖工具的文本描述来决定使用哪些工具，这一过程却意外地脆弱。在本研究中，我们通过一系列对工具描述的修改，揭示了广泛使用的工具/函数调用协议中的一个漏洞。实验表明，与原始描述相比，经过适当编辑的工具描述使 GPT-4.1 和 Qwen2.5-7B 对这些工具的使用量增加了超过 10 倍。我们进一步评估了不同工具描述修改在直接竞争中的表现，以及这些趋势在更广泛的 10 种不同模型中的一致性或差异性。这些现象虽然为开发者提供了一种强大的方法来推广他们的工具，但也突显了为智能体 LLM 提供一个更可靠的基础以选择和利用工具及资源的必要性。

> Large language models (LLMs) can now access a wide range of external tools, thanks to the Model Context Protocol (MCP). This greatly expands their abilities as various agents. However, LLMs rely entirely on the text descriptions of tools to decide which ones to use--a process that is surprisingly fragile. In this work, we expose a vulnerability in prevalent tool/function-calling protocols by investigating a series of edits to tool descriptions, some of which can drastically increase a tool's usage from LLMs when competing with alternatives. Through controlled experiments, we show that tools with properly edited descriptions receive over 10 times more usage from GPT-4.1 and Qwen2.5-7B than tools with original descriptions. We further evaluate how various edits to tool descriptions perform when competing directly with one another and how these trends generalize or differ across a broader set of 10 different models. These phenomenons, while giving developers a powerful way to promote their tools, underscore the need for a more reliable foundation for agentic LLMs to select and utilize tools and resources.

[Arxiv](https://arxiv.org/abs/2505.18135)