# 图世界模型

发布时间：2025年07月14日

`LLM理论

理由：这篇论文提出了一个新的模型架构（图世界模型GWM），探讨了如何处理图结构化数据和多模态信息，并分析了其在多个任务中的表现。这属于模型的理论和方法论层面的研究，因此归类为LLM理论。` `信息检索` `推荐系统`

> Graph World Model

# 摘要

> 世界模型 (WMs) 在预测、生成和规划任务中表现卓越。然而，现有 WM 主要聚焦于非结构化数据，难以利用数字世界中广泛存在的图结构化数据。尽管已有多种图基础模型问世，但它们局限于图学习任务，难以扩展至多模态数据与跨学科场景。为应对这些挑战，我们提出了图世界模型 (GWM)，一个支持非结构化与图结构状态、多模态信息，并将多样化任务表示为动作的世界模型。GWM 的核心是通用消息传递算法，可聚合结构化信息，支持通过统一多模态令牌空间（GWM-T）或模态特定编码器构建的统一多模态嵌入空间（GWM-E）实现。值得注意的是，GWM 引入了动作节点以支持多样化任务，这些节点可通过直接引用或相似性计算与其他节点相连。在多模态生成与匹配、推荐、图预测、多智能体、检索增强生成以及规划与优化等六个跨领域任务上的大量实验表明，GWM 在性能上超越或媲美特定领域基线模型，有效利用多跳结构，并在未见过的新任务上展现出强大的零样本/少样本能力。我们的 GWM 代码已开源，地址为 https://github.com/ulab-uiuc/GWM。


> World models (WMs) demonstrate strong capabilities in prediction, generation, and planning tasks. Existing WMs primarily focus on unstructured data and cannot leverage the ubiquitous structured data, often represented as graphs, in the digital world. While multiple graph foundation models have been proposed, they focus on graph learning tasks and cannot extend to diverse multi-modal data and interdisciplinary tasks. To address these challenges, we propose the Graph World Model (GWM), a world model that supports both unstructured and graph-structured states with multi-modal information and represents diverse tasks as actions. The core of a GWM is a generic message-passing algorithm to aggregate structured information, either over a unified multi-modal token space by converting multi-modal data into text (GWM-T) or a unified multi-modal embedding space by modality-specific encoders (GWM-E). Notably, GWM introduces action nodes to support diverse tasks, where action nodes are linked to other nodes via direct reference or similarity computation. Extensive experiments on six tasks from diverse domains, including multi-modal generation and matching, recommendation, graph prediction, multi-agent, retrieval-augmented generation, and planning and optimization, show that the same GWM outperforms or matches domain-specific baselines' performance, benefits from multi-hop structures, and demonstrates strong zero-shot/few-shot capabilities on unseen new tasks. Our code for GWM is released at https://github.com/ulab-uiuc/GWM.

[Arxiv](https://arxiv.org/abs/2507.10539)