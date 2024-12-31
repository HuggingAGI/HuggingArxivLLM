# 当前的视频 LLMs 是否具备强大的 OCR 能力？这是一项初步研究。

发布时间：2024年12月29日

`LLM应用` `光学字符识别`

> Do Current Video LLMs Have Strong OCR Abilities? A Preliminary Study

# 摘要

> 随着多模态大型语言模型的兴起，从视频内容中精确提取和理解文本信息，也就是所谓的基于视频的光学字符识别（Video OCR），已成为关键能力。本文引入了一个全新的基准，用于评估多模态模型在视频中的 Video OCR 性能。此基准包含 1028 个视频和 2961 个问答对，并通过 6 个不同的子任务提出了若干关键挑战：（1）文本内容本身及其基本视觉属性的识别，（2）视频中 OCR 对象的语义和空间理解，（3）动态运动检测和时间定位。我们通过一种半自动化的方式开发了这一基准，将图像 LLMs 的 OCR 能力与人工优化相结合，平衡了效率、成本和数据质量。我们的资源旨在助力视频 LLMs 的研究，并突出了提升视频 LLMs 的 OCR 能力的必要性。该基准将在 https://github.com/YuHuiGao/FG-Bench.git 发布。

> With the rise of multimodal large language models, accurately extracting and understanding textual information from video content, referred to as video based optical character recognition (Video OCR), has become a crucial capability. This paper introduces a novel benchmark designed to evaluate the video OCR performance of multi-modal models in videos. Comprising 1,028 videos and 2,961 question-answer pairs, this benchmark proposes several key challenges through 6 distinct subtasks: (1) Recognition of text content itself and its basic visual attributes, (2)Semantic and Spatial Comprehension of OCR objects in videos (3) Dynamic Motion detection and Temporal Localization. We developed this benchmark using a semi-automated approach that integrates the OCR ability of image LLMs with manual refinement, balancing efficiency, cost, and data quality. Our resource aims to help advance research in video LLMs and underscores the need for improving OCR ability for video LLMs. The benchmark will be released on https://github.com/YuHuiGao/FG-Bench.git.

[Arxiv](https://arxiv.org/abs/2412.20613)