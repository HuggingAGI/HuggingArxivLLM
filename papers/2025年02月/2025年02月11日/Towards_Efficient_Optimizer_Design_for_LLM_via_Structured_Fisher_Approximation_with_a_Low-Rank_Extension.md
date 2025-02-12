# 基于结构化费舍尔近似与低秩扩展的LLM优化器高效设计方法

发布时间：2025年02月11日

`LLM理论

论文摘要：为大型语言模型（LLMs）设计高效优化器，要求低内存占用和快速收敛，是一项重要且具挑战性的任务。本文通过结构化费舍尔信息矩阵（FIM）近似的视角，向系统化设计此类优化器迈出了重要一步。我们发现，众多先进的高效优化器本质上是在特定结构假设下对FIM进行近似的解决方案（基于弗罗贝尼乌斯范数）。基于此，我们为LLMs的优化器设计提出两点实用建议：其一，谨慎选择结构假设，以实现通用性和效率的平衡；其二，通过创新的低秩扩展框架，提升通用结构优化器的内存效率。我们通过设计新的内存高效优化器——行和列缩放随机梯度下降（RACS）和自适应低维子空间估计（Alice）——来展示这些设计方法的实际应用。在LLaMA预训练（高达10亿参数）的实验中，这些优化器展现出显著优势，不仅收敛速度更快，效果更佳，而且内存占用极低。特别值得一提的是，Alice的收敛速度比Adam快出两倍，而RACS在10亿参数模型上表现优异，内存需求与随机梯度下降相当。` `机器学习` `人工智能`

> Towards Efficient Optimizer Design for LLM via Structured Fisher Approximation with a Low-Rank Extension

# 摘要

> 为大型语言模型（LLMs）设计高效优化器，要求低内存占用和快速收敛，是一项重要且具挑战性的任务。本文通过结构化费舍尔信息矩阵（FIM）近似的视角，向系统化设计此类优化器迈出了重要一步。我们发现，众多先进的高效优化器本质上是在特定结构假设下对FIM进行近似的解决方案（基于弗罗贝尼乌斯范数）。基于此，我们为LLMs的优化器设计提出两点实用建议：其一，谨慎选择结构假设，以实现通用性和效率的平衡；其二，通过创新的低秩扩展框架，提升通用结构优化器的内存效率。我们通过设计新的内存高效优化器——行和列缩放随机梯度下降（RACS）和自适应低维子空间估计（Alice）——来展示这些设计方法的实际应用。在LLaMA预训练（高达10亿参数）的实验中，这些优化器展现出显著优势，不仅收敛速度更快，效果更佳，而且内存占用极低。特别值得一提的是，Alice的收敛速度比Adam快出两倍，而RACS在10亿参数模型上表现优异，内存需求与随机梯度下降相当。

> Designing efficient optimizers for large language models (LLMs) with low-memory requirements and fast convergence is an important and challenging problem. This paper makes a step towards the systematic design of such optimizers through the lens of structured Fisher information matrix (FIM) approximation. We show that many state-of-the-art efficient optimizers can be viewed as solutions to FIM approximation (under the Frobenius norm) with specific structural assumptions. Building on these insights, we propose two design recommendations of practical efficient optimizers for LLMs, involving the careful selection of structural assumptions to balance generality and efficiency, and enhancing memory efficiency of optimizers with general structures through a novel low-rank extension framework. We demonstrate how to use each design approach by deriving new memory-efficient optimizers: Row and Column Scaled SGD (RACS) and Adaptive low-dimensional subspace estimation (Alice). Experiments on LLaMA pre-training (up to 1B parameters) validate the effectiveness, showing faster and better convergence than existing memory-efficient baselines and Adam with little memory overhead. Notably, Alice achieves better than 2x faster convergence over Adam, while RACS delivers strong performance on the 1B model with SGD-like memory.

[Arxiv](https://arxiv.org/abs/2502.07752)