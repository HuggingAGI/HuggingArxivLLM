# 视觉-语言模型无法理解否定

发布时间：2025年01月16日

`LLM应用

理由：这篇论文主要探讨了视觉-语言模型（VLMs）在理解否定方面的表现，并提出了一个新的基准（NegBench）来评估这些模型的能力。虽然论文中提到了CLIP模型的微调，但整体研究重点在于如何通过数据驱动的方法提升模型在特定任务（如否定理解）上的表现。这属于LLM在实际应用中的改进和优化，因此归类为LLM应用。` `视觉-语言模型`

> Vision-Language Models Do Not Understand Negation

# 摘要

> 许多视觉-语言应用需要模型理解否定，例如用自然语言检索包含某些对象但不包含其他对象的图像。尽管视觉-语言模型（VLMs）通过大规模训练取得了进展，但其理解否定的能力仍未被充分探索。本研究探讨了当前VLMs在理解否定方面的表现。我们提出了NegBench，一个涵盖18种任务变体和79k个示例的新基准，用于评估图像、视频和医学数据集中的否定理解能力。该基准包含两个核心任务：带有否定的检索和带有否定字幕的多项选择题。评估结果显示，现代VLMs在否定理解上表现不佳，通常处于随机水平。为解决这一问题，我们采用了一种以数据为中心的方法，在包含数百万个否定字幕的大规模合成数据集上微调CLIP模型。实验表明，该方法可将否定查询的召回率提高10%，并将带有否定字幕的多项选择题的准确率提升40%。

> Many practical vision-language applications require models that understand negation, e.g., when using natural language to retrieve images which contain certain objects but not others. Despite advancements in vision-language models (VLMs) through large-scale training, their ability to comprehend negation remains underexplored. This study addresses the question: how well do current VLMs understand negation? We introduce NegBench, a new benchmark designed to evaluate negation understanding across 18 task variations and 79k examples spanning image, video, and medical datasets. The benchmark consists of two core tasks designed to evaluate negation understanding in diverse multimodal settings: Retrieval with Negation and Multiple Choice Questions with Negated Captions. Our evaluation reveals that modern VLMs struggle significantly with negation, often performing at chance level. To address these shortcomings, we explore a data-centric approach wherein we finetune CLIP models on large-scale synthetic datasets containing millions of negated captions. We show that this approach can result in a 10% increase in recall on negated queries and a 40% boost in accuracy on multiple-choice questions with negated captions.

[Arxiv](https://arxiv.org/abs/2501.09425)