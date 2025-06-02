# MMAFFBen：一个多语言和多模态情感分析基准，用于评估大语言模型和视觉语言模型

发布时间：2025年05月30日

`LLM应用` `情感分析` `多模态`

> MMAFFBen: A Multilingual and Multimodal Affective Analysis Benchmark for Evaluating LLMs and VLMs

# 摘要

> 大型语言模型和视觉语言模型（统称为LMs）彻底革新了自然语言处理和计算机视觉领域，展现出跨领域应用的巨大潜力。然而，它们在情感分析（包括情感倾向分析和情绪识别）方面的能力仍有待深入探索。这一差距主要源于缺乏全面的评估基准，以及情感分析任务本身的复杂性。本文推出首个全面开源的多语言多模态情感分析基准测试——MMAFFBen。该基准涵盖文本、图像和视频三种模态，支持35种语言，全面覆盖情感极性、情感强度、情绪分类和情绪强度四大情感分析任务。此外，我们构建了MMAFFIn数据集用于微调LMs进行情感分析，并在此基础上开发了MMAFFLM-3b和MMAFFLM-7b模型。通过评估包括GPT-4o-mini在内的多种代表性LMs，我们系统性地比较了它们的情感理解能力。本项目已在GitHub上开源：https://github.com/lzw108/MMAFFBen。

> Large language models and vision-language models (which we jointly call LMs) have transformed NLP and CV, demonstrating remarkable potential across various fields. However, their capabilities in affective analysis (i.e. sentiment analysis and emotion detection) remain underexplored. This gap is largely due to the absence of comprehensive evaluation benchmarks, and the inherent complexity of affective analysis tasks. In this paper, we introduce MMAFFBen, the first extensive open-source benchmark for multilingual multimodal affective analysis. MMAFFBen encompasses text, image, and video modalities across 35 languages, covering four key affective analysis tasks: sentiment polarity, sentiment intensity, emotion classification, and emotion intensity. Moreover, we construct the MMAFFIn dataset for fine-tuning LMs on affective analysis tasks, and further develop MMAFFLM-3b and MMAFFLM-7b based on it. We evaluate various representative LMs, including GPT-4o-mini, providing a systematic comparison of their affective understanding capabilities. This project is available at https://github.com/lzw108/MMAFFBen.

[Arxiv](https://arxiv.org/abs/2505.24423)