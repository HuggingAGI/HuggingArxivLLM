# # 眼动数据分词

发布时间：2025年03月28日

`LLM应用

分类解释：这篇论文探讨了如何将大型语言模型（LLM）应用于处理注视数据，并评估了不同分词策略对模型性能的影响，属于LLM应用的研究。` `计算机视觉` `眼球追踪技术`

> Tokenization of Gaze Data

# 摘要

> 当代大型语言模型（LLMs）和多模态大型语言模型（MLLMs）的性能显著依赖于其分词策略。尽管分词器在文本和视觉输入方面得到了广泛研究，但由于其特性，目前尚无针对注视数据（gaze data）的分词策略研究。然而，设计一种相应的分词策略将使我们能够利用预训练MLLM的视觉能力来处理注视数据，例如通过微调的方式。本文旨在通过分析五种不同的注视数据分词器在三个不同数据集上的表现，填补这一研究空白，进而通过LLMs实现注视数据的预测与生成（参见~\cref{fig:teaser}）。我们从分词器的重构和压缩能力两个方面进行评估。此外，我们针对每种分词策略训练了一个LLM，并测量其生成和预测性能。总体而言，我们发现分位数分词器在预测注视位置方面表现最佳，而k-means分词器在预测注视速度方面最为出色。

> A considerable part of the performance of today's large language models (LLM's) and multimodal large language models (MLLM's) depends on their tokenization strategies. While tokenizers are extensively researched for textual and visual input, there is no research on tokenization strategies for gaze data due to its nature. However, a corresponding tokenization strategy would allow using the vision capabilities of pre-trained MLLM's for gaze data, for example, through fine-tuning.
  In this paper, we aim to close this research gap by analyzing five different tokenizers for gaze data on three different datasets for the forecasting and generation of gaze data through LLMs (cf.~\cref{fig:teaser}). We evaluate the tokenizers regarding their reconstruction and compression abilities. Further, we train an LLM for each tokenization strategy, measuring its generative and predictive performance. Overall, we found that a quantile tokenizer outperforms all others in predicting the gaze positions and k-means is best when predicting gaze velocities.

[Arxiv](https://arxiv.org/abs/2503.22145)