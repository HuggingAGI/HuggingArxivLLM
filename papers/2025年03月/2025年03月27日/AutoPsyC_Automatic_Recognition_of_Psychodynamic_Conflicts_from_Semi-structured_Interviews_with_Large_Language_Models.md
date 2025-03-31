# AutoPsyC：借助大型语言模型自动识别半结构化访谈中的心理动力冲突

发布时间：2025年03月27日

`RAG` `心理学` `精神病学`

> AutoPsyC: Automatic Recognition of Psychodynamic Conflicts from Semi-structured Interviews with Large Language Models

# 摘要

> 心理动力学冲突是持续存在、常常无意识的主题，它们深刻影响着一个人的行为和体验。精准诊断这些冲突对于有效治疗患者至关重要，传统上主要通过长期的手动评分半结构化访谈来完成。现有精神病诊断自动化方案多聚焦于抑郁症等广泛精神障碍类别的识别，而对于心理动力学冲突（甚至患者自身可能都无法有意识地察觉到的）能在多大程度上通过对话自动识别，目前尚不明确。本文中，我们提出了AutoPsyC，这是首个利用大型语言模型（LLMs）从完整的操作化心理动力学诊断（OPD）访谈中识别心理动力学冲突的存在和重要性的方法。我们的方法结合了参数高效微调和检索增强生成（RAG）的最新进展，并采用总结策略来有效处理长达90分钟的完整对话。在包含141次诊断访谈的数据集上进行评估，结果显示AutoPsyC在四种高度相关心理动力学冲突的识别上始终优于所有基线和消融实验条件。

> Psychodynamic conflicts are persistent, often unconscious themes that shape a person's behaviour and experiences. Accurate diagnosis of psychodynamic conflicts is crucial for effective patient treatment and is commonly done via long, manually scored semi-structured interviews. Existing automated solutions for psychiatric diagnosis tend to focus on the recognition of broad disorder categories such as depression, and it is unclear to what extent psychodynamic conflicts which even the patient themselves may not have conscious access to could be automatically recognised from conversation. In this paper, we propose AutoPsyC, the first method for recognising the presence and significance of psychodynamic conflicts from full-length Operationalized Psychodynamic Diagnostics (OPD) interviews using Large Language Models (LLMs). Our approach combines recent advances in parameter-efficient fine-tuning and Retrieval-Augmented Generation (RAG) with a summarisation strategy to effectively process entire 90 minute long conversations. In evaluations on a dataset of 141 diagnostic interviews we show that AutoPsyC consistently outperforms all baselines and ablation conditions on the recognition of four highly relevant psychodynamic conflicts.

[Arxiv](https://arxiv.org/abs/2503.21911)