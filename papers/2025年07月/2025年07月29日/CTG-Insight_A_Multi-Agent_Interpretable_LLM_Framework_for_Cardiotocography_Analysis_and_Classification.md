# # **CTG-Insight: 用于心电图分析与分类的多智能体可解释 LLM 框架**

发布时间：2025年07月29日

`Agent` `医疗健康` `医学监测`

> CTG-Insight: A Multi-Agent Interpretable LLM Framework for Cardiotocography Analysis and Classification

# 摘要

> 远程胎儿监护技术正变得越来越普遍，但现有系统大多缺乏足够的可解释性，准父母往往只能面对难以理解的胎心监护（CTG）数据。为此，我们推出了CTG-Insight——一个多智能体LLM系统，专注于提供胎儿心率（FHR）和宫缩（UC）信号的结构化解释。基于医学指南，CTG-Insight将每份CTG记录分解为基线、变异、加速、减速和正弦波模式五个特征，每个特征由专门的智能体深入分析。最终，聚合智能体综合各部分结果，给出胎儿健康的整体评估，并辅以自然语言解释。在NeuroFetalNet数据集上的评估显示，CTG-Insight不仅达到了96.4%的准确率和97.8%的F1分数，还实现了透明且易于理解的输出。这项研究为CTG分析提供了一个可解释且可扩展的全新框架。

> Remote fetal monitoring technologies are becoming increasingly common. Yet, most current systems offer limited interpretability, leaving expectant parents with raw cardiotocography (CTG) data that is difficult to understand. In this work, we present CTG-Insight, a multi-agent LLM system that provides structured interpretations of fetal heart rate (FHR) and uterine contraction (UC) signals. Drawing from established medical guidelines, CTG-Insight decomposes each CTG trace into five medically defined features: baseline, variability, accelerations, decelerations, and sinusoidal pattern, each analyzed by a dedicated agent. A final aggregation agent synthesizes the outputs to deliver a holistic classification of fetal health, accompanied by a natural language explanation. We evaluate CTG-Insight on the NeuroFetalNet Dataset and compare it against deep learning models and the single-agent LLM baseline. Results show that CTG-Insight achieves state-of-the-art accuracy (96.4%) and F1-score (97.8%) while producing transparent and interpretable outputs. This work contributes an interpretable and extensible CTG analysis framework.

[Arxiv](https://arxiv.org/abs/2507.22205)