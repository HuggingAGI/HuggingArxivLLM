# # 多模态大语言模型赋能端到端情感计算：生成知识提示驱动的基准评测与性能提升

发布时间：2025年08月04日

`LLM应用` `情感计算` `多模态处理`

> Multimodal Large Language Models for End-to-End Affective Computing: Benchmarking and Boosting with Generative Knowledge Prompting

# 摘要

> # 多模态情感计算（MAC）
多模态情感计算（MAC）的目标是通过整合文本、视频和音频等多种模态的信息，实现对人类情感的识别与解读。近年来，多模态大型语言模型（MLLMs）的突破性进展为MAC领域带来了革命性的变化，不仅提供了一个统一的框架来处理和对齐跨模态信息，还显著提升了情感计算的效率与准确性。

然而，尽管取得了显著进展，多模态情感计算在实际应用中仍面临诸多挑战。首先，现有模型在处理复杂MAC任务时，性能表现存在较大波动；其次，我们对模型架构设计和数据特性如何影响情感分析结果的理解仍然有限。针对这些研究空白，我们对一系列先进的开源MLLMs展开了系统性的基准评估，这些模型能够同时处理音频、视觉和文本等多种模态信息，并在多个已建立的MAC数据集上进行测试。

通过此次评估，我们不仅全面比较了不同MLLMs的性能表现，还深入分析了模型架构和数据集属性对情感分析结果的影响，从而为模型优化提供了切实可行的见解。此外，我们创新性地提出了一种结合生成式知识提示与监督微调的混合策略，旨在进一步提升MLLMs在情感计算任务中的表现。实验结果表明，这种综合方法在多种MAC任务中均取得了显著的性能提升，为未来在该领域的研究与发展提供了极具潜力的方向。

我们的代码已开源，地址为：https://github.com/LuoMSen/MLLM-MAC。

> Multimodal Affective Computing (MAC) aims to recognize and interpret human emotions by integrating information from diverse modalities such as text, video, and audio. Recent advancements in Multimodal Large Language Models (MLLMs) have significantly reshaped the landscape of MAC by offering a unified framework for processing and aligning cross-modal information. However, practical challenges remain, including performance variability across complex MAC tasks and insufficient understanding of how architectural designs and data characteristics impact affective analysis. To address these gaps, we conduct a systematic benchmark evaluation of state-of-the-art open-source MLLMs capable of concurrently processing audio, visual, and textual modalities across multiple established MAC datasets. Our evaluation not only compares the performance of these MLLMs but also provides actionable insights into model optimization by analyzing the influence of model architectures and dataset properties. Furthermore, we propose a novel hybrid strategy that combines generative knowledge prompting with supervised fine-tuning to enhance MLLMs' affective computing capabilities. Experimental results demonstrate that this integrated approach significantly improves performance across various MAC tasks, offering a promising avenue for future research and development in this field. Our code is released on https://github.com/LuoMSen/MLLM-MAC.

[Arxiv](https://arxiv.org/abs/2508.02429)