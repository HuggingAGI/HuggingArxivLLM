# # 真理无界：跨语言真实性的评估

发布时间：2025年02月13日

`LLM应用` `语言处理`

> Truth Knows No Language: Evaluating Truthfulness Beyond English

# 摘要

> 我们介绍了一个专业翻译的TruthfulQA基准测试扩展，旨在评估巴斯克语、加泰罗尼亚语、加利西亚语和西班牙语中的真实性。尽管大型语言模型（LLMs）的真实性评估主要是在英语中进行的，但LLMs在跨语言中保持真实性的能力仍然未被充分探索。本研究评估了12个最先进的开源LLM，通过人工评估、多项选择指标以及将LLM作为评分员的评分方法，比较了基础模型和指令微调模型的表现。研究发现，尽管LLMs在英语中表现最佳，在巴斯克语（资源最少的语言）中表现最差，但跨语言的真实性差异总体上比预期的要小。此外，我们将LLM作为评分员的评分方法与人工判断的相关性发现比多项选择指标更高，并且信息量在真实性评估中起到了关键作用。我们的结果还表明，机器翻译为扩展真实性基准到更多语言提供了一种可行的方法，为专业翻译提供了一种可扩展的替代方案。最后，我们观察到，通用知识问题在跨语言中比依赖上下文和时间的问题处理得更好，突显了在真实性评估中考虑文化和时间变化的必要性。数据集和代码在开放许可下公开可用。

> We introduce a professionally translated extension of the TruthfulQA benchmark designed to evaluate truthfulness in Basque, Catalan, Galician, and Spanish. Truthfulness evaluations of large language models (LLMs) have primarily been conducted in English. However, the ability of LLMs to maintain truthfulness across languages remains under-explored. Our study evaluates 12 state-of-the-art open LLMs, comparing base and instruction-tuned models using human evaluation, multiple-choice metrics, and LLM-as-a-Judge scoring. Our findings reveal that, while LLMs perform best in English and worst in Basque (the lowest-resourced language), overall truthfulness discrepancies across languages are smaller than anticipated. Furthermore, we show that LLM-as-a-Judge correlates more closely with human judgments than multiple-choice metrics, and that informativeness plays a critical role in truthfulness assessment. Our results also indicate that machine translation provides a viable approach for extending truthfulness benchmarks to additional languages, offering a scalable alternative to professional translation. Finally, we observe that universal knowledge questions are better handled across languages than context- and time-dependent ones, highlighting the need for truthfulness evaluations that account for cultural and temporal variability. Dataset and code are publicly available under open licenses.

[Arxiv](https://arxiv.org/abs/2502.09387)