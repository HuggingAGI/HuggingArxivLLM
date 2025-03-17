# CALLM: 基于大型语言模型和检索增强型移动日记的癌症幸存者上下文感知情绪分析

发布时间：2025年03月12日

`LLM应用` `情绪分析`

> CALLM: Context-Aware Emotion Analysis in Cancer Survivors Using LLMs and Retrieval-Augmented Mobile Diaries

# 摘要

> 癌症幸存者常常面临影响生活质量的独特情感挑战。移动日记——通过手机记录的简短情感体验——提供了一种有前景的实时追踪方法。尽管情绪分析工具在从文本中识别情绪方面有潜力，但现有方法难以准确理解移动日记中的简短个人叙述。我们提出了CALLM，一个基于检索增强生成（RAG）的大型语言模型（LLMs）的情境感知情绪分析框架，用于分析癌症幸存者的移动日记，预测他们的情绪状态。通过整合同伴经验作为情境示例，并纳入个人的时间情绪轨迹，CALLM显著提升了预测准确性。我们收集了包含407名癌症幸存者的移动生态瞬时评估（EMA）数据集，评估了积极和消极情绪、调节情绪的愿望、社交互动质量以及对干预的可用性，并附带开放响应格式的每日移动日记条目。结果显示，CALLM表现出色，积极情绪的平衡准确率达到72.96%，消极情绪为73.29%，预测个体调节情绪愿望的准确率为73.72%。事后分析表明，利用模型置信度、鼓励更长的日记条目以及纳入个人真实情况，可以进一步提升预测结果。我们的研究支持在慢性健康人群中部署基于LLM的情绪分析，并为癌症幸存者的个性化干预提供了新方向。

> Cancer survivors face unique emotional challenges that impact their quality of life. Mobile diary entries-short text entries recording through their phone about their emotional experiences-provide a promising method for tracking these experiences in real time. Although emotion analysis tools show potential for recognizing emotions from text, current methods lack the contextual understanding necessary to accurately interpret the brief, personal narratives in mobile diaries. We propose CALLM, a context-aware emotion analysis framework that leverages Large Language Models (LLMs) with Retrieval-Augmented Generation (RAG), to analyze mobile diary entries from cancer survivors to predict their emotional states. The framework enhances prediction accuracy beyond existing methods by (1) integrating retrieved peer experiences as contextual examples and (2) incorporating individuals' temporal emotional trajectories from their mobile diary entries. We collected a large-scale dataset (N=407) of cancer survivors' mobile ecological momentary assessments (EMAs), which assessed positive and negative affect, desire to regulate emotions, social interaction quality, and availability for interventions, alongside daily mobile diary entries in an open response format regarding what was driving their current emotional experience. Results demonstrate strong performance of CALLM, with balanced accuracies reaching 72.96% for positive and 73.29% for negative affect, and 73.72% for predicting individual's desire to regulate emotions. Post-hoc analysis reveals that leveraging model confidence, encouraging longer diary entries, and incorporating personal ground truth, further enhance predictive outcomes. Our findings support the feasibility of deploying LLM-powered emotion analysis in chronic health populations and suggest promising directions for personalized interventions for cancer survivors.

[Arxiv](https://arxiv.org/abs/2503.10707)