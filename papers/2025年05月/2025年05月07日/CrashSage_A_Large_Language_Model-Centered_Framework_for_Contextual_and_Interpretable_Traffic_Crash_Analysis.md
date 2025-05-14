# CrashSage：基于大型语言模型的上下文感知与可解释交通事故分析框架

发布时间：2025年05月07日

`LLM应用` `道路安全` `交通事故分析`

> CrashSage: A Large Language Model-Centered Framework for Contextual and Interpretable Traffic Crash Analysis

# 摘要

> 全球每年约有130万人死于道路交通事故，造成超过1.8万亿美元的经济损失。这一严峻现实凸显了深入研究交通事故机制并提供实用解决方案的迫切需求。传统的统计模型和树集成方法在分析交通事故时存在明显局限：它们依赖结构化数据，忽视了情境细节，难以捕捉复杂的因果关系和潜在语义。此外，这些方法在处理涉及多车互动、事故演变和罕见事件特征等叙述性信息时，往往会导致重要信息的丢失。

本研究提出的CrashSage框架，通过四项创新突破了传统方法的局限。首先，我们开发了一种表格数据到文本的转换策略，结合关系数据集成模式，将零散的碰撞数据转化为结构完整、语义丰富的文本叙述。其次，借助基础LLM模型进行情境感知的数据增强，显著提升了叙述的连贯性，同时确保了事实的准确性。第三，我们对LLaMA3-8B模型进行了针对性微调，用于事故严重性推断，并在多个模型（包括GPT-4o、GPT-4o-mini、LLaMA3-70B）上验证了其优越性，性能远超零样本学习、零样本链式思维提示和少量样本学习等基线方法。最后，我们采用基于梯度的可解释性技术，深入解析模型在单次事故分析和整体风险因素评估中的决策逻辑。这一可解释性机制不仅增强了模型的透明度，还通过揭示关键影响因素，为制定精准的道路安全干预措施提供了科学依据。


> Road crashes claim over 1.3 million lives annually worldwide and incur global economic losses exceeding \$1.8 trillion. Such profound societal and financial impacts underscore the urgent need for road safety research that uncovers crash mechanisms and delivers actionable insights. Conventional statistical models and tree ensemble approaches typically rely on structured crash data, overlooking contextual nuances and struggling to capture complex relationships and underlying semantics. Moreover, these approaches tend to incur significant information loss, particularly in narrative elements related to multi-vehicle interactions, crash progression, and rare event characteristics. This study presents CrashSage, a novel Large Language Model (LLM)-centered framework designed to advance crash analysis and modeling through four key innovations. First, we introduce a tabular-to-text transformation strategy paired with relational data integration schema, enabling the conversion of raw, heterogeneous crash data into enriched, structured textual narratives that retain essential structural and relational context. Second, we apply context-aware data augmentation using a base LLM model to improve narrative coherence while preserving factual integrity. Third, we fine-tune the LLaMA3-8B model for crash severity inference, demonstrating superior performance over baseline approaches, including zero-shot, zero-shot with chain-of-thought prompting, and few-shot learning, with multiple models (GPT-4o, GPT-4o-mini, LLaMA3-70B). Finally, we employ a gradient-based explainability technique to elucidate model decisions at both the individual crash level and across broader risk factor dimensions. This interpretability mechanism enhances transparency and enables targeted road safety interventions by providing deeper insights into the most influential factors.

[Arxiv](https://arxiv.org/abs/2505.07853)