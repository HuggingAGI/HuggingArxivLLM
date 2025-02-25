# MQADet: 通过多模态问答实现开放词汇目标检测的即插即用增强范式

发布时间：2025年02月23日

`LLM应用` `计算机视觉`

> MQADet: A Plug-and-Play Paradigm for Enhancing Open-Vocabulary Object Detection via Multimodal Question Answering

# 摘要

> 开放词汇检测（OVD）是一项极具挑战性的任务，旨在从不受限制的类别集合中检测和分类物体，包括那些在训练期间未见的类别。现有检测器因复杂视觉-文本对齐问题和长尾类别不平衡而受限，在挑战性场景下表现欠佳。为解决这些问题，我们提出	extbf{MQADet}，一种通用范式，通过多模态大语言模型（MLLMs）的跨模态推理能力，增强现有开放词汇检测器。MQADet作为即插即用的解决方案，无缝集成到预训练检测器中，无需额外训练成本。我们设计了一个三阶段多模态问答（MQA）管道，引导MLLMs精确定位复杂文本和视觉目标，同时增强检测器对相关物体的关注。为验证方法，我们在四个挑战性数据集上构建新基准，采用三种先进检测器作为基线。实验显示，MQADet显著提升检测器性能，尤其在未见复杂类别上，在多样挑战场景中表现突出。为促进研究，我们将公开代码。

> Open-vocabulary detection (OVD) is a challenging task to detect and classify objects from an unrestricted set of categories, including those unseen during training. Existing open-vocabulary detectors are limited by complex visual-textual misalignment and long-tailed category imbalances, leading to suboptimal performance in challenging scenarios. To address these limitations, we introduce \textbf{MQADet}, a universal paradigm for enhancing existing open-vocabulary detectors by leveraging the cross-modal reasoning capabilities of multimodal large language models (MLLMs). MQADet functions as a plug-and-play solution that integrates seamlessly with pre-trained object detectors without substantial additional training costs. Specifically, we design a novel three-stage Multimodal Question Answering (MQA) pipeline to guide the MLLMs to precisely localize complex textual and visual targets while effectively enhancing the focus of existing object detectors on relevant objects. To validate our approach, we present a new benchmark for evaluating our paradigm on four challenging open-vocabulary datasets, employing three state-of-the-art object detectors as baselines. Experimental results demonstrate that our proposed paradigm significantly improves the performance of existing detectors, particularly in unseen complex categories, across diverse and challenging scenarios. To facilitate future research, we will publicly release our code.

[Arxiv](https://arxiv.org/abs/2502.16486)