# 评估LLM中的二元决策偏差：对公平代理金融模拟的启示

发布时间：2025年01月20日

`LLM应用

理由：这篇论文主要探讨了将大型语言模型（LLMs）应用于基于代理的金融市场模型（ABMs）中的决策过程，并评估了不同模型及其子版本在决策中的偏见。论文关注的是LLMs在实际应用中的表现和影响，特别是如何将其整合到金融市场模型中，并讨论了采样方法和模型子版本对结果的影响。因此，这篇论文属于“LLM应用”类别。` `人工智能`

> Evaluating Binary Decision Biases in Large Language Models: Implications for Fair Agent-Based Financial Simulations

# 摘要

> 大型语言模型（LLMs）正越来越多地用于模拟基于代理的金融市场模型（ABMs）中的人类决策。随着模型能力的提升和易用性的增强，研究人员现在可以将单个LLM的决策整合到ABM环境中。然而，这种整合可能会带来需要仔细评估的固有偏见。本文通过一次性采样和少次采样API查询两种方法，测试了三种最先进的GPT模型的偏见。我们发现，不同模型及其子版本之间的输出分布存在显著差异，其中GPT-4o-Mini-2024-07-18表现更优（32-43%的“是”响应），而GPT-4-0125-preview则表现出极端偏见（98-99%的“是”响应）。我们展示了采样方法和模型子版本对结果的显著影响：重复的独立API调用与单次调用中的批量采样相比，会产生不同的分布。尽管目前没有GPT模型能在一次性测试中同时实现均匀分布和马尔可夫性质，但在某些条件下，少次采样可以接近均匀分布。我们探讨了温度参数，并提供了定义和比较结果。我们还将结果与真正的随机二进制序列进行了对比，并特别测试了人类常见的负向近期偏见——发现LLMs在这一方面具有混合的能力来“击败”人类。这些发现强调了将LLM谨慎整合到金融市场ABMs中的重要性，并具有更广泛的应用价值。

> Large Language Models (LLMs) are increasingly being used to simulate human-like decision making in agent-based financial market models (ABMs). As models become more powerful and accessible, researchers can now incorporate individual LLM decisions into ABM environments. However, integration may introduce inherent biases that need careful evaluation. In this paper we test three state-of-the-art GPT models for bias using two model sampling approaches: one-shot and few-shot API queries. We observe significant variations in distributions of outputs between specific models, and model sub versions, with GPT-4o-Mini-2024-07-18 showing notably better performance (32-43% yes responses) compared to GPT-4-0125-preview's extreme bias (98-99% yes responses). We show that sampling methods and model sub-versions significantly impact results: repeated independent API calls produce different distributions compared to batch sampling within a single call. While no current GPT model can simultaneously achieve a uniform distribution and Markovian properties in one-shot testing, few-shot sampling can approach uniform distributions under certain conditions. We explore the Temperature parameter, providing a definition and comparative results. We further compare our results to true random binary series and test specifically for the common human bias of Negative Recency - finding LLMs have a mixed ability to 'beat' humans in this one regard. These findings emphasise the critical importance of careful LLM integration into ABMs for financial markets and more broadly.

[Arxiv](https://arxiv.org/abs/2501.16356)