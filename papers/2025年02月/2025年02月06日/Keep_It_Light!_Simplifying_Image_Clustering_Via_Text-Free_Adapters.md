# 轻装上阵！用无文本适配器简化图像聚类

发布时间：2025年02月06日

`其他

理由：这篇论文主要讨论的是一种无文本且高度简化的训练方法，通过预训练模型的简单聚类（SCP）来进行视觉聚类。虽然提到了大型语言模型（LLMs），但论文的核心内容并不直接涉及LLM的应用、理论、Agent或RAG（Retrieval-Augmented Generation）。相反，它更侧重于视觉模型的聚类方法和性能提升，因此归类为“其他”更为合适。` `计算机视觉` `机器学习`

> Keep It Light! Simplifying Image Clustering Via Text-Free Adapters

# 摘要

> 许多先进的聚类方法采用多模态设计，依赖大型语言模型（LLMs）或文本编码器，以及文本-图像对，但这些在实际应用中往往难以获取。此外，这些框架通常训练复杂，计算资源消耗大，难以广泛推广。本文提出了一种无文本且高度简化的训练方法——通过预训练模型的简单聚类（SCP），仅需训练一个小的聚类头，同时利用预训练视觉模型的特征和正数据对。在CIFAR-10、CIFAR-20、CIFAR-100、STL-10、ImageNet-10和ImageNet-Dogs等基准数据集上的实验表明，SCP性能优异。我们还从理论上解释了为何在理想条件下，基于文本的嵌入可能并非视觉聚类性能提升的必要条件。

> Many competitive clustering pipelines have a multi-modal design, leveraging large language models (LLMs) or other text encoders, and text-image pairs, which are often unavailable in real-world downstream applications. Additionally, such frameworks are generally complicated to train and require substantial computational resources, making widespread adoption challenging. In this work, we show that in deep clustering, competitive performance with more complex state-of-the-art methods can be achieved using a text-free and highly simplified training pipeline. In particular, our approach, Simple Clustering via Pre-trained models (SCP), trains only a small cluster head while leveraging pre-trained vision model feature representations and positive data pairs. Experiments on benchmark datasets including CIFAR-10, CIFAR-20, CIFAR-100, STL-10, ImageNet-10, and ImageNet-Dogs, demonstrate that SCP achieves highly competitive performance. Furthermore, we provide a theoretical result explaining why, at least under ideal conditions, additional text-based embeddings may not be necessary to achieve strong clustering performance in vision.

[Arxiv](https://arxiv.org/abs/2502.04226)