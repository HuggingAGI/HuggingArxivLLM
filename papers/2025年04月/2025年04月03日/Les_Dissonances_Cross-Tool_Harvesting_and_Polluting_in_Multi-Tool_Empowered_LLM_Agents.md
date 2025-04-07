# # 工具间冲突：多工具增强的大型语言模型代理中的跨工具信息采集与污染

发布时间：2025年04月03日

`Agent` `人工智能`

> Les Dissonances: Cross-Tool Harvesting and Polluting in Multi-Tool Empowered LLM Agents

# 摘要

> 大型语言模型（LLM）代理是由LLM驱动的自主系统，能够通过工具进行推理和规划以解决问题。然而，多工具能力的集成带来了安全挑战，包括工具管理、兼容性、依赖关系和控制流保护。本文首次对多工具LLM代理的任务控制流进行系统性安全分析，发现了一种新型威胁——跨工具收割与污染（XTHP）。这一威胁通过劫持控制流收集和污染系统中的敏感信息。为评估其影响，我们开发了Chord工具，用于自动检测易受XTHP攻击的代理工具。对来自LangChain和LlamaIndex框架的73个工具的评估显示：80%的工具易受劫持攻击，78%易受XTH攻击，41%易受XTP攻击，凸显了这一威胁的普遍性。

> Large Language Model (LLM) agents are autonomous systems powered by LLMs, capable of reasoning and planning to solve problems by leveraging a set of tools. However, the integration of multi-tool capabilities in LLM agents introduces challenges in securely managing tools, ensuring their compatibility, handling dependency relationships, and protecting control flows within LLM agent workflows. In this paper, we present the first systematic security analysis of task control flows in multi-tool-enabled LLM agents. We identify a novel threat, Cross-Tool Harvesting and Polluting (XTHP), which includes multiple attack vectors to first hijack the normal control flows of agent tasks, and then collect and pollute confidential or private information within LLM agent systems. To understand the impact of this threat, we developed Chord, a dynamic scanning tool designed to automatically detect real-world agent tools susceptible to XTHP attacks. Our evaluation of 73 real-world tools from the repositories of two major LLM agent development frameworks, LangChain and LlamaIndex, revealed a significant security concern: 80% of the tools are vulnerable to hijacking attacks, 78% to XTH attacks, and 41% to XTP attacks, highlighting the prevalence of this threat.

[Arxiv](https://arxiv.org/abs/2504.03111)