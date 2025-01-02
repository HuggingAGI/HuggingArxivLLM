# 探究检索增强生成中置信度的影响：以医疗领域为例

发布时间：2024年12月28日

`RAG`

> Understanding the Impact of Confidence in Retrieval Augmented Generation: A Case Study in the Medical Domain

# 摘要

> 检索增强生成（RAG）借助外部信息来补充大型语言模型（LLMs）的知识，从而提升对查询的响应精准度。此方法因能注入最新信息，在多个领域广泛应用，研究人员正致力于理解并改进这一点，以在高风险应用中充分释放 RAG 的潜能。然而，尽管 RAG 有望满足这些需求，但即便信息的置信度在金融、医疗保健和医学等某些领域至关重要，其输出置信水平背后的机制仍未被充分探究。我们的研究聚焦于各种配置和模型下，RAG 对医疗领域置信度的影响。我们把模型的预测概率当作输出，依据概率和准确性计算预期校准误差（ECE）和自适应校准误差（ACE）分数来评估置信度。另外，我们分析提示中检索文档的顺序是否校准了置信度。我们的发现显示，置信度和准确性会因模型、设置以及输入提示的格式而有很大差异。这些结果凸显了根据特定模型和条件优化配置的必要性。

> Retrieval Augmented Generation (RAG) complements the knowledge of Large Language Models (LLMs) by leveraging external information to enhance response accuracy for queries. This approach is widely applied in several fields by taking its advantage of injecting the most up-to-date information, and researchers are focusing on understanding and improving this aspect to unlock the full potential of RAG in such high-stakes applications. However, despite the potential of RAG to address these needs, the mechanisms behind the confidence levels of its outputs remain underexplored, although the confidence of information is very critical in some domains, such as finance, healthcare, and medicine. Our study focuses the impact of RAG on confidence within the medical domain under various configurations and models. We evaluate confidence by treating the model's predicted probability as its output and calculating Expected Calibration Error (ECE) and Adaptive Calibration Error (ACE) scores based on the probabilities and accuracy. In addition, we analyze whether the order of retrieved documents within prompts calibrates the confidence. Our findings reveal large variation in confidence and accuracy depending on the model, settings, and the format of input prompts. These results underscore the necessity of optimizing configurations based on the specific model and conditions.

[Arxiv](https://arxiv.org/abs/2412.20309)