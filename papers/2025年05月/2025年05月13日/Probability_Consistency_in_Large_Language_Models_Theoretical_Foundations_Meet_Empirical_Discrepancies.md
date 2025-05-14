# 概率一致性在大型语言模型中的探讨：理论与实证的差异

发布时间：2025年05月13日

`LLM理论` `模型评估`

> Probability Consistency in Large Language Models: Theoretical Foundations Meet Empirical Discrepancies

# 摘要

> 自回归大型语言模型（LLMs）在不同令牌顺序的序列上训练时，能否学习到一致的概率分布？我们从理论上证明，对于任何明确的概率分布，序列困惑度在任何分解下都保持不变，包括正向、反向或任意排列。这一发现不仅为研究LLMs的学习机制奠定了坚实的理论基础，还为实证评估提供了科学的评估协议。通过应用这些协议，我们揭示了先前研究在考察顺序效应时存在的关键方法学问题。我们在科学文本上对GPT-2模型进行了正向、反向和任意排列顺序的重新训练。实验发现，所有顺序均存在系统性偏离理论不变性，其中任意排列的模型与正向和反向模型存在显著差异，而正向和反向模型在很大程度上（但并非完全）一致。这些偏离可追溯到自注意力机制的差异，反映了模型在处理过程中存在的位置和局部性偏见。我们的理论和实证结果不仅为理解LLMs中的位置偏见提供了新的研究方向，还为检测LLMs概率分布的不一致性提供了方法，从而帮助判断其可靠性。


> Can autoregressive large language models (LLMs) learn consistent probability distributions when trained on sequences in different token orders? We prove formally that for any well-defined probability distribution, sequence perplexity is invariant under any factorization, including forward, backward, or arbitrary permutations. This result establishes a rigorous theoretical foundation for studying how LLMs learn from data and defines principled protocols for empirical evaluation. Applying these protocols, we show that prior studies examining ordering effects suffer from critical methodological flaws. We retrain GPT-2 models across forward, backward, and arbitrary permuted orders on scientific text. We find systematic deviations from theoretical invariance across all orderings with arbitrary permutations strongly deviating from both forward and backward models, which largely (but not completely) agreed with one another. Deviations were traceable to differences in self-attention, reflecting positional and locality biases in processing. Our theoretical and empirical results provide novel avenues for understanding positional biases in LLMs and suggest methods for detecting when LLMs' probability distributions are inconsistent and therefore untrustworthy.

[Arxiv](https://arxiv.org/abs/2505.08739)