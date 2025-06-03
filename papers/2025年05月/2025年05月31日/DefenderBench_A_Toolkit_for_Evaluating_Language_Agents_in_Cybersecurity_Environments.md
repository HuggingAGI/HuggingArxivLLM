# DefenderBench：专为网络安全环境设计的语言代理能力评估工具箱

发布时间：2025年05月31日

`LLM应用

理由：这篇论文探讨了大型语言模型（LLM）在网络安全领域的应用，特别是通过DefenderBench工具包评估其在攻击、防御和网络安全知识任务中的表现。这属于LLM的具体应用领域，因此归类为LLM应用。` `网络安全` `人工智能`

> DefenderBench: A Toolkit for Evaluating Language Agents in Cybersecurity Environments

# 摘要

> 大型语言模型（LLM）代理在语言理解和推理方面表现出色，但在网络安全领域的潜力尚未充分挖掘。我们推出 DefenderBench，一个实用且开源的工具包，专注于评估语言模型在攻击、防御和网络安全知识任务中的表现。DefenderBench 提供了网络入侵、恶意内容检测、代码漏洞分析和网络安全知识评估等环境。它专为研究人员设计，价格实惠且易于获取，同时确保评估的公平性和严谨性。我们采用标准化代理框架对多个最先进（SoTA）和流行的 LLM 进行了基准测试，涵盖开放和闭合权重模型。结果显示，Claude-3.7-sonnet 以 81.65 的 DefenderBench 评分领先，Claude-3.7-sonnet-think 以 78.40 紧随其后，而最佳开放权重模型 Llama 3.3 70B 以 71.81 的评分位列第三。DefenderBench 的模块化设计支持定制 LLM 和任务的无缝集成，助力研究的可重复性和公平比较。如需获取 DefenderBench 的匿名版本，请访问 https://github.com/microsoft/DefenderBench。

> Large language model (LLM) agents have shown impressive capabilities in human language comprehension and reasoning, yet their potential in cybersecurity remains underexplored. We introduce DefenderBench, a practical, open-source toolkit for evaluating language agents across offense, defense, and cybersecurity knowledge-based tasks. DefenderBench includes environments for network intrusion, malicious content detection, code vulnerability analysis, and cybersecurity knowledge assessment. It is intentionally designed to be affordable and easily accessible for researchers while providing fair and rigorous assessment. We benchmark several state-of-the-art (SoTA) and popular LLMs, including both open- and closed-weight models, using a standardized agentic framework. Our results show that Claude-3.7-sonnet performs best with a DefenderBench score of 81.65, followed by Claude-3.7-sonnet-think with 78.40, while the best open-weight model, Llama 3.3 70B, is not far behind with a DefenderBench score of 71.81. DefenderBench's modular design allows seamless integration of custom LLMs and tasks, promoting reproducibility and fair comparisons. An anonymized version of DefenderBench is available at https://github.com/microsoft/DefenderBench.

[Arxiv](https://arxiv.org/abs/2506.00739)