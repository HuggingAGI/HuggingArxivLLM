# jina-clip-v2：针对文本和图像的多语言多模态嵌入

发布时间：2024年12月11日

`LLM应用` `信息检索` `多模态`

> jina-clip-v2: Multilingual Multimodal Embeddings for Text and Images

# 摘要

> 对比语言 - 图像预训练（CLIP）是在共享嵌入空间中让图像和文本对齐的高效之法。此类模型广泛用于跨模态信息检索和多模态理解等任务。然而，CLIP 模型在纯文本任务上常遇难题，表现逊于专门的文本模型。这一性能差距使得检索系统得依靠单独的模型来处理纯文本和多模态任务。在本项工作中，我们以先前的模型 jina - clip - v1 为基础，引入了一个优化的框架，它利用多种语言的多任务、多阶段对比学习，再结合改进的训练方案来强化纯文本检索。最终的模型 jina - clip - v2 在纯文本和多模态任务上都超越了前者，还增添了多语言支持，借助 Matryoshka 表示学习和向量截断，对复杂的视觉文档理解更佳，效率也有所提升。该模型在多语言 - 多模态和多语言文本检索基准测试中的表现与前沿水平相当，化解了统一纯文本和多模态检索系统的难题。

> Contrastive Language-Image Pretraining (CLIP) is a highly effective method for aligning images and texts in a shared embedding space. These models are widely used for tasks such as cross-modal information retrieval and multi-modal understanding. However, CLIP models often struggle with text-only tasks, underperforming compared to specialized text models. This performance disparity forces retrieval systems to rely on separate models for text-only and multi-modal tasks. In this work, we build upon our previous model, jina-clip-v1, by introducing a refined framework that utilizes multi-task, multi-stage contrastive learning across multiple languages, coupled with an improved training recipe to enhance text-only retrieval. The resulting model, jina-clip-v2, outperforms its predecessor on text-only and multimodal tasks, while adding multilingual support, better understanding of complex visual documents and efficiency gains thanks to Matryoshka Representation Learning and vector truncation. The model performs comparably to the state-of-the-art in both multilingual-multimodal and multilingual text retrieval benchmarks, addressing the challenge of unifying text-only and multi-modal retrieval systems.

[Arxiv](https://arxiv.org/abs/2412.08802)