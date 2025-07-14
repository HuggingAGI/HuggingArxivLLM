# # LLaPa: 用于过程规划的反事实感知视觉-语言模型框架

发布时间：2025年07月11日

`LLM应用` `人工智能` `机器人`

> LLaPa: A Vision-Language Model Framework for Counterfactual-Aware Procedural Planning

# 摘要

> 尽管大型语言模型（LLMs）通过强大的推理能力显著提升了具身AI系统的过程规划能力，但多模态输入和反事实推理的整合仍然是一个未充分探索的领域。为此，我们提出了LLaPa——一个专为多模态过程规划设计的视觉语言模型框架。LLaPa能够从文本任务描述和视觉环境图像中生成可执行的动作序列，其核心是视觉语言模型（VLMs）。为了进一步提升过程规划能力，我们为LLaPa配备了两个辅助模块：任务-环境重排序器（TER）和反事实活动检索器（CAR）。TER通过任务导向的分割创建了一个任务敏感的特征空间，使文本描述与视觉环境实现精准对齐，并突出关键区域以优化过程执行。而CAR则专注于识别并强调潜在的反事实条件，从而显著提升了模型在反事实场景中的推理能力。在ActPlan-1K和ALFRED基准测试中，LLaPa展现了卓越的性能，其生成的计划在最长公共子序列（LCS）和正确性方面均优于现有先进模型。代码和模型已开源，可访问https://github.com/sunshibo1234/LLaPa获取。

> While large language models (LLMs) have advanced procedural planning for embodied AI systems through strong reasoning abilities, the integration of multimodal inputs and counterfactual reasoning remains underexplored. To tackle these challenges, we introduce LLaPa, a vision-language model framework designed for multimodal procedural planning. LLaPa generates executable action sequences from textual task descriptions and visual environmental images using vision-language models (VLMs). Furthermore, we enhance LLaPa with two auxiliary modules to improve procedural planning. The first module, the Task-Environment Reranker (TER), leverages task-oriented segmentation to create a task-sensitive feature space, aligning textual descriptions with visual environments and emphasizing critical regions for procedural execution. The second module, the Counterfactual Activities Retriever (CAR), identifies and emphasizes potential counterfactual conditions, enhancing the model's reasoning capability in counterfactual scenarios. Extensive experiments on ActPlan-1K and ALFRED benchmarks demonstrate that LLaPa generates higher-quality plans with superior LCS and correctness, outperforming advanced models. The code and models are available https://github.com/sunshibo1234/LLaPa.

[Arxiv](https://arxiv.org/abs/2507.08496)