# LogTinyLLM：基于上下文日志异常检测的小型大型语言模型

发布时间：2025年07月15日

`LLM应用` `系统维护与开发` `日志分析`

> LogTinyLLM: Tiny Large Language Models Based Contextual Log Anomaly Detection

# 摘要

> 日志异常检测在传统基于规则或深度学习的方法中常常面临挑战，主要由于日志序列数据量庞大且复杂性高。有效识别异常的日志序列对系统维护与开发至关重要。本文提出了一种参数高效的微调方法，特别是低秩适应（LoRA）和适配器方法，用于在大型日志数据集中发现上下文异常。研究在Thunderbird数据集上对比了不同小型大型语言模型（LLMs）的表现。结果显示，基于LoRA的微调方法相较于基于LogBert的全微调方法，性能提升了18%到19%，准确率范围为97.76%到98.83%，而LogBert的准确率为79.37%。


> Log anomaly detection using traditional rule based or deep learning based methods is often challenging due to the large volume and highly complex nature of log sequence. So effective way of detection of anomalous sequence of logs is crucial for system maintenance and development. This paper proposes parameter efficient finetuning specifically low rank adaptation (LoRA) and adapter based approaches for finding contextual anomalies in sequence of logs in large log data set. It compares different tiny large language models (LLMs) on the Thunderbird dataset. The results show that LoRA based finetuning provides substantial performance improvements of 18 to 19 percentage over LogBert based full finetuning approach, achieving accuracy scores between 97.76% and 98.83% compared to 79.37%.

[Arxiv](https://arxiv.org/abs/2507.11071)