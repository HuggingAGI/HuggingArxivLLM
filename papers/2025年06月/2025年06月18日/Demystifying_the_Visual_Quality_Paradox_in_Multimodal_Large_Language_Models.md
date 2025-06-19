# # 多模态大型语言模型中的视觉质量悖论解析

发布时间：2025年06月18日

`LLM应用` `计算机视觉`

> Demystifying the Visual Quality Paradox in Multimodal Large Language Models

# 摘要

> 多模态大型语言模型（MLLMs）在视觉-语言任务中表现出色，但我们对输入视觉质量如何影响其表现知之甚少。更高的图像质量是否必然带来更好的理解？我们首次系统性研究了领先MLLMs和视觉-语言基准测试，对图像进行了受控降级和风格转换。令人惊讶的是，我们发现视觉质量悖论：当图像偏离人类感知的保真度时，模型、任务甚至单个实例的性能可能会提升。现有修复方法无法调和这些特殊偏好。为解决这一问题，我们提出了视觉质量测试时间调优（VQ-TTT）——一个轻量级模块，通过插入低秩核调节频率内容，并仅微调浅层视觉编码器。VQ-TTT在单次前向传递中动态调整图像，使其与模型偏好匹配。在所有评估中，VQ-TTT显著提升了准确性，无需额外数据或模型。这重新定义了MLLMs的“更好”视觉输入，强调了适应性图像的重要性，而非传统“干净”图像。

> Recent Multimodal Large Language Models (MLLMs) excel on benchmark vision-language tasks, yet little is known about how input visual quality shapes their responses. Does higher perceptual quality of images already translate to better MLLM understanding? We conduct the first systematic study spanning leading MLLMs and a suite of vision-language benchmarks, applying controlled degradations and stylistic shifts to each image. Surprisingly, we uncover a visual-quality paradox: model, task, and even individual-instance performance can improve when images deviate from human-perceived fidelity. Off-the-shelf restoration pipelines fail to reconcile these idiosyncratic preferences. To close the gap, we introduce Visual-Quality Test-Time Tuning (VQ-TTT)-a lightweight adaptation module that: (1) inserts a learnable, low-rank kernel before the frozen vision encoder to modulate frequency content; and (2) fine-tunes only shallow vision-encoder layers via LoRA. VQ-TTT dynamically adjusts each input image in a single forward pass, aligning it with task-specific model preferences. Across the evaluated MLLMs and all datasets, VQ-TTT lifts significant average accuracy, with no external models, cached features, or extra training data. These findings redefine ``better'' visual inputs for MLLMs and highlight the need for adaptive, rather than universally ``clean'', imagery, in the new era of AI being the main data customer.

[Arxiv](https://arxiv.org/abs/2506.15645)