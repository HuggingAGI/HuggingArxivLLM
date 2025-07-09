# 语言模型在物联网安全日志威胁检测中的评估

发布时间：2025年07月03日

`LLM应用

理由：这篇论文探讨了大型语言模型在异常检测和缓解建议中的应用，特别是在物联网安全日志分析中的应用。论文对比了不同LLMs在分类任务中的表现，并讨论了微调策略。虽然涉及LLMs的安全性，但主要关注点是应用层面，而不是LLMs的理论或机制。` `网络安全` `物联网安全`

> Evaluating Language Models For Threat Detection in IoT Security Logs

# 摘要

> 日志分析是网络安全领域的研究重点，为网络与系统的威胁检测提供重要信息。本文提出了一种基于物联网安全日志的微调大型语言模型（LLMs）管道，用于异常检测与缓解建议。以经典机器学习分类器为基准，本文对比了三种开源LLMs在二分类与多分类异常检测中的表现，分别采用零样本、少样本提示和基于物联网数据集的微调策略。结果显示，LLMs在多分类攻击分类任务中表现更优。通过将检测到的威胁映射至MITRE CAPEC，定义物联网特定的缓解动作并进行模型微调，最终实现了检测与推荐指导的有机结合。

> Log analysis is a relevant research field in cybersecurity as they can provide a source of information for the detection of threats to networks and systems. This paper presents a pipeline to use fine-tuned Large Language Models (LLMs) for anomaly detection and mitigation recommendation using IoT security logs. Utilizing classical machine learning classifiers as a baseline, three open-source LLMs are compared for binary and multiclass anomaly detection, with three strategies: zero-shot, few-shot prompting and fine-tuning using an IoT dataset. LLMs give better results on multi-class attack classification than the corresponding baseline models. By mapping detected threats to MITRE CAPEC, defining a set of IoT-specific mitigation actions, and fine-tuning the models with those actions, the models are able to provide a combined detection and recommendation guidance.

[Arxiv](https://arxiv.org/abs/2507.02390)