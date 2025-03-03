# 少样本，没问题：描述性持续关系抽取

发布时间：2025年02月27日

`LLM应用

摘要中的论文探讨了如何利用大型语言模型（LLM）生成关系描述，并通过检索式解决方案来解决小样本持续关系抽取的问题。这属于将LLM应用于特定任务，即关系抽取和持续学习，因此归类为LLM应用。` `信息抽取` `关系抽取`

> Few-Shot, No Problem: Descriptive Continual Relation Extraction

# 摘要

> 小样本持续关系抽取是让AI系统识别并适应动态现实领域中不断演变的关系的重要挑战。传统基于记忆的方法往往过度拟合于有限样本，无法有效强化旧知识，而小样本场景下数据的稀缺性进一步加剧了这一问题，阻碍了潜在空间中的有效数据增强。本文中，我们提出了一种新颖的检索式解决方案，首先利用大型语言模型为每种关系生成描述。从这些描述中，我们引入了一种双编码器检索训练范式，以丰富样本和类别表示学习。借助这些增强的表示，我们设计了一种检索式预测方法，其中每个样本通过融合关系描述向量和类别原型的倒排秩融合分数，“检索”出最合适的关联关系。在多个数据集上的广泛实验表明，我们的方法在保持对连续任务的稳健性能方面显著提升了现有技术水平，有效解决了灾难性遗忘问题。

> Few-shot Continual Relation Extraction is a crucial challenge for enabling AI systems to identify and adapt to evolving relationships in dynamic real-world domains. Traditional memory-based approaches often overfit to limited samples, failing to reinforce old knowledge, with the scarcity of data in few-shot scenarios further exacerbating these issues by hindering effective data augmentation in the latent space. In this paper, we propose a novel retrieval-based solution, starting with a large language model to generate descriptions for each relation. From these descriptions, we introduce a bi-encoder retrieval training paradigm to enrich both sample and class representation learning. Leveraging these enhanced representations, we design a retrieval-based prediction method where each sample "retrieves" the best fitting relation via a reciprocal rank fusion score that integrates both relation description vectors and class prototypes. Extensive experiments on multiple datasets demonstrate that our method significantly advances the state-of-the-art by maintaining robust performance across sequential tasks, effectively addressing catastrophic forgetting.

[Arxiv](https://arxiv.org/abs/2502.20596)