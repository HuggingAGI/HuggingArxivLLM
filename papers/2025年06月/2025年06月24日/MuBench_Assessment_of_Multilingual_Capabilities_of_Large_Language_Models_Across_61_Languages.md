# # MuBench：评测大型语言模型跨61种语言的多语言能力

发布时间：2025年06月24日

`LLM应用

理由：这篇论文主要探讨了多语言大语言模型的评估和改进，属于大型语言模型的应用层面。` `模型评估`

> MuBench: Assessment of Multilingual Capabilities of Large Language Models Across 61 Languages

# 摘要

> 多语言大语言模型（LLMs）发展迅猛，新模型层出不穷，不断声称支持越来越多的语言。然而，现有的评估数据集不仅数量有限，而且缺乏跨语言对齐，导致对多语言能力的评估在语言和技能覆盖方面都显得分散。为了解决这一问题，我们推出了涵盖61种语言的MuBench基准，全面评估模型能力。通过对多个先进多语言LLM的评估，我们发现声明的语言覆盖范围与实际覆盖范围之间存在显著差距，特别是在英语和低资源语言之间持续存在性能差异。借助MuBench的对齐能力，我们提出了多语言一致性（MLC）作为准确性的补充指标，用于分析性能瓶颈并指导模型改进。最后，我们使用5000亿个tokens在英语和中文上预训练了一组12亿参数的模型，通过调整语言比例和并行数据比例来研究跨语言迁移的动态。

> Multilingual large language models (LLMs) are advancing rapidly, with new models frequently claiming support for an increasing number of languages. However, existing evaluation datasets are limited and lack cross-lingual alignment, leaving assessments of multilingual capabilities fragmented in both language and skill coverage. To address this, we introduce MuBench, a benchmark covering 61 languages and evaluating a broad range of capabilities. We evaluate several state-of-the-art multilingual LLMs and find notable gaps between claimed and actual language coverage, particularly a persistent performance disparity between English and low-resource languages. Leveraging MuBench's alignment, we propose Multilingual Consistency (MLC) as a complementary metric to accuracy for analyzing performance bottlenecks and guiding model improvement. Finally, we pretrain a suite of 1.2B-parameter models on English and Chinese with 500B tokens, varying language ratios and parallel data proportions to investigate cross-lingual transfer dynamics.

[Arxiv](https://arxiv.org/abs/2506.19468)