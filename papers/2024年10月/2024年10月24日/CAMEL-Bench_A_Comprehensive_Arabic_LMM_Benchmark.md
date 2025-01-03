# CAMEL-Bench: 全面的阿拉伯语 LMM 基准

发布时间：2024年10月24日

`LLM应用

**理由**：这篇论文主要讨论了开发一个用于评估大型多模态模型（LMMs）在阿拉伯语任务中表现的基准——CAMEL-Bench。虽然涉及多模态模型，但其核心是评估这些模型在特定语言任务中的应用表现，因此属于LLM应用的范畴。` `多模态模型` `阿拉伯语`

> CAMEL-Bench: A Comprehensive Arabic LMM Benchmark

# 摘要

> # 摘要
近年来，开发能够执行多种视觉推理和理解任务的大型多模态模型（LMMs）引发了广泛关注。为此，多个LMM基准应运而生，用于评估LMMs在不同任务中的表现。然而，现有LMM评估基准大多以英语为主。为此，我们开发了一个全面的阿拉伯语LMM评估基准——CAMEL-Bench，旨在覆盖超过4亿使用者的庞大群体。CAMEL-Bench涵盖八个领域和38个子领域，包括多图像理解、复杂视觉感知、手写文档理解、视频理解、医学成像、植物疾病和基于遥感的地利用理解，以全面评估模型的场景泛化能力。该基准包含约29,036个问题，这些问题从大量样本中筛选而出，并由母语者手动验证质量，确保评估的可靠性。我们对闭源模型（如GPT-4系列）和开源LMMs进行了评估。分析表明，开源模型尤其需要大幅改进，即使是闭源的GPT-4o也仅获得62%的总体得分。我们的基准和评估脚本已开源。

> Recent years have witnessed a significant interest in developing large multimodal models (LMMs) capable of performing various visual reasoning and understanding tasks. This has led to the introduction of multiple LMM benchmarks to evaluate LMMs on different tasks. However, most existing LMM evaluation benchmarks are predominantly English-centric. In this work, we develop a comprehensive LMM evaluation benchmark for the Arabic language to represent a large population of over 400 million speakers. The proposed benchmark, named CAMEL-Bench, comprises eight diverse domains and 38 sub-domains including, multi-image understanding, complex visual perception, handwritten document understanding, video understanding, medical imaging, plant diseases, and remote sensing-based land use understanding to evaluate broad scenario generalizability. Our CAMEL-Bench comprises around 29,036 questions that are filtered from a larger pool of samples, where the quality is manually verified by native speakers to ensure reliable model assessment. We conduct evaluations of both closed-source, including GPT-4 series, and open-source LMMs. Our analysis reveals the need for substantial improvement, especially among the best open-source models, with even the closed-source GPT-4o achieving an overall score of 62%. Our benchmark and evaluation scripts are open-sourced.

[Arxiv](https://arxiv.org/abs/2410.18976)