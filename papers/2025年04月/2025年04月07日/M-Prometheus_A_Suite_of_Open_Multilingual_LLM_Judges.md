# # M-Prometheus：一个多语言LLM评测工具包

发布时间：2025年04月07日

`LLM应用` `多语言模型`

> M-Prometheus: A Suite of Open Multilingual LLM Judges

# 摘要

> 语言模型作为评估者自动评估长文本的应用越来越普遍，但目前大多数模型仅针对英语优化，多语言评估能力的提升策略尚未得到充分探索。这种不平衡限制了多语言模型的发展。为此，我们推出M-Prometheus，一套参数从3B到14B的开源LLM评估工具，支持多语言输出的直接评估和对比反馈。在覆盖20多种语言的基准测试和4种语言对的文学翻译评估中，M-Prometheus表现优于现有开源评估模型。此外，它在解码时能显著提升多语言生成质量，助力更强大的多语言模型开发。通过深入分析，我们发现选择合适的主干模型和使用原生多语言反馈数据是提升评估效果的关键。我们开源了模型、数据和代码，助力研究和应用。


> The use of language models for automatically evaluating long-form text (LLM-as-a-judge) is becoming increasingly common, yet most LLM judges are optimized exclusively for English, with strategies for enhancing their multilingual evaluation capabilities remaining largely unexplored in the current literature. This has created a disparity in the quality of automatic evaluation methods for non-English languages, ultimately hindering the development of models with better multilingual capabilities. To bridge this gap, we introduce M-Prometheus, a suite of open-weight LLM judges ranging from 3B to 14B parameters that can provide both direct assessment and pairwise comparison feedback on multilingual outputs. M-Prometheus models outperform state-of-the-art open LLM judges on multilingual reward benchmarks spanning more than 20 languages, as well as on literary machine translation (MT) evaluation covering 4 language pairs. Furthermore, M-Prometheus models can be leveraged at decoding time to significantly improve generated outputs across all 3 tested languages, showcasing their utility for the development of better multilingual models. Lastly, through extensive ablations, we identify the key factors for obtaining an effective multilingual judge, including backbone model selection and training on natively multilingual feedback data instead of translated data. We release our models, training dataset, and code.

[Arxiv](https://arxiv.org/abs/2504.04953)