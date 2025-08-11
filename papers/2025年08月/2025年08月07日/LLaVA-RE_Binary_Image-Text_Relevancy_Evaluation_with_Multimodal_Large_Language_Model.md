# **LLaVA-RE：基于多模态大型语言模型的二元图像文本相关性评估**

发布时间：2025年08月07日

`LLM应用` `语言模型`

> LLaVA-RE: Binary Image-Text Relevancy Evaluation with Multimodal Large Language Model

# 摘要

> 多模态生成式AI通常根据另一种模态的输入生成图像或文本响应。评估图像-文本相关性对于衡量响应质量或对候选响应进行排序至关重要。其中，二元相关性评估（“相关”与“不相关”）是一个基础问题。然而，由于文本格式多样且相关性定义因场景而异，这一任务颇具挑战性。我们发现，多模态大型语言模型（MLLMs）是构建此类评估器的理想选择，因其能够灵活处理复杂文本格式并接收额外任务信息。本文中，我们介绍了LLaVA-RE——首个基于MLLM的二元图像-文本相关性评估尝试。它基于LLaVA架构，采用详细任务指令和多模态上下文示例。此外，我们提出了一种涵盖多种任务的全新二元相关性数据集。实验结果验证了我们框架的有效性。

> Multimodal generative AI usually involves generating image or text responses given inputs in another modality. The evaluation of image-text relevancy is essential for measuring response quality or ranking candidate responses. In particular, binary relevancy evaluation, i.e., ``Relevant'' vs. ``Not Relevant'', is a fundamental problem. However, this is a challenging task considering that texts have diverse formats and the definition of relevancy varies in different scenarios. We find that Multimodal Large Language Models (MLLMs) are an ideal choice to build such evaluators, as they can flexibly handle complex text formats and take in additional task information. In this paper, we present LLaVA-RE, a first attempt for binary image-text relevancy evaluation with MLLM. It follows the LLaVA architecture and adopts detailed task instructions and multimodal in-context samples. In addition, we propose a novel binary relevancy data set that covers various tasks. Experimental results validate the effectiveness of our framework.

[Arxiv](https://arxiv.org/abs/2508.05602)