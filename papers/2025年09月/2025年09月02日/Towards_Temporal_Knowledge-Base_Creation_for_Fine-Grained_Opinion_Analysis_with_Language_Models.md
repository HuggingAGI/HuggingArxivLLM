# 面向细粒度观点分析：利用语言模型构建时序知识库

发布时间：2025年09月02日

`LLM应用` `基础理论`

> Towards Temporal Knowledge-Base Creation for Fine-Grained Opinion Analysis with Language Models

# 摘要

> 我们提出了一种可扩展方法，利用大型语言模型（LLMs）作为自动标注器构建时间观点知识库。尽管文本的时间序列观点分析在预测、趋势分析等下游应用中已展现实用价值，但现有方法因缺乏时间锚定的细粒度标注，未能充分释放其潜力。我们的方法通过将成熟的观点挖掘框架融入声明式LLM标注流程，填补了这一空白，无需手动提示工程即可实现结构化观点提取。我们基于情感与观点挖掘文献定义了三种数据模型，作为结构化表示的框架。我们利用人工标注的测试样本，对该流程进行了严格的定量评估。我们使用两个独立的LLM完成最终标注，并参照人工标注规范，在细粒度观点维度上按标签计算标注者间一致性。最终构建的知识库涵盖时间对齐的结构化观点，可应用于检索增强生成（RAG）、时间问答及时间线总结等场景。

> We propose a scalable method for constructing a temporal opinion knowledge base with large language models (LLMs) as automated annotators. Despite the demonstrated utility of time-series opinion analysis of text for downstream applications such as forecasting and trend analysis, existing methodologies underexploit this potential due to the absence of temporally grounded fine-grained annotations. Our approach addresses this gap by integrating well-established opinion mining formulations into a declarative LLM annotation pipeline, enabling structured opinion extraction without manual prompt engineering. We define three data models grounded in sentiment and opinion mining literature, serving as schemas for structured representation. We perform rigorous quantitative evaluation of our pipeline using human-annotated test samples. We carry out the final annotations using two separate LLMs, and inter-annotator agreement is computed label-wise across the fine-grained opinion dimensions, analogous to human annotation protocols. The resulting knowledge base encapsulates time-aligned, structured opinions and is compatible with applications in Retrieval-Augmented Generation (RAG), temporal question answering, and timeline summarisation.

[Arxiv](https://arxiv.org/abs/2509.02363)