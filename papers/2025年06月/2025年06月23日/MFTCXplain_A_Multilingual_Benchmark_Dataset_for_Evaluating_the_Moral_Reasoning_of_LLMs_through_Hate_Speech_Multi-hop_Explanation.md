# MFTCXplain: 一个多语言基准数据集，用于通过多跳解释仇恨言论来评估大型语言模型（LLMs）的道德推理能力

发布时间：2025年06月23日

`LLM应用` `仇恨言论检测` `社交媒体分析`

> MFTCXplain: A Multilingual Benchmark Dataset for Evaluating the Moral Reasoning of LLMs through Hate Speech Multi-hop Explanation

# 摘要

> 随着大型语言模型（LLMs）被越来越多地应用于社会敏感任务，确保其道德推理能力日益引起关注。然而，现有的评估基准存在两大缺陷：一是缺乏能够证明道德分类的标注，导致透明度和可解释性不足；二是过度关注英语，限制了对跨文化背景下道德推理能力的评估。本文提出了MFTCXplain，这是一个基于道德基础理论（MFT）的多语言基准数据集，通过仇恨言论的多跳解释来评估LLMs的道德推理能力。该数据集包含葡萄牙语、意大利语、波斯语和英语四种语言的3,000条推文，每条推文均标注了二元仇恨言论标签、道德类别和文本跨度级别的理由。实证研究表明，LLMs的输出与人类标注在道德推理任务中存在显著差异。尽管LLMs在仇恨言论检测方面表现出色（F1最高达0.836），但其预测道德情感的能力相对较弱（F1 < 0.35）。此外，理由对齐在代表性不足的语言中仍然有限。这些发现表明，当前LLMs在内化和反映人类道德推理方面的能力仍有待提升。

> Ensuring the moral reasoning capabilities of Large Language Models (LLMs) is a growing concern as these systems are used in socially sensitive tasks. Nevertheless, current evaluation benchmarks present two major shortcomings: a lack of annotations that justify moral classifications, which limits transparency and interpretability; and a predominant focus on English, which constrains the assessment of moral reasoning across diverse cultural settings. In this paper, we introduce MFTCXplain, a multilingual benchmark dataset for evaluating the moral reasoning of LLMs via hate speech multi-hop explanation using Moral Foundation Theory (MFT). The dataset comprises 3,000 tweets across Portuguese, Italian, Persian, and English, annotated with binary hate speech labels, moral categories, and text span-level rationales. Empirical results highlight a misalignment between LLM outputs and human annotations in moral reasoning tasks. While LLMs perform well in hate speech detection (F1 up to 0.836), their ability to predict moral sentiments is notably weak (F1 < 0.35). Furthermore, rationale alignment remains limited mainly in underrepresented languages. These findings show the limited capacity of current LLMs to internalize and reflect human moral reasoning.

[Arxiv](https://arxiv.org/abs/2506.19073)