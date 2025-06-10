# 基于语义保留数据增强和置信度加权微调的方面级情感分类

发布时间：2025年06月08日

`LLM应用

理由：这篇论文讨论了如何利用大型语言模型（LLM）进行数据增强，特别是在基于方面的情感分析（ACSA）任务中。它提出了一种通过结构化提示模板生成数据的方法，并引入后处理技术以确保语义一致性。此外，论文还提出了基于置信度加权的微调策略，以提升模型的情感预测能力。这些方法都是针对LLM在实际任务中的应用和优化，因此属于LLM应用类别。` `情感分析`

> Semantic-preserved Augmentation with Confidence-weighted Fine-tuning for Aspect Category Sentiment Analysis

# 摘要

> 大型语言模型（LLM）在解决低资源场景下的数据稀缺问题上表现出色。当前研究主要通过人工设计提示来引导LLM完成数据增强任务。针对基于方面情感分析（ACSA），我们提出了一种保留语义且具备语言多样性的数据增强策略，具体通过为LLM提供结构化提示模板来生成预定义内容。此外，我们引入后处理技术，进一步确保生成句子与原句在语义上的一致性。增强数据扩大了训练分布的语义覆盖范围，帮助模型更深入理解方面类别与情感极性之间的关系，从而提升推理能力。同时，我们提出了基于置信度加权的微调策略，促使模型生成更自信、更准确的情感预测。与现有优秀研究相比，我们的方法在四个基准数据集上均优于所有基线模型，表现最佳。

> Large language model (LLM) is an effective approach to addressing data scarcity in low-resource scenarios. Recent existing research designs hand-crafted prompts to guide LLM for data augmentation. We introduce a data augmentation strategy for the aspect category sentiment analysis (ACSA) task that preserves the original sentence semantics and has linguistic diversity, specifically by providing a structured prompt template for an LLM to generate predefined content. In addition, we employ a post-processing technique to further ensure semantic consistency between the generated sentence and the original sentence. The augmented data increases the semantic coverage of the training distribution, enabling the model better to understand the relationship between aspect categories and sentiment polarities, enhancing its inference capabilities. Furthermore, we propose a confidence-weighted fine-tuning strategy to encourage the model to generate more confident and accurate sentiment polarity predictions. Compared with powerful and recent works, our method consistently achieves the best performance on four benchmark datasets over all baselines.

[Arxiv](https://arxiv.org/abs/2506.07148)