# 研究和理解对话LLM修复的有效性和失败情况

发布时间：2025年03月19日

`LLM应用` `软件工程` `人工智能`

> Studying and Understanding the Effectiveness and Failures of Conversational LLM-Based Repair

# 摘要

> 自动化程序修复（APR）旨在实现漏洞修复的自动化。近年来，得益于大型语言模型（LLMs）的快速发展，自动化修复取得了长足进展。其中，基于对话型LLMs的高级APR技术，尤其是以ChatGPT为代表的工具，凭借其强大的修复反馈能力和迭代补丁改进能力，展现出卓越的修复能力，并日益受到青睐。尽管具备优势，对话型APR技术仍无法修复大量漏洞。例如，最先进的对话型技术ChatRepair未能正确修复Defects4J数据集中过半的单功能漏洞。为深入理解基于对话型LLM的修复效果及其失败原因，并为改进提供可能方向，我们以ChatRepair为例展开研究，重点比较其填空式与全功能修复策略的有效性，评估其关键迭代组件在补丁改进中的作用，并分析修复失败的原因。我们的研究揭示了一系列重要发现，这些发现为未来研究提供了关键启示。

> Automated program repair (APR) is designed to automate the process of bug-fixing. In recent years, thanks to the rapid development of large language models (LLMs), automated repair has achieved remarkable progress. Advanced APR techniques powered by conversational LLMs, most notably ChatGPT, have exhibited impressive repair abilities and gained increasing popularity due to the capabilities of the underlying LLMs in providing repair feedback and performing iterative patch improvement. Despite the superiority, conversational APR techniques still fail to repair a large number of bugs. For example, a state-of-the-art conversational technique ChatRepair does not correctly repair over half of the single-function bugs in the Defects4J dataset. To understand the effectiveness and failures of conversational LLM-based repair and provide possible directions for improvement, we studied the exemplary ChatRepair with a focus on comparing the effectiveness of its cloze-style and full function repair strategies, assessing its key iterative component for patch improvement, and analyzing the repair failures. Our study has led to a series of findings, which we believe provide key implications for future research.

[Arxiv](https://arxiv.org/abs/2503.15050)