# SePA：面向个性化健康指导的搜索增强型预测智能体

发布时间：2025年09月04日

`LLM应用` `医疗健康`

> SePA: A Search-enhanced Predictive Agent for Personalized Health Coaching

# 摘要

> 本文提出了SePA（搜索增强型预测AI智能体）——一种新型LLM健康指导系统，它融合个性化机器学习与检索增强生成技术，可提供适应性强、循证的健康指导。SePA主要包含两部分：（1）基于可穿戴传感器数据预测日常压力、酸痛及受伤风险的个性化模型（28名用户，1260个数据点）；（2）检索模块，该模块将LLM生成的反馈锚定在专家验证的网络内容上，确保建议的上下文相关性和可靠性。通过滚动原点交叉验证与分组k折交叉验证评估发现，我们的预测模型中，个性化模型性能优于通用基线模型。在试点专家研究（n=4）中，SePA的检索式建议比非检索基线更受认可，且具有显著实际效果（Cliff's δ=0.3，p=0.05）。我们还量化了响应质量与速度间的延迟性能权衡，为下一代可信个人健康信息系统提供了清晰的设计蓝图。

> This paper introduces SePA (Search-enhanced Predictive AI Agent), a novel LLM health coaching system that integrates personalized machine learning and retrieval-augmented generation to deliver adaptive, evidence-based guidance. SePA combines: (1) Individualized models predicting daily stress, soreness, and injury risk from wearable sensor data (28 users, 1260 data points); and (2) A retrieval module that grounds LLM-generated feedback in expert-vetted web content to ensure contextual relevance and reliability. Our predictive models, evaluated with rolling-origin cross-validation and group k-fold cross-validation show that personalized models outperform generalized baselines. In a pilot expert study (n=4), SePA's retrieval-based advice was preferred over a non-retrieval baseline, yielding meaningful practical effect (Cliff's $δ$=0.3, p=0.05). We also quantify latency performance trade-offs between response quality and speed, offering a transparent blueprint for next-generation, trustworthy personal health informatics systems.

[Arxiv](https://arxiv.org/abs/2509.04752)