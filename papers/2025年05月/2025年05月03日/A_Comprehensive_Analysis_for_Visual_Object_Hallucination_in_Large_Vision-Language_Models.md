# 大型视觉-语言模型中视觉对象幻觉的全面分析

发布时间：2025年05月03日

`LLM应用` `视觉语言模型` `多模态`

> A Comprehensive Analysis for Visual Object Hallucination in Large Vision-Language Models

# 摘要

> 大型视觉语言模型（LVLMs）在多模态任务中表现出色，但视觉物体幻觉问题仍然存在。这种现象指模型根据输入生成不准确的视觉信息，可能导致错误信息和安全问题。尽管前人研究主要关注视觉幻觉的评估和缓解，但其根本原因尚未被深入探究。本文深入分析了类似LLaVA的LVLMs的三大核心组件——大型语言模型、视觉主干和投影器——以识别潜在的错误来源及其影响。基于此，我们针对每个问题组件提出了相应的缓解方法。此外，我们还开发了两个幻觉基准测试：QA-VisualGenome专注于属性和关系幻觉，而QA-FB15k则聚焦于认知型幻觉。

> Large Vision-Language Models (LVLMs) demonstrate remarkable capabilities in multimodal tasks, but visual object hallucination remains a persistent issue. It refers to scenarios where models generate inaccurate visual object-related information based on the query input, potentially leading to misinformation and concerns about safety and reliability. Previous works focus on the evaluation and mitigation of visual hallucinations, but the underlying causes have not been comprehensively investigated. In this paper, we analyze each component of LLaVA-like LVLMs -- the large language model, the vision backbone, and the projector -- to identify potential sources of error and their impact. Based on our observations, we propose methods to mitigate hallucination for each problematic component. Additionally, we developed two hallucination benchmarks: QA-VisualGenome, which emphasizes attribute and relation hallucinations, and QA-FB15k, which focuses on cognition-based hallucinations.

[Arxiv](https://arxiv.org/abs/2505.01958)