# 大型语言模型可能只是死记硬背的高手。

发布时间：2025年04月11日

`LLM应用` `模型评估` `知识评估`

> Large language models could be rote learners

# 摘要

> 多选题（MCQ）基准测试是评估大型语言模型（LLMs）的常用方法，但基准污染问题严重削弱了其可靠性。本研究将污染重新定义为学习过程中的固有组成部分，并致力于在LLMs评估中区分真实能力获取与浅层记忆。通过分析模型在不同记忆条件下的表现，我们发现了一个反直觉的趋势：LLMs在记忆过的MCQ上表现不如未记忆过的，这表明死记硬背和真实能力学习这两种不同的学习现象并存。为区分这两种现象，我们提出了TrinEval，这是一种全新的评估框架，将MCQ重新表述为三元组格式，从而减少记忆同时保持知识评估。实验验证了TrinEval在重新表述方面的有效性，其评估结果表明，常见LLMs可能通过死记硬背记忆了20.5%的知识点（平均基于MMLU）。

> Multiple-choice question (MCQ) benchmarks are widely used for evaluating Large Language Models (LLMs), yet their reliability is undermined by benchmark contamination. In this study, we reframe contamination as an inherent aspect of learning and seek to disentangle genuine capability acquisition from superficial memorization in LLM evaluation. First, by analyzing model performance under different memorization conditions, we uncover a counterintuitive trend: LLMs perform worse on memorized MCQs than on non-memorized ones, indicating the coexistence of two distinct learning phenomena, i.e., rote memorization and genuine capability learning. To disentangle them, we propose TrinEval, a novel evaluation framework that reformulates MCQs into an alternative trinity format, reducing memorization while preserving knowledge assessment. Experiments validate TrinEval's effectiveness in reformulation, and its evaluation reveals that common LLMs may memorize by rote 20.5% of knowledge points (in MMLU on average).

[Arxiv](https://arxiv.org/abs/2504.08300)