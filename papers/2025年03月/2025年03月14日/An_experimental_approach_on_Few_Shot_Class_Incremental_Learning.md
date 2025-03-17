# # 小样本类增量学习的实验方法研究

发布时间：2025年03月14日

`LLM应用` `机器学习` `计算机视觉`

> An experimental approach on Few Shot Class Incremental Learning

# 摘要

> # 摘要
少样本类增量学习 (FSCIL) 是机器学习领域的一项前沿技术，旨在让模型在仅有少量示例的情况下掌握新类别，同时保留已有的知识。本文将介绍多种解决方案，这些方案通过大规模数据集、领域迁移和不同网络架构的实验，对各种方法进行评估和比较。我们特别关注这些方法的优势，并提出一种实验方法，旨在通过用另一种视觉语言 (V-L) 模型 (CLOOB) 替换现有的 CLIP 模型来改进最有前景的方法，因为 CLOOB 在零样本学习任务上表现更优。本报告的目标是提出一种改进 FSCIL 性能的实验方法。我们还计划概述并分析 FSCIL 领域的最新进展，重点关注缓解灾难性遗忘和提高模型适应不断变化的任务与数据集的能力的各种策略。

> Few-Shot Class-Incremental Learning (FSCIL) represents a cutting-edge paradigm within the broader scope of machine learning, designed to empower models with the ability to assimilate new classes of data with limited examples while safeguarding existing knowledge. The paper will present different solutions which contain extensive experiments across large-scale datasets, domain shifts, and network architectures to evaluate and compare the selected methods. We highlight their advantages and then present an experimental approach with the purpose of improving the most promising one by replacing the visual-language (V-L) model (CLIP) with another V-L model (CLOOB) that seem to outperform it on zero-shot learning tasks. The aim of this report is to present an experimental method for FSCIL that would improve its performance. We also plan to offer an overview followed by an analysis of the recent advancements in FSCIL domain, focusing on various strategies to mitigate catastrophic forgetting and improve the adaptability of models to evolving tasks and datasets.

[Arxiv](https://arxiv.org/abs/2503.11349)