# # 真实能力检验：如何评估大型语言模型的性能指标？

发布时间：2025年05月13日

`LLM应用` `人工智能`

> Evaluating LLM Metrics Through Real-World Capabilities

# 摘要

> 生成式 AI 日渐融入日常 workflows，评估其在真实世界使用中的表现至关重要，而非局限于抽象智能概念。与现有侧重通用智能的基准不同，我们的方法聚焦于现实实用性，评估模型在日常任务中对用户的实际支持效果。当前基准多侧重代码生成或事实检索，而用户对 AI 的依赖范围更广，涵盖写作辅助、摘要、引用格式化和风格反馈等多方面。

本文通过分析大规模调查数据和使用日志，识别出六项代表人们日常使用大型语言模型（LLMs）的核心能力：总结、技术协助、审阅工作、数据结构化、生成和信息检索。我们评估现有基准在这些能力上的覆盖程度，发现存在显著的覆盖范围、效率衡量和可解释性方面的差距。基于此分析，我们采用以人为本的标准，依据五项实际标准——连贯性、准确性、清晰度、相关性和效率——识别当前基准在反映日常使用方面的不足。

对于六项核心能力中的四项，我们识别出最符合真实世界任务的基准，并利用它们来比较领先模型。结果显示，Google Gemini 在这些以实用性为导向的指标上优于其他模型，包括 OpenAI 的 GPT、xAI 的 Grok、Meta 的 LLaMA、Anthropic 的 Claude、DeepSeek 以及阿里巴巴的 Qwen。


> As generative AI becomes increasingly embedded in everyday workflows, it is important to evaluate its performance in ways that reflect real-world usage rather than abstract notions of intelligence. Unlike many existing benchmarks that assess general intelligence, our approach focuses on real-world utility, evaluating how well models support users in everyday tasks. While current benchmarks emphasize code generation or factual recall, users rely on AI for a much broader range of activities-from writing assistance and summarization to citation formatting and stylistic feedback. In this paper, we analyze large-scale survey data and usage logs to identify six core capabilities that represent how people commonly use Large Language Models (LLMs): Summarization, Technical Assistance, Reviewing Work, Data Structuring, Generation, and Information Retrieval. We then assess the extent to which existing benchmarks cover these capabilities, revealing significant gaps in coverage, efficiency measurement, and interpretability. Drawing on this analysis, we use human-centered criteria to identify gaps in how well current benchmarks reflect common usage that is grounded in five practical criteria: coherence, accuracy, clarity, relevance, and efficiency. For four of the six capabilities, we identify the benchmarks that best align with real-world tasks and use them to compare leading models. We find that Google Gemini outperforms other models-including OpenAI's GPT, xAI's Grok, Meta's LLaMA, Anthropic's Claude, DeepSeek, and Qwen from Alibaba-on these utility-focused metrics.

[Arxiv](https://arxiv.org/abs/2505.08253)