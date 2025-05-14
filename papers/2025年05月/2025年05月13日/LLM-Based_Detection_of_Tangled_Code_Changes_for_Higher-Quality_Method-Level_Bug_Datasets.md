# 基于 LLM 的复杂代码变更检测，助力构建更高质量的方法级缺陷数据集

发布时间：2025年05月13日

`LLM应用` `软件工程`

> LLM-Based Detection of Tangled Code Changes for Higher-Quality Method-Level Bug Datasets

# 摘要

> 混乱的代码变更——将 bug 修复、重构和增强等无关修改混杂在一起的提交——给 bug 数据集带来了显著噪声，对 bug 预测模型的性能产生了负面影响。目前，从细粒度、方法级别的角度来解决这一问题的研究仍显不足。这至关重要，因为近期的 bug 预测模型正越来越多地关注更细粒度的预测，而非传统的类级别或文件级别预测。本研究探讨了大型语言模型（LLMs）在检测混乱代码变更方面的实用性，结合提交消息和方法级别代码差异。我们将问题建模为二元分类任务，评估了零样本、少样本和链式思考提示等多种提示策略，使用了 GPT-4o 和 Gemini-2.0-Flash 等最新专有 LLM。结果显示，结合提交消息与代码差异显著提升了模型性能，其中结合少样本和链式思考提示的策略达到了 0.88 的 F1 分数。此外，基于 LLM 生成嵌入的嵌入式机器学习模型中，多层感知机分类器表现尤为出色（F1 分数：0.906，MCC：0.807）。这对研究界来说是鼓舞人心的，因为方法级别 bug 预测仍是一个开放问题，很大程度上是由于缺乏无噪声的 bug 数据集。这项研究不仅为解决混乱代码变更提供了方法级别视角，还为提升自动化软件质量评估工具提供了实用途径。

> Tangled code changes-commits that conflate unrelated modifications such as bug fixes, refactorings, and enhancements-introduce significant noise into bug datasets and adversely affect the performance of bug prediction models. Addressing this issue at a fine-grained, method-level granularity remains underexplored. This is critical to address, as recent bug prediction models, driven by practitioner demand, are increasingly focusing on finer granularity rather than traditional class- or file-level predictions. This study investigates the utility of Large Language Models (LLMs) for detecting tangled code changes by leveraging both commit messages and method-level code diffs. We formulate the problem as a binary classification task and evaluate multiple prompting strategies, including zero-shot, few-shot, and chain-of-thought prompting, using state-of-the-art proprietary LLMs such as GPT-4o and Gemini-2.0-Flash.
  Our results demonstrate that combining commit messages with code diffs significantly enhances model performance, with the combined few-shot and chain-of-thought prompting achieving an F1-score of 0.88. Additionally, we explore embedding-based machine learning models trained on LLM-generated embeddings, where a multi-layer perceptron classifier achieves superior performance (F1-score: 0.906, MCC: 0.807). These findings are encouraging for the research community, as method-level bug prediction remains an open research problem, largely due to the lack of noise-free bug datasets. This research not only contributes a novel method-level perspective to the untangling problem but also highlights practical avenues for enhancing automated software quality assessment tools.

[Arxiv](https://arxiv.org/abs/2505.08263)