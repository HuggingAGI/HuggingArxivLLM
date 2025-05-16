# 大型语言模型是否具备冲突认知？研究LLMs在冲突预测中的参数化与非参数化知识差异

发布时间：2025年05月14日

`LLM应用` `冲突预测`

> Do Large Language Models Know Conflict? Investigating Parametric vs. Non-Parametric Knowledge of LLMs for Conflict Forecasting

# 摘要

> 大型语言模型（LLMs）在自然语言任务中表现卓越，但它们预测暴力冲突的能力仍有待深入挖掘。我们研究了LLMs是否具备参数化知识——即其预训练权重中编码的信息——来预测冲突升级和伤亡，而无需外部数据支持。这对早期预警系统、人道主义规划和政策制定至关重要。我们通过检索增强生成（RAG）方法，对比了LLMs的参数化与非参数化能力，使其能够从冲突数据集（如ACLED、GDELT）和近期新闻报道中获取结构化和非结构化的上下文信息。整合外部信息能够弥补预训练权重的不足，从而提升模型性能。我们的两阶段评估框架覆盖了2020年至2024年期间非洲之角和中东冲突频发地区的冲突情况。在参数化设置中，LLMs仅依赖预训练知识预测冲突趋势和伤亡情况；而在非参数化设置中，模型会收到近期冲突事件摘要、指标和地缘政治动态。我们将预测的冲突趋势标签（如升级、稳定冲突、降级、和平）和伤亡情况与历史数据进行对比。研究结果不仅揭示了LLMs在冲突预测方面的优势与局限性，还凸显了通过结构化外部知识增强其能力的重要性。

> Large Language Models (LLMs) have shown impressive performance across natural language tasks, but their ability to forecast violent conflict remains underexplored. We investigate whether LLMs possess meaningful parametric knowledge-encoded in their pretrained weights-to predict conflict escalation and fatalities without external data. This is critical for early warning systems, humanitarian planning, and policy-making. We compare this parametric knowledge with non-parametric capabilities, where LLMs access structured and unstructured context from conflict datasets (e.g., ACLED, GDELT) and recent news reports via Retrieval-Augmented Generation (RAG). Incorporating external information could enhance model performance by providing up-to-date context otherwise missing from pretrained weights. Our two-part evaluation framework spans 2020-2024 across conflict-prone regions in the Horn of Africa and the Middle East. In the parametric setting, LLMs predict conflict trends and fatalities relying only on pretrained knowledge. In the non-parametric setting, models receive summaries of recent conflict events, indicators, and geopolitical developments. We compare predicted conflict trend labels (e.g., Escalate, Stable Conflict, De-escalate, Peace) and fatalities against historical data. Our findings highlight the strengths and limitations of LLMs for conflict forecasting and the benefits of augmenting them with structured external knowledge.

[Arxiv](https://arxiv.org/abs/2505.09852)