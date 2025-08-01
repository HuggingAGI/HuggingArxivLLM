# 因果推理分步：模块化上下文学习助力因果发现

发布时间：2025年07月31日

`LLM应用` `因果推理` `跨领域应用`

> Causal Reasoning in Pieces: Modular In-Context Learning for Causal Discovery

# 摘要

> 因果推理仍是大型语言模型的核心挑战。随着大型语言模型内部推理技术的最新进展，研究界开始关注当前最先进的推理模型是否能稳健地完成因果发现任务——传统模型在数据扰动下往往表现欠佳，容易过拟合且效果接近随机。我们基于 OpenAI 的 o 系列和 DeepSeek-R 模型，在 Corr2Cause 基准数据集上进行因果发现研究，发现这些以推理为导向的架构较以往方法取得了显著的性能提升。为了进一步发挥这些模型的优势，我们设计了一种受 Tree-of-Thoughts 和 Chain-of-Thoughts 方法启发的模块化 in-context 管道，与传统基线相比，性能提升了近三倍。通过分析推理链的长度和复杂性，并对传统模型与推理模型进行定性和定量对比，我们深入探究了该管道的影响。研究结果表明，尽管先进推理模型带来了显著的性能提升，但精心设计的 in-context 框架对于充分发挥其潜力至关重要，同时也为跨领域因果发现提供了一个通用的解决方案。

> Causal inference remains a fundamental challenge for large language models. Recent advances in internal reasoning with large language models have sparked interest in whether state-of-the-art reasoning models can robustly perform causal discovery-a task where conventional models often suffer from severe overfitting and near-random performance under data perturbations. We study causal discovery on the Corr2Cause benchmark using the emergent OpenAI's o-series and DeepSeek-R model families and find that these reasoning-first architectures achieve significantly greater native gains than prior approaches. To capitalize on these strengths, we introduce a modular in-context pipeline inspired by the Tree-of-Thoughts and Chain-of-Thoughts methodologies, yielding nearly three-fold improvements over conventional baselines. We further probe the pipeline's impact by analyzing reasoning chain length, complexity, and conducting qualitative and quantitative comparisons between conventional and reasoning models. Our findings suggest that while advanced reasoning models represent a substantial leap forward, carefully structured in-context frameworks are essential to maximize their capabilities and offer a generalizable blueprint for causal discovery across diverse domains.

[Arxiv](https://arxiv.org/abs/2507.23488)