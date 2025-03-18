# GeoRSMLLM：面向地球科学与遥感领域视觉-语言任务的多模态大型语言模型

发布时间：2025年03月16日

`LLM应用`

> GeoRSMLLM: A Multimodal Large Language Model for Vision-Language Tasks in Geoscience and Remote Sensing

# 摘要

> 视觉语言模型（VLMs）在遥感（RS）中的应用在场景分类、目标检测和图像 captioning 等传统任务中表现突出。然而，尽管当前模型在 Referring Expression Comprehension（REC）方面表现出色，但面对涉及复杂指令（如存在多个条件）或像素级操作（如分割和变化检测）的任务时仍显不足。在这篇白皮书中，我们对遥感中的视觉语言任务进行了全面的分层总结，根据不同认知能力需求进行了分类。我们引入了遥感视觉语言任务集（RSVLTS），其中包括开放词汇任务（OVT）、引用表达任务（RET）、难度递增的描述对象任务（DOT），以及视觉问答（VQA）。此外，我们提出了一种基于点集方法的新型统一数据表示，结合了条件解析器和基于循环引用的自我增强策略。这些功能集成到 GeoRSMLLM 模型中，使其能够处理 RSVLTS 的广泛任务，为地学和遥感中的视觉语言任务提供了更通用的解决方案。

> The application of Vision-Language Models (VLMs) in remote sensing (RS) has demonstrated significant potential in traditional tasks such as scene classification, object detection, and image captioning. However, current models, which excel in Referring Expression Comprehension (REC), struggle with tasks involving complex instructions (e.g., exists multiple conditions) or pixel-level operations like segmentation and change detection. In this white paper, we provide a comprehensive hierarchical summary of vision-language tasks in RS, categorized by the varying levels of cognitive capability required. We introduce the Remote Sensing Vision-Language Task Set (RSVLTS), which includes Open-Vocabulary Tasks (OVT), Referring Expression Tasks (RET), and Described Object Tasks (DOT) with increased difficulty, and Visual Question Answering (VQA) aloneside. Moreover, we propose a novel unified data representation using a set-of-points approach for RSVLTS, along with a condition parser and a self-augmentation strategy based on cyclic referring. These features are integrated into the GeoRSMLLM model, and this enhanced model is designed to handle a broad range of tasks of RSVLTS, paving the way for a more generalized solution for vision-language tasks in geoscience and remote sensing.

[Arxiv](https://arxiv.org/abs/2503.12490)