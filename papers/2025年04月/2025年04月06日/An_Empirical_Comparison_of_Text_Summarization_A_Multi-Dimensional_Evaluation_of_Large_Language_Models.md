# # 文本摘要的实证对比研究：对大型语言模型的多维度评估

发布时间：2025年04月06日

`LLM应用` `文本摘要`

> An Empirical Comparison of Text Summarization: A Multi-Dimensional Evaluation of Large Language Models

# 摘要

> 文本摘要在新闻、医学和商业等领域缓解信息过载方面具有重要作用。本研究通过创新的多维框架，评估了来自 OpenAI、Google、Anthropic 和开源社区的 17 个大型语言模型的摘要性能。我们从 BigPatent、BillSum、CNN/DailyMail、PubMed、SAMSum、WikiHow 和 XSum 七个多样化数据集中选取 50、100 和 150 个令牌三种输出长度，采用事实一致性、语义相似性、词汇重叠和类人质量等指标进行评估，同时考虑效率因素。

研究发现不同模型表现差异显著：deepseek-v3 在事实准确性上领先，claude-3-5-sonnet 在类人质量上表现突出，而 gemini-1.5-flash 和 gemini-2.0-flash 在处理效率和成本效益上优势明显。模型在技术领域表现较弱，但在对话内容上表现出色。我们发现事实一致性（50 个令牌时最佳）与感知质量（150 个令牌时最佳）之间存在关键的权衡关系。

本研究为不同应用场景提供了基于证据的建议，从需要事实准确性的高风险应用到需要高效处理的资源受限环境。通过整合质量指标与运营考虑，综合分析了准确性、效率和成本效益的权衡，为特定应用的模型选择提供了指导。
    

> Text summarization is crucial for mitigating information overload across domains like journalism, medicine, and business. This research evaluates summarization performance across 17 large language models (OpenAI, Google, Anthropic, open-source) using a novel multi-dimensional framework. We assessed models on seven diverse datasets (BigPatent, BillSum, CNN/DailyMail, PubMed, SAMSum, WikiHow, XSum) at three output lengths (50, 100, 150 tokens) using metrics for factual consistency, semantic similarity, lexical overlap, and human-like quality, while also considering efficiency factors. Our findings reveal significant performance differences, with specific models excelling in factual accuracy (deepseek-v3), human-like quality (claude-3-5-sonnet), and processing efficiency/cost-effectiveness (gemini-1.5-flash, gemini-2.0-flash). Performance varies dramatically by dataset, with models struggling on technical domains but performing well on conversational content. We identified a critical tension between factual consistency (best at 50 tokens) and perceived quality (best at 150 tokens). Our analysis provides evidence-based recommendations for different use cases, from high-stakes applications requiring factual accuracy to resource-constrained environments needing efficient processing. This comprehensive approach enhances evaluation methodology by integrating quality metrics with operational considerations, incorporating trade-offs between accuracy, efficiency, and cost-effectiveness to guide model selection for specific applications.

[Arxiv](https://arxiv.org/abs/2504.04534)