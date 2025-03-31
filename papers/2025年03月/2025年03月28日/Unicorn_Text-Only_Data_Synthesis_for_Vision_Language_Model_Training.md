# Unicorn：专为视觉语言模型训练打造的纯文本数据合成方案

发布时间：2025年03月28日

`LLM应用

理由：这篇论文探讨了如何利用大型语言模型（LLMs）生成高质量的图像-文本对，用于训练视觉语言模型（VLMs）。通过提出一种三阶段的数据合成框架，论文展示了LLMs在生成多模态数据中的应用，属于LLM的应用层面。` `数据生成` `多模态`

> Unicorn: Text-Only Data Synthesis for Vision Language Model Training

# 摘要

> 训练视觉语言模型（VLMs）通常需要大规模、高质量的图像-文本对，但获取或合成这类数据成本高昂。相比之下，文本数据丰富且易于获取，这引出了一个问题：是否可以仅通过文本生成高质量的多模态训练数据？为了解决这一问题，我们提出了一种跨模态三阶段数据合成框架，该框架生成了两个数据集：Unicorn-1.2M 和 Unicorn-471K-Instruction。

在第一阶段：多样化文本描述生成，我们利用大型语言模型（LLMs）扩展稀疏的描述种子，构建了120万条语义多样化的高质量描述。在第二阶段：指令微调数据生成，我们进一步将47.1万条描述处理为多轮指令微调任务，以支持复杂推理。最后，在第三阶段：模态表示转换，这些文本描述的表示被转换为视觉表示，生成多样化的合成图像表示。

这一三阶段流程使我们能够构建用于预训练的Unicorn-1.2M和用于指令微调的Unicorn-471K-Instruction，无需依赖真实图像。通过消除对真实图像的依赖，同时保持数据质量和多样性，我们的框架为VLMs训练提供了一种经济高效且可扩展的解决方案。代码可在https://github.com/Yu-xm/Unicorn.git获取。

> Training vision-language models (VLMs) typically requires large-scale, high-quality image-text pairs, but collecting or synthesizing such data is costly. In contrast, text data is abundant and inexpensive, prompting the question: can high-quality multimodal training data be synthesized purely from text? To tackle this, we propose a cross-integrated three-stage multimodal data synthesis framework, which generates two datasets: Unicorn-1.2M and Unicorn-471K-Instruction. In Stage 1: Diverse Caption Data Synthesis, we construct 1.2M semantically diverse high-quality captions by expanding sparse caption seeds using large language models (LLMs). In Stage 2: Instruction-Tuning Data Generation, we further process 471K captions into multi-turn instruction-tuning tasks to support complex reasoning. Finally, in Stage 3: Modality Representation Transfer, these textual captions representations are transformed into visual representations, resulting in diverse synthetic image representations. This three-stage process enables us to construct Unicorn-1.2M for pretraining and Unicorn-471K-Instruction for instruction-tuning, without relying on real images. By eliminating the dependency on real images while maintaining data quality and diversity, our framework offers a cost-effective and scalable solution for VLMs training. Code is available at https://github.com/Yu-xm/Unicorn.git.

[Arxiv](https://arxiv.org/abs/2503.22655)