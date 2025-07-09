# 重新审视人类标签变化下的主动学习

发布时间：2025年07月03日

`LLM应用` `机器学习`

> Revisiting Active Learning under (Human) Label Variation

# 摘要

> # 摘要
在应用监督学习中，高质量标注数据的获取仍是关键瓶颈。尽管标签变化（LV）在自然语言处理中常见，现有标注框架仍普遍假设单一真实标签，忽视了人类标签变化（HLV）这一重要信号。类似地，主动学习（AL）虽是优化有限标注预算的热门方法，却常依赖于难以在承认HLV情况下成立的简化假设。本文审视了关于真实标签本质的基本假设，强调将标签变化分解为信号（如HLV）与噪声（如标注错误）的重要性。我们综述了AL与（H）LV社区在处理这些区别上的进展与不足，并提出了一种整合HLV的主动学习概念框架，涵盖实例选择、注释者选择及标签表示。我们还探讨了将大型语言模型（LLM）作为注释者的可能性。本研究旨在为HLV感知主动学习奠定概念基础，更真实地反映现实世界标注的复杂性。


> Access to high-quality labeled data remains a limiting factor in applied supervised learning. While label variation (LV), i.e., differing labels for the same instance, is common, especially in natural language processing, annotation frameworks often still rest on the assumption of a single ground truth. This overlooks human label variation (HLV), the occurrence of plausible differences in annotations, as an informative signal. Similarly, active learning (AL), a popular approach to optimizing the use of limited annotation budgets in training ML models, often relies on at least one of several simplifying assumptions, which rarely hold in practice when acknowledging HLV. In this paper, we examine foundational assumptions about truth and label nature, highlighting the need to decompose observed LV into signal (e.g., HLV) and noise (e.g., annotation error). We survey how the AL and (H)LV communities have addressed -- or neglected -- these distinctions and propose a conceptual framework for incorporating HLV throughout the AL loop, including instance selection, annotator choice, and label representation. We further discuss the integration of large language models (LLM) as annotators. Our work aims to lay a conceptual foundation for HLV-aware active learning, better reflecting the complexities of real-world annotation.

[Arxiv](https://arxiv.org/abs/2507.02593)