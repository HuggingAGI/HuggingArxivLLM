# Multi-TW：针对台湾地区传统中文问答的多模态模型评估基准

发布时间：2025年08月02日

`LLM应用

这篇论文主要探讨了多模态大型语言模型在传统中文环境下的性能评估，特别是针对跨模态任务和推理延迟的分析。它属于对LLM的应用和评估，因此归类为LLM应用。` `人工智能`

> Multi-TW: Benchmarking Multimodal Models on Traditional Chinese Question Answering in Taiwan

# 摘要

> 多模态大型语言模型（MLLMs）通过整合视觉、听觉与文本输入，克服了单一模态LLMs的局限。然而，现有基准测试往往忽视了对传统中文的三模态评估，且未充分考虑推理延迟问题。为此，我们推出了Multi-TW——首个专注于评估任何对任何多模态模型性能与延迟的传统中文基准。该基准包含900道选择题（涵盖图像与文本、音频与文本配对），这些题目源自华语水平测试学术指导委员会（SC-TOP）开发的官方 proficiency tests。我们对多种任何对任何模型以及具备音频转录功能的视觉语言模型（VLMs）进行了评估。结果显示，闭源模型在跨模态任务中普遍优于开源模型，尽管开源模型在音频任务中仍能表现出色。此外，端到端的任何对任何管道相较于采用独立音频转录的VLMs，展现出显著的延迟优势。Multi-TW不仅全面呈现了模型能力，还凸显了对传统中文微调及高效多模态架构的迫切需求。

> Multimodal Large Language Models (MLLMs) process visual, acoustic, and textual inputs, addressing the limitations of single-modality LLMs. However, existing benchmarks often overlook tri-modal evaluation in Traditional Chinese and do not consider inference latency. To address this, we introduce Multi-TW, the first Traditional Chinese benchmark for evaluating the performance and latency of any-to-any multimodal models. Multi-TW includes 900 multiple-choice questions (image and text, audio and text pairs) sourced from official proficiency tests developed with the Steering Committee for the Test of Proficiency-Huayu (SC-TOP). We evaluated various any-to-any models and vision-language models (VLMs) with audio transcription. Our results show that closed-source models generally outperform open-source ones across modalities, although open-source models can perform well in audio tasks. End-to-end any-to-any pipelines offer clear latency advantages compared to VLMs using separate audio transcription. Multi-TW presents a comprehensive view of model capabilities and highlights the need for Traditional Chinese fine-tuning and efficient multimodal architectures.

[Arxiv](https://arxiv.org/abs/2508.01274)