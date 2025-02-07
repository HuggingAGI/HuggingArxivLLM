# 大型语言模型的偏斜记忆：量化与分解

发布时间：2025年02月03日

`LLM理论

理由：这篇论文主要探讨了大型语言模型（LLMs）中的记忆化问题，分析了其与训练时长、数据集规模和样本相似性的关联，并提出了风险检测与缓解策略。这些内容涉及LLM的内部机制和理论分析，属于对LLM的理论研究，因此归类为“LLM理论”。` `隐私保护` `人工智能安全`

> Skewed Memorization in Large Language Models: Quantification and Decomposition

# 摘要

> # 摘要
大型语言模型（LLMs）中的记忆化问题引发了隐私和安全风险，模型可能无意中泄露敏感或受版权保护的数据。现有研究多关注平均情况，忽视了记忆化分布的严重偏斜。本文深入探讨了LLM监督微调（SFT）中的记忆化现象，分析了其与训练时长、数据集规模和样本相似性的关联。通过研究序列长度对记忆化概率的影响，我们揭示了这种偏斜性与令牌生成过程的联系，为记忆化估计和指标对比提供了新视角。结合理论分析与实证研究，我们全面解析了记忆化行为，并提出了风险检测与缓解策略，助力构建更安全的LLMs。

> Memorization in Large Language Models (LLMs) poses privacy and security risks, as models may unintentionally reproduce sensitive or copyrighted data. Existing analyses focus on average-case scenarios, often neglecting the highly skewed distribution of memorization. This paper examines memorization in LLM supervised fine-tuning (SFT), exploring its relationships with training duration, dataset size, and inter-sample similarity. By analyzing memorization probabilities over sequence lengths, we link this skewness to the token generation process, offering insights for estimating memorization and comparing it to established metrics. Through theoretical analysis and empirical evaluation, we provide a comprehensive understanding of memorization behaviors and propose strategies to detect and mitigate risks, contributing to more privacy-preserving LLMs.

[Arxiv](https://arxiv.org/abs/2502.01187)