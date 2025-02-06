# COCONut-PanCap: 联合全景分割与基于地面的描述，助力细粒度理解与生成

发布时间：2025年02月04日

`其他

理由：这篇论文主要介绍了一个新的数据集COCONut-PanCap，旨在提升全景分割和基于图像的描述生成能力。虽然涉及视觉-语言模型（VLMs）和生成模型，但主要内容集中在数据集的构建和应用，而不是直接讨论Agent、RAG、LLM应用或LLM理论。因此，将其分类为“其他”更为合适。` `计算机视觉`

> COCONut-PanCap: Joint Panoptic Segmentation and Grounded Captions for Fine-Grained Understanding and Generation

# 摘要

> 本文介绍了COCONut-PanCap数据集，旨在提升全景分割和基于图像的描述生成能力。该数据集基于COCO数据集，结合了先进的COCONut全景掩码，解决了现有图像-文本数据集中缺乏详细、全面场景描述的不足。COCONut-PanCap通过细粒度、区域级的描述，确保了一致性并提升了生成描述的细节。通过人工编辑的密集注释，COCONut-PanCap优化了视觉-语言模型（VLMs）在图像理解中的训练，以及文本到图像任务的生成模型。实验表明，COCONut-PanCap在理解和生成任务中显著提升了性能，为大规模数据集提供了互补优势。该数据集为联合全景分割和基于描述的生成任务设定了新的评估基准，满足了多模态学习中对高质量、详细图像-文本注释的需求。

> This paper introduces the COCONut-PanCap dataset, created to enhance panoptic segmentation and grounded image captioning. Building upon the COCO dataset with advanced COCONut panoptic masks, this dataset aims to overcome limitations in existing image-text datasets that often lack detailed, scene-comprehensive descriptions. The COCONut-PanCap dataset incorporates fine-grained, region-level captions grounded in panoptic segmentation masks, ensuring consistency and improving the detail of generated captions. Through human-edited, densely annotated descriptions, COCONut-PanCap supports improved training of vision-language models (VLMs) for image understanding and generative models for text-to-image tasks. Experimental results demonstrate that COCONut-PanCap significantly boosts performance across understanding and generation tasks, offering complementary benefits to large-scale datasets. This dataset sets a new benchmark for evaluating models on joint panoptic segmentation and grounded captioning tasks, addressing the need for high-quality, detailed image-text annotations in multi-modal learning.

[Arxiv](https://arxiv.org/abs/2502.02589)