# 先排序再评分：提升大型语言模型在自动作文评分中的表现

发布时间：2025年04月08日

`LLM应用` `评分系统`

> Rank-Then-Score: Enhancing Large Language Models for Automated Essay Scoring

# 摘要

> 近年来，大型语言模型（LLMs）在各类任务中取得了显著的成功。然而，大型语言模型在自动评分系统（AES）领域的潜力仍未得到充分挖掘。此外，与英文数据相比，中文自动评分的方法尚未得到充分发展。本文中，我们提出了Rank-Then-Score（RTS），这是一种基于大型语言模型的微调框架，旨在提升其在作文评分方面的性能。具体而言，我们使用特征增强数据对排名模型（Ranker）进行微调，然后将排名模型的输出（以候选分数集的形式）与作文内容一起输入评分模型（Scorer），以生成最终分数。在HSK和ASAP两个基准数据集上的实验结果表明，与直接提示（Vanilla）方法相比，RTS在所有大型语言模型和数据集上的平均QWK表现更优，并且在使用HSK数据集进行中文作文评分时取得了最佳性能。

> In recent years, large language models (LLMs) achieve remarkable success across a variety of tasks. However, their potential in the domain of Automated Essay Scoring (AES) remains largely underexplored. Moreover, compared to English data, the methods for Chinese AES is not well developed. In this paper, we propose Rank-Then-Score (RTS), a fine-tuning framework based on large language models to enhance their essay scoring capabilities. Specifically, we fine-tune the ranking model (Ranker) with feature-enriched data, and then feed the output of the ranking model, in the form of a candidate score set, with the essay content into the scoring model (Scorer) to produce the final score. Experimental results on two benchmark datasets, HSK and ASAP, demonstrate that RTS consistently outperforms the direct prompting (Vanilla) method in terms of average QWK across all LLMs and datasets, and achieves the best performance on Chinese essay scoring using the HSK dataset.

[Arxiv](https://arxiv.org/abs/2504.05736)