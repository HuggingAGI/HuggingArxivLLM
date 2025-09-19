# 关注差距：深入探究大型语言模型（LLMs）在多项选择题问答中的分词问题

发布时间：2025年09月18日

`LLM应用` `基础理论`

> Mind the Gap: A Closer Look at Tokenization for Multiple-Choice Question Answering with LLMs

# 摘要

> 在利用多项选择题（MCQA）评估大型语言模型（LLMs）时，人们常在提示词末尾添加"Answer:"，以便借助下一个token的概率自动提取答案。但对于冒号后空格的分词方式，学界尚未达成共识，这一细节常因看似微不足道而被忽略。本文研究发现，这种看似无关的分词差异竟会造成高达11%的准确率波动，还会导致模型排名大洗牌，这让人们开始质疑以往LLM对比研究的可靠性。意外的是，我们找到了一个最优策略：将空格与答案字母合并分词。采用这一方法后，模型性能实现了持续且统计显著的提升。此外，该策略还能优化模型校准，提升模型置信度估计的可信度。这些发现凸显了精心设计评估方案的必要性，同时也呼吁建立标准化、透明的评估协议，从而保障研究结果的可靠性与可比性。

> When evaluating large language models (LLMs) with multiple-choice question answering (MCQA), it is common to end the prompt with the string "Answer:" to facilitate automated answer extraction via next-token probabilities. However, there is no consensus on how to tokenize the space following the colon, often overlooked as a trivial choice. In this paper, we uncover accuracy differences of up to 11% due to this (seemingly irrelevant) tokenization variation as well as reshuffled model rankings, raising concerns about the reliability of LLM comparisons in prior work. Surprisingly, we are able to recommend one specific strategy -- tokenizing the space together with the answer letter -- as we observe consistent and statistically significant performance improvements. Additionally, it improves model calibration, enhancing the reliability of the model's confidence estimates. Our findings underscore the importance of careful evaluation design and highlight the need for standardized, transparent evaluation protocols to ensure reliable and comparable results.

[Arxiv](https://arxiv.org/abs/2509.15020)