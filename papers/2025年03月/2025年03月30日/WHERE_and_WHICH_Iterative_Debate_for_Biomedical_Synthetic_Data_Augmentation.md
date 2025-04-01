# WHERE和WHICH：迭代式讨论应用于生物医学合成数据增强

发布时间：2025年03月30日

`LLM应用

理由：这篇论文讨论了在生物医学自然语言处理任务中，如何通过改进的数据增强方法来提升大型语言模型的性能。它专注于模型的应用和实际效果，而非模型的理论或架构，因此归类为LLM应用。` `生物医学`

> WHERE and WHICH: Iterative Debate for Biomedical Synthetic Data Augmentation

# 摘要

> 在生物医学自然语言处理（BioNLP）任务中，如关系抽取、命名实体识别和文本分类，高质量数据的匮乏仍是重大挑战。这一问题限制了大型语言模型正确理解生物实体间关系的能力，如分子与疾病关联或药物相互作用，可能导致对生物医学文档的误读。现有方法通常采用合成数据增强技术，通过相似性计算后进行词语替换，但常生成反事实数据，破坏有意义的词语集合或生成与原始上下文大相径庭的句子，无法有效提升模型性能。为此，本文提出一种基于生物医学专用推理的合成数据增强方法。除了简单的词汇相似性外，我们还测量了特定的生物关系相似性，确保增强实例与生物关系强相关，而非仅增加数据多样性。此外，多智能体参与的反思机制帮助模型逐步区分相似实体的不同用法，避免误替换。我们在BLURB和BigBIO基准上评估了该方法，涵盖四个主要BioNLP任务的9个数据集。实验结果表明，我们的方法在所有任务中均表现出一致的性能提升，突显了其在解决数据稀缺挑战和提升生物医学NLP模型性能方面的有效性。

> In Biomedical Natural Language Processing (BioNLP) tasks, such as Relation Extraction, Named Entity Recognition, and Text Classification, the scarcity of high-quality data remains a significant challenge. This limitation poisons large language models to correctly understand relationships between biological entities, such as molecules and diseases, or drug interactions, and further results in potential misinterpretation of biomedical documents. To address this issue, current approaches generally adopt the Synthetic Data Augmentation method which involves similarity computation followed by word replacement, but counterfactual data are usually generated. As a result, these methods disrupt meaningful word sets or produce sentences with meanings that deviate substantially from the original context, rendering them ineffective in improving model performance. To this end, this paper proposes a biomedical-dedicated rationale-based synthetic data augmentation method. Beyond the naive lexicon similarity, specific bio-relation similarity is measured to hold the augmented instance having a strong correlation with bio-relation instead of simply increasing the diversity of augmented data. Moreover, a multi-agents-involved reflection mechanism helps the model iteratively distinguish different usage of similar entities to escape falling into the mis-replace trap. We evaluate our method on the BLURB and BigBIO benchmark, which includes 9 common datasets spanning four major BioNLP tasks. Our experimental results demonstrate consistent performance improvements across all tasks, highlighting the effectiveness of our approach in addressing the challenges associated with data scarcity and enhancing the overall performance of biomedical NLP models.

[Arxiv](https://arxiv.org/abs/2503.23673)