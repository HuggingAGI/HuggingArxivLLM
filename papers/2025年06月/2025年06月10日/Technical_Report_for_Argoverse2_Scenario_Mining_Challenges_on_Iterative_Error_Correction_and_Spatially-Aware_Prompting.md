# 技术报告：Argoverse2场景挖掘挑战——关于迭代错误修正与空间感知提示的研究

发布时间：2025年06月10日

`LLM应用` `自动驾驶` `AI生成`

> Technical Report for Argoverse2 Scenario Mining Challenges on Iterative Error Correction and Spatially-Aware Prompting

# 摘要

> 从Argoverse 2等广泛自动驾驶数据集中进行场景挖掘，对自动驾驶系统的开发和验证至关重要。RefAV框架通过利用大型语言模型（LLMs）将自然语言查询转换为可执行代码来识别相关场景，展现出巨大潜力。然而，这种方法面临一些挑战，包括由LLM生成代码引发的运行时错误，以及在解释描述复杂多目标空间关系的函数参数时的不准确性。本技术报告介绍了两个关键改进，以解决这些限制：(1) 一种容错迭代代码生成机制，通过将错误反馈重新提示LLM来优化代码；(2) 专门的提示工程，以提高LLM对空间关系函数的理解和正确应用。在Argoverse 2验证集上使用多种LLMs（包括Qwen2.5-VL-7B、Gemini 2.5 Flash和Gemini 2.5 Pro）进行的实验显示，多个指标均有所提升；其中，使用Gemini 2.5 Pro在官方测试集上实现了52.37的HOTA-Temporal得分。这些结果凸显了所提技术在可靠、高精度场景挖掘中的有效性。


> Scenario mining from extensive autonomous driving datasets, such as Argoverse 2, is crucial for the development and validation of self-driving systems. The RefAV framework represents a promising approach by employing Large Language Models (LLMs) to translate natural-language queries into executable code for identifying relevant scenarios. However, this method faces challenges, including runtime errors stemming from LLM-generated code and inaccuracies in interpreting parameters for functions that describe complex multi-object spatial relationships. This technical report introduces two key enhancements to address these limitations: (1) a fault-tolerant iterative code-generation mechanism that refines code by re-prompting the LLM with error feedback, and (2) specialized prompt engineering that improves the LLM's comprehension and correct application of spatial-relationship functions. Experiments on the Argoverse 2 validation set with diverse LLMs-Qwen2.5-VL-7B, Gemini 2.5 Flash, and Gemini 2.5 Pro-show consistent gains across multiple metrics; most notably, the proposed system achieves a HOTA-Temporal score of 52.37 on the official test set using Gemini 2.5 Pro. These results underline the efficacy of the proposed techniques for reliable, high-precision scenario mining.

[Arxiv](https://arxiv.org/abs/2506.11124)