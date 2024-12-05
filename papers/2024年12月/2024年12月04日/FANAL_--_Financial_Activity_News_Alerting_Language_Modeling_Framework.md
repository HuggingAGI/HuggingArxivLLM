# FANAL——金融活动新闻警报语言建模框架

发布时间：2024年12月04日

`LLM应用` `新闻分析`

> FANAL -- Financial Activity News Alerting Language Modeling Framework

# 摘要

> 在快速演变的金融领域，对于需要应对不可预测事件的利益相关方而言，准确且及时地解读市场新闻至关重要。本文引入了 FANAL（金融活动新闻警报语言建模框架），这是一个专为实时金融事件检测与分析打造的基于 BERT 的框架，它将新闻划分为十二种不同的金融类别。FANAL 借助通过 XGBoost 处理的银标数据，并运用先进的微调技术，还有 ORBERT（赔率比 BERT），这是通过 ORPO（赔率比偏好优化）微调的 BERT 新变体，用于实现更出色的类别概率校准以及与金融事件相关性的匹配。我们将 FANAL 的性能与领先的大型语言模型（如 GPT-4o、Llama-3.1 8B 和 Phi-3）进行对比评估，展现出其卓越的准确性和成本效益。该框架为金融智能和响应能力树立了新标杆，在性能和性价比方面均大幅超越现有模型。

> In the rapidly evolving financial sector, the accurate and timely interpretation of market news is essential for stakeholders needing to navigate unpredictable events. This paper introduces FANAL (Financial Activity News Alerting Language Modeling Framework), a specialized BERT-based framework engineered for real-time financial event detection and analysis, categorizing news into twelve distinct financial categories. FANAL leverages silver-labeled data processed through XGBoost and employs advanced fine-tuning techniques, alongside ORBERT (Odds Ratio BERT), a novel variant of BERT fine-tuned with ORPO (Odds Ratio Preference Optimization) for superior class-wise probability calibration and alignment with financial event relevance. We evaluate FANAL's performance against leading large language models, including GPT-4o, Llama-3.1 8B, and Phi-3, demonstrating its superior accuracy and cost efficiency. This framework sets a new standard for financial intelligence and responsiveness, significantly outstripping existing models in both performance and affordability.

[Arxiv](https://arxiv.org/abs/2412.03527)