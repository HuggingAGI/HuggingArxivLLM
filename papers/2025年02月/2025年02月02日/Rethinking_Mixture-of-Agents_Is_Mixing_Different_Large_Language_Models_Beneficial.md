# 混合代理再思考：融合不同大型语言模型是否真的有益？

发布时间：2025年02月02日

`Agent

理由：这篇论文主要讨论了混合代理（Mixture-of-Agents, MoA）和Self-MoA方法，这些方法涉及多个大型语言模型（LLMs）的集成和优化。论文的核心在于如何通过集成不同LLMs的输出或仅集成单个表现最佳的LLM输出来提升性能。这属于Agent的范畴，因为Agent通常涉及多个智能体的协作或集成，以完成特定任务或优化性能。论文中的Self-MoA方法可以被视为一种智能体（Agent）的优化策略，旨在通过动态选择和集成LLM输出来提升整体性能。` `机器学习`

> Rethinking Mixture-of-Agents: Is Mixing Different Large Language Models Beneficial?

# 摘要

> # 摘要
集成多源输出是一种简单却高效的性能提升方法。混合代理（Mixture-of-Agents, MoA）作为一种流行的集成方法，聚合了多个不同大型语言模型（LLMs）的输出。本文在语言模型的背景下提出了一个关键问题：混合不同的LLMs真的有益吗？我们提出了Self-MoA——一种仅聚合单个表现最佳LLM输出的集成方法。大量实验表明，令人惊讶的是，Self-MoA在众多场景中优于混合不同LLMs的标准MoA：在AlpacaEval 2.0基准测试中，Self-MoA比MoA提升了6.6%，在MMLU、CRUX和MATH等基准测试中平均提升了3.8%。将Self-MoA应用于AlpacaEval 2.0中的一个顶级模型，直接刷新了排行榜的最先进性能。为了深入理解Self-MoA的有效性，我们系统研究了不同MoA设置下输出多样性与质量之间的权衡。我们发现，MoA性能对质量极为敏感，混合不同LLMs往往会降低模型的平均质量。为了补充研究，我们还识别了混合不同LLMs可能有益的特定场景。本文进一步提出了Self-MoA的序列版本，能够在多轮中动态聚合大量LLM输出，效果与一次性聚合所有输出相当。

> Ensembling outputs from diverse sources is a straightforward yet effective approach to boost performance. Mixture-of-Agents (MoA) is one such popular ensemble method that aggregates outputs from multiple different Large Language Models (LLMs). This paper raises the question in the context of language models: is mixing different LLMs truly beneficial? We propose Self-MoA -- an ensemble method that aggregates outputs from only the single top-performing LLM. Our extensive experiments reveal that, surprisingly, Self-MoA outperforms standard MoA that mixes different LLMs in a large number of scenarios: Self-MoA achieves $6.6\%$ improvement over MoA on the AlpacaEval 2.0 benchmark, and an average of $3.8\%$ improvement across various benchmarks, including MMLU, CRUX, and MATH. Applying Self-MoA to one of the top-ranking models in AlpacaEval 2.0 directly achieves the new state-of-the-art performance on the leaderboard. To understand the effectiveness of Self-MoA, we systematically investigate the trade-off between diversity and quality of outputs under various MoA settings. We confirm that the MoA performance is rather sensitive to the quality, and mixing different LLMs often lowers the average quality of the models. To complement the study, we identify the scenarios where mixing different LLMs could be helpful. This paper further introduces a sequential version of Self-MoA, that is capable of aggregating a large number of LLM outputs on-the-fly over multiple rounds, and is as effective as aggregating all outputs at once.

[Arxiv](https://arxiv.org/abs/2502.00674)