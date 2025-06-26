# 视觉语言模型在新领域的扩展：一项系统性综述

发布时间：2025年06月23日

`LLM应用

理由：这篇论文探讨了视觉语言模型（VLMs）的应用和迁移方法，属于将大型语言模型应用于视觉和文本结合的领域，因此归类为LLM应用。` `多模态学习` `多模态应用`

> Generalizing Vision-Language Models to Novel Domains: A Comprehensive Survey

# 摘要

> 视觉语言预训练正以一种整合视觉与文本优势的革命性技术重塑领域格局，造就了强大的视觉语言模型（VLMs）。凭借网络规模的预训练数据，这些模型展现了卓越的零样本能力。然而，在面对领域特定或专业化的泛化任务时，性能往往不尽如人意。为解决这一难题，越来越多的研究致力于将VLMs中的丰富知识迁移或泛化到各类下游应用中。本综述旨在全面梳理视觉语言文献中的泛化设置、方法、基准测试及研究成果。深入剖析典型VLM结构后，根据迁移模块的不同，当前文献被归类为基于提示、基于参数和基于特征的方法。通过重新审视迁移学习（TL）的典型设置，进一步提炼并探讨了各类方法的差异与特点，为VLM时代的迁移学习提供了全新视角。此外，我们还介绍了流行的VLM泛化基准，并对各类方法进行了详尽的性能对比。伴随大规模可泛化预训练技术的进步，本综述还深入探讨了VLMs与最新多模态大语言模型（MLLM）（如DeepSeek-VL）之间的关系与差异。通过从新颖且实用的泛化视角系统性地回顾视觉语言研究领域的最新进展，本综述为当前及未来的多模态研究领域描绘出清晰的发展蓝图。

> Recently, vision-language pretraining has emerged as a transformative technique that integrates the strengths of both visual and textual modalities, resulting in powerful vision-language models (VLMs). Leveraging web-scale pretraining data, these models exhibit strong zero-shot capabilities. However, their performance often deteriorates when confronted with domain-specific or specialized generalization tasks. To address this, a growing body of research focuses on transferring or generalizing the rich knowledge embedded in VLMs to various downstream applications. This survey aims to comprehensively summarize the generalization settings, methodologies, benchmarking and results in VLM literatures. Delving into the typical VLM structures, current literatures are categorized into prompt-based, parameter-based and feature-based methods according to the transferred modules. The differences and characteristics in each category are furthered summarized and discussed by revisiting the typical transfer learning (TL) settings, providing novel interpretations for TL in the era of VLMs. Popular benchmarks for VLM generalization are further introduced with thorough performance comparisons among the reviewed methods. Following the advances in large-scale generalizable pretraining, this survey also discusses the relations and differences between VLMs and up-to-date multimodal large language models (MLLM), e.g., DeepSeek-VL. By systematically reviewing the surging literatures in vision-language research from a novel and practical generalization prospective, this survey contributes to a clear landscape of current and future multimodal researches.

[Arxiv](https://arxiv.org/abs/2506.18504)