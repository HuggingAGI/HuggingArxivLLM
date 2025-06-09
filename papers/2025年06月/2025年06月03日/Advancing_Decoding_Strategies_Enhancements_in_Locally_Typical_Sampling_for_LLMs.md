# 探索解码策略：大型语言模型中局部典型采样的优化

发布时间：2025年06月03日

`LLM理论

理由：这篇论文探讨了大型语言模型（LLM）解码策略的改进，特别是提出了自适应语义感知典型性采样（ASTS）方法，属于对模型生成机制的理论研究和优化，因此归类为LLM理论。` `内容生成`

> Advancing Decoding Strategies: Enhancements in Locally Typical Sampling for LLMs

# 摘要

> 本章深入探讨了大型语言模型 (LLMs) 解码策略的最新进展，重点改进了 Locally Typical Sampling (LTS) 算法。传统的 top-k 和 nucleus 采样方法在文本生成中常难以平衡流利性、多样性和连贯性。为此，我们提出了自适应语义感知典型性采样 (ASTS)，作为 LTS 的升级版，它融合了动态熵阈值、多目标评分和奖励-惩罚调整机制。ASTS 在保持高效计算的同时，确保了上下文连贯且多样化的文本生成效果。通过故事生成和摘要生成等多基准测试，采用困惑度、MAUVE 和多样性分数等指标评估其性能。实验结果表明，ASTS 在减少重复、增强语义对齐和提升流利性方面显著优于现有采样技术。

> This chapter explores advancements in decoding strategies for large language models (LLMs), focusing on enhancing the Locally Typical Sampling (LTS) algorithm. Traditional decoding methods, such as top-k and nucleus sampling, often struggle to balance fluency, diversity, and coherence in text generation. To address these challenges, Adaptive Semantic-Aware Typicality Sampling (ASTS) is proposed as an improved version of LTS, incorporating dynamic entropy thresholding, multi-objective scoring, and reward-penalty adjustments. ASTS ensures contextually coherent and diverse text generation while maintaining computational efficiency. Its performance is evaluated across multiple benchmarks, including story generation and abstractive summarization, using metrics such as perplexity, MAUVE, and diversity scores. Experimental results demonstrate that ASTS outperforms existing sampling techniques by reducing repetition, enhancing semantic alignment, and improving fluency.

[Arxiv](https://arxiv.org/abs/2506.05387)