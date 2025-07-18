# 平衡训练数据增强在方面情感分析中的应用至关重要。

发布时间：2025年07月13日

`LLM应用` `社交媒体` `情感分析`

> Balanced Training Data Augmentation for Aspect-Based Sentiment Analysis

# 摘要

> # 基于方面的情感分析
基于方面的情感分析（ABSA）是一项在社交媒体场景中至关重要的细粒度任务，用于识别句子中特定方面术语的情感极性。尽管现有的许多研究利用大型语言模型（LLMs）进行ABSA，因为它们在上下文理解方面表现出色，但仍面临挑战。具体来说，由于文本较短以及标注训练数据量小且不平衡（大部分数据为正面情感标注），LLMs难以有效学习运行文本中的上下文信息。数据增强（DA）是一种通过使用LLMs生成合成训练数据来丰富上下文信息的可行策略，但在确保增强数据质量方面仍存在挑战。本文提出了一种结合训练数据增强的基于LLMs的ABSA方法。具体而言，我们通过提示LLM根据原始训练数据生成增强数据，构建一个规模更大、标签分布更均衡的新训练集，从而更好地训练ABSA模型。同时，为提升增强数据的质量，我们提出了一种强化学习方法来优化数据增强过程。实验结果及在英语基准数据集上的进一步分析表明，我们提出的方法表现优异，超越了强大的基线模型和现有研究。


> Aspect-based sentiment analysis (ABSA) is a crucial fine-grained task in social media scenarios to identify the sentiment polarity of specific aspect terms in a sentence. Although many existing studies leverage large language models (LLMs) to perform ABSA due to their strong context understanding capabilities, they still face challenges to learn the context information in the running text because of the short text, as well as the small and unbalanced labeled training data, where most data are labeled with positive sentiment. Data augmentation (DA) is a feasible strategy for providing richer contextual information, especially when using LLMs to create synthetic training data, but faces challenges in ensuring a high quality of the augmented data.In this paper, we propose an LLM-based ABSA approach with training data augmentation.Specifically, an LLM is prompted to generate augmented training data based on the original training data, so as to construct a new training data with larger size and balanced label distributions to better train an ABSA model. Meanwhile, in order to improve the quality of the augmented data, we propose a reinforcement learning approach to optimize the data augmentation. LLM.Experiment results and further analyses on English benchmark datasets for ABSA demonstrate the effectiveness of our approach, where superior performance is observed over strong baselines and most existing studies.

[Arxiv](https://arxiv.org/abs/2507.09485)