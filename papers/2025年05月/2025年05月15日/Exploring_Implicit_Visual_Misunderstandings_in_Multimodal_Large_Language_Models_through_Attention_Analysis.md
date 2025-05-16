# 探索多模态大型语言模型中的隐性视觉误解问题：基于注意力分析

发布时间：2025年05月15日

`LLM应用` `计算机视觉`

> Exploring Implicit Visual Misunderstandings in Multimodal Large Language Models through Attention Analysis

# 摘要

> 近期研究显著提升了多模态大型语言模型（MLLMs）对多图像信息的理解能力。然而，现有评估指标主要关注答案的正确性，却忽视了模型是否真正理解了视觉输入。为解决这一问题，我们提出了“隐式视觉误解”（IVM）的概念——即模型在未完全理解视觉输入的情况下仍能给出正确答案。通过深入分析，我们解耦了因果注意力模块中的视觉与文本模态，发现随着网络层数的加深，注意力分布逐渐聚焦于与正确答案相关的图像。这一发现启发我们提出了一个尺度无关的评估指标——	extit{注意力准确率}，并构建了一个全新的基准测试来量化IVM。该指标通过模型内部机制直接评估视觉理解能力，有效克服了位置偏见的影响，从而提供更可靠的评估结果。此外，我们将这一方法扩展至更细粒度的分析，并在单模态场景中验证了其有效性，充分展现了其多样性和泛化能力。

> Recent advancements have enhanced the capability of Multimodal Large Language Models (MLLMs) to comprehend multi-image information. However, existing benchmarks primarily evaluate answer correctness, overlooking whether models genuinely comprehend the visual input. To address this, we define implicit visual misunderstanding (IVM), where MLLMs provide correct answers without fully comprehending the visual input. Through our analysis, we decouple the visual and textual modalities within the causal attention module, revealing that attention distribution increasingly converges on the image associated with the correct answer as the network layers deepen. This insight leads to the introduction of a scale-agnostic metric, \textit{attention accuracy}, and a novel benchmark for quantifying IVMs. Attention accuracy directly evaluates the model's visual understanding via internal mechanisms, remaining robust to positional biases for more reliable assessments. Furthermore, we extend our approach to finer granularities and demonstrate its effectiveness in unimodal scenarios, underscoring its versatility and generalizability.

[Arxiv](https://arxiv.org/abs/2505.10541)