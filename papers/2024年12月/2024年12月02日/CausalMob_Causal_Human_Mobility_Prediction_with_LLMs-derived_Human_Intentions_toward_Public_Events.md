# CausalMob：借助从LLM获取的人类对于公共事件的意图来进行因果人类移动性预测

发布时间：2024年12月02日

`LLM应用` `政策制定`

> CausalMob: Causal Human Mobility Prediction with LLMs-derived Human Intentions toward Public Events

# 摘要

> 大规模的人类流动展现出时空规律，能为政策制定者的决策提供帮助。尽管传统预测模型试图捕捉这些规律，却常被诸如灾难和偶尔的庆祝活动等非周期性公共事件所干扰。由于正常的人类流动规律深受这些事件影响，估算其因果效应对于精准的流动预测至关重要。虽然新闻文章以非结构化形式提供了关于这些事件的独特视角，但处理起来颇具挑战。在本研究中，我们提出了一种名为	extbf{CausalMob}的因果增强预测模型，用于剖析公共事件的因果效应。首先，我们借助大型语言模型（LLMs）从新闻文章中提取人类意图，并将其转化为充当因果处理的特征。接着，该模型从多个数据源学习时空区域协变量的表征，作为因果推断的混杂因素。最后，我们给出一个因果效应估计框架，确保在预测过程中事件特征独立于混杂因素。基于大规模的真实世界数据，实验结果显示，所提出的模型在人类流动预测方面表现卓越，胜过了最先进的模型。

> Large-scale human mobility exhibits spatial and temporal patterns that can assist policymakers in decision making. Although traditional prediction models attempt to capture these patterns, they often interfered by non-periodic public events, such as disasters and occasional celebrations. Since regular human mobility patterns are heavily affected by these events, estimating their causal effects is critical to accurate mobility predictions. Although news articles provide unique perspectives on these events in an unstructured format, processing is a challenge. In this study, we propose a causality-augmented prediction model, called \textbf{CausalMob}, to analyze the causal effects of public events. We first utilize large language models (LLMs) to extract human intentions from news articles and transform them into features that act as causal treatments. Next, the model learns representations of spatio-temporal regional covariates from multiple data sources to serve as confounders for causal inference. Finally, we present a causal effect estimation framework to ensure event features remain independent of confounders during prediction. Based on large-scale real-world data, the experimental results show that the proposed model excels in human mobility prediction, outperforming state-of-the-art models.

[Arxiv](https://arxiv.org/abs/2412.02155)