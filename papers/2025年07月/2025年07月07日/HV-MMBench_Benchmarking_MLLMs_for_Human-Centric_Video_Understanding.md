# HV-MMBench：评估多模态大型语言模型在以人为本的视频理解中的基准性能

发布时间：2025年07月07日

`LLM应用

摘要讨论了多模态大型语言模型在视频理解中的应用，并提出了一种新的评估基准，属于LLM的应用层面。` `视频分析` `多模态`

> HV-MMBench: Benchmarking MLLMs for Human-Centric Video Understanding

# 摘要

> 多模态大型语言模型（MLLMs）在图像和视频的视觉理解任务中表现优异，但其在以人类为中心的视频数据理解方面的能力仍有待深入探索。这主要是因为目前缺乏全面且高质量的评估基准。现有以人类为中心的基准测试大多关注视频生成质量和动作识别，却忽视了在人类场景中至关重要的感知和认知能力。此外，这些基准测试往往受限于单一问题范式和过于简化的评估指标。为解决这些问题，我们提出了现代的HV-MMBench，这是一个经过精心设计的基准测试，旨在全面评估MLLMs在以人类为中心的视频理解方面的表现。相比现有以人类为中心的视频基准测试，我们的工作具有以下特点：(1) 多样化的评估维度：HV-MMBench包含15项任务，从基础属性感知（如年龄估计、情绪识别）到高级认知推理（如社交关系预测、意图预测），全面评估模型能力；(2) 多样化的数据类型：采用选择题、填空题、判断题和开放性问题等多种格式，并结合多样化评估指标，准确反映模型性能；(3) 多领域视频覆盖：涵盖50种不同视觉场景，实现细粒度场景变化的全面评估；(4) 时间跨度覆盖：支持从短期（10秒）到长期（30分钟）视频的分析，系统评估模型在不同上下文长度下的时间推理能力。

> Multimodal Large Language Models (MLLMs) have demonstrated significant advances in visual understanding tasks involving both images and videos. However, their capacity to comprehend human-centric video data remains underexplored, primarily due to the absence of comprehensive and high-quality evaluation benchmarks. Existing human-centric benchmarks predominantly emphasize video generation quality and action recognition, while overlooking essential perceptual and cognitive abilities required in human-centered scenarios. Furthermore, they are often limited by single-question paradigms and overly simplistic evaluation metrics. To address above limitations, we propose a modern HV-MMBench, a rigorously curated benchmark designed to provide a more holistic evaluation of MLLMs in human-centric video understanding. Compared to existing human-centric video benchmarks, our work offers the following key features: (1) Diverse evaluation dimensions: HV-MMBench encompasses 15 tasks, ranging from basic attribute perception (e.g., age estimation, emotion recognition) to advanced cognitive reasoning (e.g., social relationship prediction, intention prediction), enabling comprehensive assessment of model capabilities; (2) Varied data types: The benchmark includes multiple-choice, fill-in-blank, true/false, and open-ended question formats, combined with diverse evaluation metrics, to more accurately and robustly reflect model performance; (3) Multi-domain video coverage: The benchmark spans 50 distinct visual scenarios, enabling comprehensive evaluation across fine-grained scene variations; (4) Temporal coverage: The benchmark covers videos from short-term (10 seconds) to long-term (up to 30min) durations, supporting systematic analysis of models temporal reasoning abilities across diverse contextual lengths.

[Arxiv](https://arxiv.org/abs/2507.04909)