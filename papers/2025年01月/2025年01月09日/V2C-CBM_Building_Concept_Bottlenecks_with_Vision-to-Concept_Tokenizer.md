# V2C-CBM：基于视觉到概念标记器的概念瓶颈构建

发布时间：2025年01月09日

`LLM应用

理由：这篇论文主要讨论了如何利用多模态模型（如CLIP）和大型语言模型（LLM）来构建概念瓶颈模型（CBMs），以提高视觉分类任务的可解释性和准确性。虽然论文涉及了多模态模型的使用，但其核心关注点是如何利用LLM的知识来改进视觉分类任务，因此可以归类为LLM应用。` `计算机视觉` `人工智能`

> V2C-CBM: Building Concept Bottlenecks with Vision-to-Concept Tokenizer

# 摘要

> # 摘要
概念瓶颈模型（CBMs）通过将图像转化为人类可理解的概念并进行线性组合分类，提供了固有的可解释性。然而，视觉识别任务中的概念标注需要大量专家知识和劳动力，限制了CBMs的广泛应用。最近的研究利用大型语言模型的知识构建概念瓶颈，随后使用如CLIP的多模态模型将图像特征映射到概念空间进行分类。尽管如此，语言模型生成的概念可能冗长且包含非视觉属性，影响准确性和可解释性。本研究通过直接从多模态模型构建CBMs来避免这些问题。我们采用常用词作为基础概念词汇，并利用未标记图像构建视觉到概念（V2C）标记器，将图像明确量化为其最相关的视觉概念，从而创建与多模态模型紧密耦合的视觉导向概念瓶颈。我们的V2C-CBM在训练效率和可解释性方面表现出色，并在多个视觉分类基准上匹配或超越了LLM监督的CBMs，验证了该方法的有效性。

> Concept Bottleneck Models (CBMs) offer inherent interpretability by initially translating images into human-comprehensible concepts, followed by a linear combination of these concepts for classification. However, the annotation of concepts for visual recognition tasks requires extensive expert knowledge and labor, constraining the broad adoption of CBMs. Recent approaches have leveraged the knowledge of large language models to construct concept bottlenecks, with multimodal models like CLIP subsequently mapping image features into the concept feature space for classification. Despite this, the concepts produced by language models can be verbose and may introduce non-visual attributes, which hurts accuracy and interpretability. In this study, we investigate to avoid these issues by constructing CBMs directly from multimodal models. To this end, we adopt common words as base concept vocabulary and leverage auxiliary unlabeled images to construct a Vision-to-Concept (V2C) tokenizer that can explicitly quantize images into their most relevant visual concepts, thus creating a vision-oriented concept bottleneck tightly coupled with the multimodal model. This leads to our V2C-CBM which is training efficient and interpretable with high accuracy. Our V2C-CBM has matched or outperformed LLM-supervised CBMs on various visual classification benchmarks, validating the efficacy of our approach.

[Arxiv](https://arxiv.org/abs/2501.04975)