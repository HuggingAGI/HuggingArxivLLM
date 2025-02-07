# OrcaLoca: 软件问题定位的LLM代理框架

发布时间：2025年02月01日

`Agent

理由：这篇论文主要讨论了一个名为OrcaLoca的LLM代理框架，该框架通过集成多种技术（如基于优先级的LLM引导操作调度、带相关性评分的操作分解和距离感知的上下文修剪）来提升软件问题定位的准确性。论文的核心是LLM代理在自主软件工程中的应用，因此应归类为Agent。` `软件工程` `自动化`

> OrcaLoca: An LLM Agent Framework for Software Issue Localization

# 摘要

> # 摘要
大型语言模型（LLM）代理的最新进展正在革新自主软件工程（ASE），实现了自动化编码、问题修复和功能改进。然而，精准定位软件问题——通过导航到相关代码部分——仍是一个重大挑战。由于LLM代理与精确代码搜索机制之间缺乏有效集成，现有方法往往效果不佳。本文提出OrcaLoca，一个LLM代理框架，通过集成基于优先级的LLM引导操作调度、带相关性评分的操作分解和距离感知的上下文修剪，显著提升了软件问题定位的准确性。实验结果显示，OrcaLoca在SWE-bench Lite上的函数匹配率（65.33%）成为新的开源SOTA，并通过补丁生成集成将开源框架的最终解决率提高了6.33个百分点。

> Recent developments in Large Language Model (LLM) agents are revolutionizing Autonomous Software Engineering (ASE), enabling automated coding, problem fixes, and feature improvements. However, localization -- precisely identifying software problems by navigating to relevant code sections -- remains a significant challenge. Current approaches often yield suboptimal results due to a lack of effective integration between LLM agents and precise code search mechanisms. This paper introduces OrcaLoca, an LLM agent framework that improves accuracy for software issue localization by integrating priority-based scheduling for LLM-guided action, action decomposition with relevance scoring, and distance-aware context pruning. Experimental results demonstrate that OrcaLoca becomes the new open-source state-of-the-art (SOTA) in function match rate (65.33%) on SWE-bench Lite. It also improves the final resolved rate of an open-source framework by 6.33 percentage points through its patch generation integration.

[Arxiv](https://arxiv.org/abs/2502.00350)