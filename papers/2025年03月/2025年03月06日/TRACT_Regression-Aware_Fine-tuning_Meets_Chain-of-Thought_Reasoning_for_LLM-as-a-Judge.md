# TRACT：回归感知微调结合链式思维推理，用于LLM作为评估者

发布时间：2025年03月06日

`LLM应用` `教育评估` `教育技术`

> TRACT: Regression-Aware Fine-tuning Meets Chain-of-Thought Reasoning for LLM-as-a-Judge

# 摘要

> LLM-as-a-judge 范式通过大型语言模型（LLMs）实现自动化文本评估，具体而言，LLM 根据评分标准为输入文本赋予数值评分。现有方法使用交叉熵（CE）损失进行微调，但忽视了分数预测的数值特性。近期研究通过回归感知微调缓解了 LLM 微调在数值预测上的不足，然而未引入链式推理（CoT）用于分数预测。本文提出 TRACT（结合 CoT 的两阶段回归感知微调），一种融合 CoT 推理与回归感知训练的方法。TRACT 分为两个阶段：首先微调种子 LLM 生成 CoT，作为第二阶段微调的监督信号。TRACT 的训练目标包含学习 CoT 推理能力的 CE 损失，以及用于分数预测的回归感知损失。在四个 LLM-as-a-judge 数据集和两种 LLM 上的实验表明，TRACT 显著超越现有方法。大量消融实验验证了 TRACT 各组件的重要性。

> The LLM-as-a-judge paradigm uses large language models (LLMs) for automated text evaluation, where a numerical assessment is assigned by an LLM to the input text following scoring rubrics. Existing methods for LLM-as-a-judge use cross-entropy (CE) loss for fine-tuning, which neglects the numeric nature of score prediction. Recent work addresses numerical prediction limitations of LLM fine-tuning through regression-aware fine-tuning, which, however, does not consider chain-of-thought (CoT) reasoning for score prediction. In this paper, we introduce TRACT (Two-stage Regression-Aware fine-tuning with CoT), a method combining CoT reasoning with regression-aware training. TRACT consists of two stages: first, seed LLM is fine-tuned to generate CoTs, which serve as supervision for the second stage fine-tuning. The training objective of TRACT combines the CE loss for learning the CoT reasoning capabilities, and the regression-aware loss for the score prediction. Experiments across four LLM-as-a-judge datasets and two LLMs show that TRACT significantly outperforms existing methods. Extensive ablation studies validate the importance of each component in TRACT.

[Arxiv](https://arxiv.org/abs/2503.04381)