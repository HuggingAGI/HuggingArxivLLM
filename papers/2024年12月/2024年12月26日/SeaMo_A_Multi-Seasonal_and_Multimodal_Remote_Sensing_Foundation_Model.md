# SeaMo: 多季节多模态遥感基础模型

发布时间：2024年12月26日

`其他

理由：这篇论文主要讨论的是遥感（RS）数据和多维信息的整合，以及如何通过视觉基础模型（VFMs）来处理这些数据。虽然提到了“大型视觉基础模型”（VFMs），但并没有直接涉及大型语言模型（LLM）、检索增强生成（RAG）或智能体（Agent）等概念。因此，这篇论文更适合归类为“其他”，因为它主要关注的是遥感数据和视觉模型的应用，而不是LLM或相关技术。` `地球科学`

> SeaMo: A Multi-Seasonal and Multimodal Remote Sensing Foundation Model

# 摘要

> # 摘要
遥感（RS）数据蕴含了丰富的地球观测多维信息。其海量、多样且具时间属性的特点，使其成为开发大型视觉基础模型（VFMs）的理想选择。VFMs作为强大的特征提取器，通过大量RS数据学习，并微调后应用于各类地球科学任务。然而，当前RS领域的VFMs主要针对特定图像特征进行预训练和定制，未能充分利用RS数据的多维属性。为此，我们提出了SeaMo，一个开创性的视觉基础模型，整合了RS领域的多季节和多模态信息。SeaMo旨在挖掘RS数据的多维潜力，通过非对齐裁剪技术提取空间属性，多源输入实现多模态整合，并引入时间-多模态融合块有效吸收多季节数据。SeaMo明确建模了RS数据的多维属性，使模型更加全面、稳健且多功能。在多个地球科学任务中，SeaMo展现了卓越性能，并通过广泛的消融研究验证了其优越性。

> Remote Sensing (RS) data contains a wealth of multi-dimensional information crucial for Earth observation. Owing to its vast volume, diverse sources, and temporal properties, RS data is highly suitable for the development of large Visual Foundation Models (VFMs). VFMs act as robust feature extractors, learning from extensive RS data, and are subsequently fine-tuned for deployment in various geoscientific tasks. However, current VFMs in the RS domain are predominantly pretrained and tailored exclusively for specific characteristics of RS imagery, neglecting the potential of utilizing the multi-dimensional properties of RS data. Therefore, in this work, we propose SeaMo, a pioneering visual foundation model that integrates multi-seasonal and multimodal information in the RS field. SeaMo is designed to harness multiple properties of RS data. Within the masked image modeling framework, we employ non-aligned cropping techniques to extract spatial properties, use multi-source inputs for multimodal integration, and incorporate temporal-multimodal fusion blocks for effective assimilation of multi-seasonal data. SeaMo explicitly models the multi-dimensional properties of RS data, making the model more comprehensive, robust, and versatile. We applied SeaMo to several downstream geoscience tasks, which demonstrated exceptional performance. Extensive ablation studies were conducted to validate the model's superiority.

[Arxiv](https://arxiv.org/abs/2412.19237)