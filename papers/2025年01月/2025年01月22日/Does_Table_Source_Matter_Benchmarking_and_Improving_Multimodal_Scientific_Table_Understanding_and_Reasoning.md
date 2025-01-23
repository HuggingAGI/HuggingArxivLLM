# 表格来源是否重要？多模态科学表格理解与推理的基准测试与优化

发布时间：2025年01月22日

`LLM应用

理由：这篇论文主要讨论了多模态大型语言模型（MLLMs）在科学表格理解与推理中的应用，提出了一个新的框架来解决现有模型在处理科学表格时的挑战。论文的核心内容围绕如何改进和优化LLM在特定任务（科学表格理解）中的应用，因此应归类为“LLM应用”。` `表格处理`

> Does Table Source Matter? Benchmarking and Improving Multimodal Scientific Table Understanding and Reasoning

# 摘要

> # 摘要
近期大型语言模型（LLMs）在表格理解方面取得了显著进展，但其依赖于将表格转换为文本序列。尽管多模态大型语言模型（MLLMs）支持直接视觉处理，但由于固定输入图像分辨率和数值推理能力的不足，它们在处理科学表格时仍面临挑战。我们提出了一种全新的多模态科学表格理解与推理框架，支持动态输入图像分辨率。该框架包含三大核心组件：（1）MMSci-Pre，一个包含52K科学表格结构识别样本的领域专用表格结构学习数据集；（2）MMSci-Ins，一个包含12K样本的指令调优数据集，涵盖三大基于表格的任务；（3）MMSci-Eval，一个包含3,114个测试样本的基准，专门用于评估数值推理能力。大量实验表明，与150K通用领域表格相比，我们的领域专用方法在52K科学表格图像上表现更优，凸显了数据质量的重要性。我们提出的动态输入分辨率表格MLLMs在通用表格理解和数值推理能力上均有显著提升，并对未见数据集展现出强大的泛化能力。代码和数据已开源，详见https://github.com/Bernard-Yang/MMSci_Table。

> Recent large language models (LLMs) have advanced table understanding capabilities but rely on converting tables into text sequences. While multimodal large language models (MLLMs) enable direct visual processing, they face limitations in handling scientific tables due to fixed input image resolutions and insufficient numerical reasoning capabilities. We present a comprehensive framework for multimodal scientific table understanding and reasoning with dynamic input image resolutions. Our framework consists of three key components: (1) MMSci-Pre, a domain-specific table structure learning dataset of 52K scientific table structure recognition samples, (2) MMSci-Ins, an instruction tuning dataset with 12K samples across three table-based tasks, and (3) MMSci-Eval, a benchmark with 3,114 testing samples specifically designed to evaluate numerical reasoning capabilities. Extensive experiments demonstrate that our domain-specific approach with 52K scientific table images achieves superior performance compared to 150K general-domain tables, highlighting the importance of data quality over quantity. Our proposed table-based MLLMs with dynamic input resolutions show significant improvements in both general table understanding and numerical reasoning capabilities, with strong generalisation to held-out datasets. Our code and data are publicly available at https://github.com/Bernard-Yang/MMSci_Table.

[Arxiv](https://arxiv.org/abs/2501.13042)