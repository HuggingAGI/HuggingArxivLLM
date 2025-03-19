# # 多模态大语言模型与人类偏好对齐：综述

发布时间：2025年03月18日

`LLM理论

理由：这篇论文讨论了多模态大规模语言模型（MLLMs）的对齐算法，包括其应用场景、数据集构建、评估基准和未来方向。对齐算法旨在解决模型输出与人类偏好对齐的问题，属于理论层面的探讨，因此归类为LLM理论。` `人工智能`

> Aligning Multimodal LLM with Human Preference: A Survey

# 摘要

> 大规模语言模型（LLMs）凭借简单的提示即可处理多种通用任务，无需针对具体任务进行额外训练。在此基础上构建的多模态大规模语言模型（MLLMs）在处理涉及视觉、听觉和文本数据的复杂任务时展现出了巨大潜力。然而，真实性、安全性、o1-like推理以及与人类偏好对齐等关键问题仍未得到充分解决。这一差距催生了多种对齐算法，每种算法针对不同的应用场景和优化目标。近期研究表明，对齐算法是解决上述挑战的有效手段。本文旨在对MLLMs的对齐算法进行全面、系统的综述。具体而言，我们将从四个方面展开探讨：（1）对齐算法的应用场景，涵盖通用图像理解、多图像、视频和音频处理，以及扩展的多模态应用；（2）构建对齐数据集的核心要素，包括数据来源、模型响应和偏好标注；（3）用于评估对齐算法的基准；（4）未来对齐算法发展的潜在方向。本研究旨在帮助研究人员整理当前领域的进展，并激发更优的对齐方法。本文的项目页面可在以下链接找到：https://github.com/BradyFU/Awesome-Multimodal-Large-Language-Models/tree/Alignment。

> Large language models (LLMs) can handle a wide variety of general tasks with simple prompts, without the need for task-specific training. Multimodal Large Language Models (MLLMs), built upon LLMs, have demonstrated impressive potential in tackling complex tasks involving visual, auditory, and textual data. However, critical issues related to truthfulness, safety, o1-like reasoning, and alignment with human preference remain insufficiently addressed. This gap has spurred the emergence of various alignment algorithms, each targeting different application scenarios and optimization goals. Recent studies have shown that alignment algorithms are a powerful approach to resolving the aforementioned challenges. In this paper, we aim to provide a comprehensive and systematic review of alignment algorithms for MLLMs. Specifically, we explore four key aspects: (1) the application scenarios covered by alignment algorithms, including general image understanding, multi-image, video, and audio, and extended multimodal applications; (2) the core factors in constructing alignment datasets, including data sources, model responses, and preference annotations; (3) the benchmarks used to evaluate alignment algorithms; and (4) a discussion of potential future directions for the development of alignment algorithms. This work seeks to help researchers organize current advancements in the field and inspire better alignment methods. The project page of this paper is available at https://github.com/BradyFU/Awesome-Multimodal-Large-Language-Models/tree/Alignment.

[Arxiv](https://arxiv.org/abs/2503.14504)