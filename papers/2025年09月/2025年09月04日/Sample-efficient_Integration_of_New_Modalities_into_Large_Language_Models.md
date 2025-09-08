# 样本高效：新模态融入大型语言模型

发布时间：2025年09月04日

`LLM应用` `基础理论`

> Sample-efficient Integration of New Modalities into Large Language Models

# 摘要

> 多模态基础模型可处理多种模态。但可能的模态空间不仅庞大，还在不断演化，因此从头训练一个覆盖所有模态的模型并不现实。此外，当前要将模态集成到现有基础模型中，往往需要大量配对数据，而低资源模态恰恰缺乏这类数据。本文提出了一种样本高效的模态集成方法（SEMI），可将其应用于大型语言模型（LLMs）。为此，我们设计了一个超网络，它能将置于特定模态编码器与LLM之间的共享投影器适配到任意模态。该超网络在高资源模态（如文本、语音、音频、视频）上完成训练，推理时仅需任意模态的少量样本作为条件，即可生成适配的适配器。为提升训练模态的多样性，我们通过等距变换对编码器数量进行了人工扩充。实验表明，在少样本集成新模态（如卫星图像、天文图像、惯性测量数据和分子数据）时，无论编码器的嵌入维度如何，SEMI都能显著提升样本效率。例如，要达到32样本SEMI的同等准确率，从头训练投影器需64倍数据量。因此，SEMI有望进一步扩展基础模型的模态覆盖能力。

> Multimodal foundation models can process several modalities. However, since the space of possible modalities is large and evolving over time, training a model from scratch to encompass all modalities is unfeasible. Moreover, integrating a modality into a pre-existing foundation model currently requires a significant amount of paired data, which is often not available for low-resource modalities. In this paper, we introduce a method for sample-efficient modality integration (SEMI) into Large Language Models (LLMs). To this end, we devise a hypernetwork that can adapt a shared projector -- placed between modality-specific encoders and an LLM -- to any modality. The hypernetwork, trained on high-resource modalities (i.e., text, speech, audio, video), is conditioned on a few samples from any arbitrary modality at inference time to generate a suitable adapter. To increase the diversity of training modalities, we artificially multiply the number of encoders through isometric transformations. We find that SEMI achieves a significant boost in sample efficiency during few-shot integration of new modalities (i.e., satellite images, astronomical images, inertial measurements, and molecules) with encoders of arbitrary embedding dimensionality. For instance, to reach the same accuracy as 32-shot SEMI, training the projector from scratch needs 64$\times$ more data. As a result, SEMI holds promise to extend the modality coverage of foundation models.

[Arxiv](https://arxiv.org/abs/2509.04606)