# DocVideoQA：通过问答理解以文档为中心的视频，迈向全面认知

发布时间：2025年03月20日

`LLM应用` `视频处理` `多模态`

> DocVideoQA: Towards Comprehensive Understanding of Document-Centric Videos through Question Answering

# 摘要

> 远程工作和在线课程的兴起，使得知识传播方式发生了重要变革，同时也催生了大量基于文档的教学视频。这些视频不同于传统的视频数据集，其特色在于丰富的文本图像和音频内容，信息密度高且与视觉内容紧密相关，这对多模态理解能力提出了更高的要求。然而，由于数据集的获取难度及其固有的复杂性，这一领域尚未得到充分探索。本文首次提出DocVideoQA任务和数据集，包含23类共计1454个视频，总时长约828小时。该数据集通过人工和GPT生成了154,000个问题答案对，旨在评估模型在理解能力、时间感知和模态整合方面的能力。我们首先基于开源的多模态大语言模型（MLLM）建立了基线。鉴于文档为中心的视频在模态理解上的挑战，我们推出了DV-LLaMA，一个强大的视频MLLM基线。我们的方法通过多样化指令微调数据增强了单模态特征提取能力，并借助对比学习提升模态整合效果。通过微调，使大语言模型具备了视听能力，从而显著提升了对文档视频的理解水平。在DocVideoQA数据集上的广泛测试表明，DV-LLaMA相较于现有模型表现更为出色。我们将开源代码和数据集，以推动未来研究的进一步发展。

> Remote work and online courses have become important methods of knowledge dissemination, leading to a large number of document-based instructional videos. Unlike traditional video datasets, these videos mainly feature rich-text images and audio that are densely packed with information closely tied to the visual content, requiring advanced multimodal understanding capabilities. However, this domain remains underexplored due to dataset availability and its inherent complexity. In this paper, we introduce the DocVideoQA task and dataset for the first time, comprising 1454 videos across 23 categories with a total duration of about 828 hours. The dataset is annotated with 154k question-answer pairs generated manually and via GPT, assessing models' comprehension, temporal awareness, and modality integration capabilities. Initially, we establish a baseline using open-source MLLMs. Recognizing the challenges in modality comprehension for document-centric videos, we present DV-LLaMA, a robust video MLLM baseline. Our method enhances unimodal feature extraction with diverse instruction-tuning data and employs contrastive learning to strengthen modality integration. Through fine-tuning, the LLM is equipped with audio-visual capabilities, leading to significant improvements in document-centric video understanding. Extensive testing on the DocVideoQA dataset shows that DV-LLaMA significantly outperforms existing models. We'll release the code and dataset to facilitate future research.

[Arxiv](https://arxiv.org/abs/2503.15887)