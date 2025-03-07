# LLM引导的计划与检索：对话中用户满意度的可解释估计策略

发布时间：2025年03月06日

`LLM应用` `对话系统` `用户体验`

> LLM-guided Plan and Retrieval: A Strategic Alignment for Interpretable User Satisfaction Estimation in Dialogue

# 摘要

> 理解用户对对话系统的满意度（USE）对于评估对话质量和提升用户体验至关重要。然而，现有方法在USE方面面临两大挑战：对用户不满原因理解有限，以及标注用户意图成本高昂。为此，我们提出了PRAISE框架，一个用于有效预测用户满意度的可解释解决方案。PRAISE通过三个模块协同工作：策略规划器制定自然语言标准以分类用户满意度；特征检索器整合大型语言模型（LLMs）中的知识并提取 utterances 中的特征；评分分析器评估预测并分类用户满意度。实验表明，PRAISE在三个基准数据集上实现了最优性能。除了卓越的表现，PRAISE还通过实例级解释增强了可解释性，并在推理阶段无需使用LLMs，从而更高效。

> Understanding user satisfaction with conversational systems, known as User Satisfaction Estimation (USE), is essential for assessing dialogue quality and enhancing user experiences. However, existing methods for USE face challenges due to limited understanding of underlying reasons for user dissatisfaction and the high costs of annotating user intentions. To address these challenges, we propose PRAISE (Plan and Retrieval Alignment for Interpretable Satisfaction Estimation), an interpretable framework for effective user satisfaction prediction. PRAISE operates through three key modules. The Strategy Planner develops strategies, which are natural language criteria for classifying user satisfaction. The Feature Retriever then incorporates knowledge on user satisfaction from Large Language Models (LLMs) and retrieves relevance features from utterances. Finally, the Score Analyzer evaluates strategy predictions and classifies user satisfaction. Experimental results demonstrate that PRAISE achieves state-of-the-art performance on three benchmarks for the USE task. Beyond its superior performance, PRAISE offers additional benefits. It enhances interpretability by providing instance-level explanations through effective alignment of utterances with strategies. Moreover, PRAISE operates more efficiently than existing approaches by eliminating the need for LLMs during the inference phase.

[Arxiv](https://arxiv.org/abs/2503.04675)