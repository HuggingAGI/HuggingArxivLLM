# Psy-Insight：面向心理健康咨询的可解释多轮双语数据集

发布时间：2025年03月05日

`LLM应用

摘要中提到，大型语言模型（LLMs）在心理健康支持领域有潜力，但由于缺乏心理咨询数据集，特别是中文数据，限制了应用。为了解决这个问题，他们构建了一个名为Psy-Insight的数据集，专注于心理健康，是个多任务双语数据集。数据集包括多轮心理咨询对话，标注了多种标签和解释，涵盖心理治疗、情绪、策略、主题，以及回合级推理和会话级指导。这个数据集不仅用于标签识别，还能训练LLMs扮演有同理心的咨询师。实验显示，使用Psy-Insight训练的模型不仅能模仿对话风格，还能理解背后的策略和推理。

这篇论文的重点在于构建一个心理健康相关的数据集，并将其应用于训练LLMs在心理咨询中的应用。因此，它属于LLM应用类别。` `心理健康支持`

> Psy-Insight: Explainable Multi-turn Bilingual Dataset for Mental Health Counseling

# 摘要

> 大型语言模型（LLMs）的上下文学习能力在心理健康支持领域展现出巨大潜力。然而，心理咨询数据集的匮乏，尤其是中文语料中的缺失，限制了这一技术的应用。为解决这一问题，我们构建了Psy-Insight——首个专注于心理健康、可解释的多任务双语数据集。我们收集了面对面的多轮心理咨询对话，并标注了多任务标签及对话流程解释。我们的标注涵盖了心理治疗、情绪、策略和主题标签，以及回合级推理和会话级指导。Psy-Insight不仅适用于标签识别等任务，还满足了通过逻辑推理训练LLMs以扮演富有同理心的咨询师的需求。实验表明，使用Psy-Insight对LLMs进行训练，不仅能让模型模仿对话风格，还能使其理解心理咨询背后的策略和推理。

> The in-context learning capabilities of large language models (LLMs) show great potential in mental health support. However, the lack of counseling datasets, particularly in Chinese corpora, restricts their application in this field. To address this, we constructed Psy-Insight, the first mental health-oriented explainable multi-task bilingual dataset. We collected face-to-face multi-turn counseling dialogues, which are annotated with multi-task labels and conversation process explanations. Our annotations include psychotherapy, emotion, strategy, and topic labels, as well as turn-level reasoning and session-level guidance. Psy-Insight is not only suitable for tasks such as label recognition but also meets the need for training LLMs to act as empathetic counselors through logical reasoning. Experiments show that training LLMs on Psy-Insight enables the models to not only mimic the conversation style but also understand the underlying strategies and reasoning of counseling.

[Arxiv](https://arxiv.org/abs/2503.03607)