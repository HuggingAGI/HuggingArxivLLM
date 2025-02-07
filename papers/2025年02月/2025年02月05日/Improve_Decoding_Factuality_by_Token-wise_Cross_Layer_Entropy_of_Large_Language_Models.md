# 利用大型语言模型的逐层交叉熵提升解码准确性

发布时间：2025年02月05日

`LLM理论

理由：这篇论文主要探讨了大型语言模型（LLMs）在生成内容时出现的幻觉问题，并提出了一种新的解码方法（跨层熵增强解码，END）来缓解这一问题。论文的核心在于通过分析隐藏状态预测变化与输出事实性之间的相关性，提出了一种理论上的改进方法，并进行了实验验证。因此，这篇论文属于对LLM的理论研究和改进，而不是具体的应用或代理（Agent）相关的研究。` `人工智能`

> Improve Decoding Factuality by Token-wise Cross Layer Entropy of Large Language Models

# 摘要

> 尽管大型语言模型（LLMs）能力出众，但它们常因生成不准确或虚构内容而陷入幻觉问题，即便拥有正确知识。本文深入探讨了隐藏状态预测变化与输出事实性之间的相关性，并将其扩展至逐令牌层面。基于此，我们提出了跨层熵增强解码（END），一种无需额外训练即可缓解幻觉的解码方法。END通过跨层内部概率变化，量化每个候选令牌所需的事实知识，并调整预测分布，优先选择事实性更高的令牌。实验表明，END在幻觉和问答基准测试中显著提升了生成内容的真实性和信息量，同时保持了高问答准确性。此外，我们的研究为理解内在知识与输出事实性之间的关联提供了新视角。

> Despite their impressive capacities, Large language models (LLMs) often struggle with the hallucination issue of generating inaccurate or fabricated content even when they possess correct knowledge. In this paper, we extend the exploration of the correlation between hidden-state prediction changes and output factuality into a deeper, token-wise level. Based on the insights , we propose cross-layer Entropy eNhanced Decoding (END), a decoding method that mitigates hallucinations without requiring extra training. END leverages inner probability changes across layers to individually quantify the factual knowledge required for each candidate token, and adjusts the final predicting distribution to prioritize tokens with higher factuality. Experiments on both hallucination and QA benchmarks demonstrate that END significantly enhances the truthfulness and informativeness of generated content while maintaining robust QA accuracy. Moreover, our work provides a deeper perspective on understanding the correlations between inherent knowledge and output factuality.

[Arxiv](https://arxiv.org/abs/2502.03199)