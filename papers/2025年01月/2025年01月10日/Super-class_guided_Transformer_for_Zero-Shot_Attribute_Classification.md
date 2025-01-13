# 超类引导的Transformer：零样本属性分类的新方法

发布时间：2025年01月10日

`LLM应用

理由：这篇论文主要讨论了如何利用视觉-语言模型（VLMs）和Transformer模型来解决零样本多标签分类问题，特别是通过引入超类来增强模型的泛化能力和可扩展性。虽然论文中提到了视觉-语言模型，但其核心思想是通过改进模型架构和训练策略来提升模型的性能，这与LLM（大型语言模型）的应用场景密切相关。因此，将其归类为LLM应用是合适的。` `计算机视觉` `图像处理`

> Super-class guided Transformer for Zero-Shot Attribute Classification

# 摘要

> # 摘要
属性分类在识别图像区域中的特定特征方面至关重要。视觉-语言模型（VLMs）通过利用大规模数据集中的通用知识，在零样本任务中表现出色。最近的研究表明，基于Transformer的模型通过类级查询可以有效解决零样本多标签分类问题。然而，由于对已见和未见属性之间关系的利用不足，模型缺乏泛化能力。此外，属性分类通常涉及大量属性，这使得保持模型的可扩展性变得困难。为此，我们提出了Super-class guided transFormer（SugaFormer），这是一个利用超类来增强零样本属性分类的可扩展性和泛化能力的新框架。SugaFormer采用超类查询初始化（SQI）来减少查询数量，利用超类中的共同语义信息，并结合多上下文解码（MD）来处理多样化的视觉线索。为了增强泛化能力，我们引入了两种利用VLMs的知识转移策略。在训练过程中，超类引导的一致性正则化（SCR）通过区域特定的提示将SugaFormer的特征与VLMs对齐，在推理过程中，零样本检索增强（ZRSE）优化了对未见属性的预测。大量实验表明，SugaFormer在零样本和跨数据集转移设置下，在三个广泛使用的属性分类基准上实现了最先进的性能。我们的代码可在https://github.com/mlvlab/SugaFormer获取。

> Attribute classification is crucial for identifying specific characteristics within image regions. Vision-Language Models (VLMs) have been effective in zero-shot tasks by leveraging their general knowledge from large-scale datasets. Recent studies demonstrate that transformer-based models with class-wise queries can effectively address zero-shot multi-label classification. However, poor utilization of the relationship between seen and unseen attributes makes the model lack generalizability. Additionally, attribute classification generally involves many attributes, making maintaining the model's scalability difficult. To address these issues, we propose Super-class guided transFormer (SugaFormer), a novel framework that leverages super-classes to enhance scalability and generalizability for zero-shot attribute classification. SugaFormer employs Super-class Query Initialization (SQI) to reduce the number of queries, utilizing common semantic information from super-classes, and incorporates Multi-context Decoding (MD) to handle diverse visual cues. To strengthen generalizability, we introduce two knowledge transfer strategies that utilize VLMs. During training, Super-class guided Consistency Regularization (SCR) aligns SugaFormer's features with VLMs using region-specific prompts, and during inference, Zero-shot Retrieval-based Score Enhancement (ZRSE) refines predictions for unseen attributes. Extensive experiments demonstrate that SugaFormer achieves state-of-the-art performance across three widely-used attribute classification benchmarks under zero-shot, and cross-dataset transfer settings. Our code is available at https://github.com/mlvlab/SugaFormer.

[Arxiv](https://arxiv.org/abs/2501.05728)