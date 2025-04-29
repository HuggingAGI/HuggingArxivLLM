# # Chatbot Arena 与 Nuggets 相遇：探索 LLM 响应评估中的解释与诊断工具
大型语言模型（LLMs）的聊天机器人竞技场与 Nuggets 相遇，致力于开发用于评估 LLM 响应的解释与诊断工具。

发布时间：2025年04月28日

`RAG` `信息检索` `问答系统`

> Chatbot Arena Meets Nuggets: Towards Explanations and Diagnostics in the Evaluation of LLM Responses

# 摘要

> 对战评估方法，即在所谓的竞技场中进行并排比较以激发人类偏好，已成为评估大型语言模型 (LLM) 输出质量的流行手段。近期，这一方法已扩展至检索增强生成 (RAG) 系统。尽管在评估领域有所创新，但对战方法在复杂信息查询场景下存在两大局限：缺乏解释性与诊断性。近期，nugget 评估方法作为一种评估 RAG 回答质量的有前景方案应运而生。nuggets 将长篇 LLM 生成的回答拆解为原子事实，突出了“优质”回答所需的重要信息片段。本研究中，我们运用 AutoNuggetizer 框架，以全自动方式分析了 LMArena 提供的约 7,000 个搜索竞技场战斗数据。结果显示，nugget 评分与人类偏好高度相关，彰显了我们在可解释性和诊断性系统评估方面方法的潜力。

> Battles, or side-by-side comparisons in so called arenas that elicit human preferences, have emerged as a popular approach to assessing the output quality of LLMs. Recently, this idea has been extended to retrieval-augmented generation (RAG) systems. While undoubtedly representing an advance in evaluation, battles have at least two drawbacks, particularly in the context of complex information-seeking queries: they are neither explanatory nor diagnostic. Recently, the nugget evaluation methodology has emerged as a promising approach to evaluate the quality of RAG answers. Nuggets decompose long-form LLM-generated answers into atomic facts, highlighting important pieces of information necessary in a "good" response. In this work, we apply our AutoNuggetizer framework to analyze data from roughly 7K Search Arena battles provided by LMArena in a fully automatic manner. Our results show a significant correlation between nugget scores and human preferences, showcasing promise in our approach to explainable and diagnostic system evaluations.

[Arxiv](https://arxiv.org/abs/2504.20006)