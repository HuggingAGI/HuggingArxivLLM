# Filter-And-Refine：基于MLLM的级联系统，实现工业级视频内容审核

发布时间：2025年07月23日

`LLM应用

摘要中的论文讨论了如何将多模态大语言模型（MLLMs）应用于内容审核任务，提出了一种高效的方法和系统设计，以解决工业应用中的挑战。这属于将LLM应用于实际问题的范畴，因此归类为“LLM应用”。` `视频平台` `人工智能`

> Filter-And-Refine: A MLLM Based Cascade System for Industrial-Scale Video Content Moderation

# 摘要

> 内容审核是视频平台保障用户体验和维护社区标准的关键。传统视频分类模型在处理明确定义的内容审核任务时表现出色，但在面对隐含有害内容和上下文模糊等复杂场景时显得力不从心。多模态大语言模型（MLLMs）凭借其卓越的跨模态推理和上下文理解能力，为解决这些问题提供了新思路。然而，MLLMs在工业应用中面临两大挑战：高昂的计算成本和生成模型向判别分类的适应问题。本文提出了一种高效方法，仅需少量判别训练数据即可将生成式MLLM转化为多模态分类器。我们还设计了一种路由-排序级联系统，结合MLLM与轻量级路由模型，实现工业规模部署。离线实验显示，与传统分类器相比，我们的MLLM基方法将F1分数提升了66.50%，仅需2%的微调数据。在线评估表明，我们的系统将自动内容审核量增加了41%，而级联部署将计算成本降低到直接全面部署的1.5%。

> Effective content moderation is essential for video platforms to safeguard user experience and uphold community standards. While traditional video classification models effectively handle well-defined moderation tasks, they struggle with complicated scenarios such as implicit harmful content and contextual ambiguity. Multimodal large language models (MLLMs) offer a promising solution to these limitations with their superior cross-modal reasoning and contextual understanding. However, two key challenges hinder their industrial adoption. First, the high computational cost of MLLMs makes full-scale deployment impractical. Second, adapting generative models for discriminative classification remains an open research problem. In this paper, we first introduce an efficient method to transform a generative MLLM into a multimodal classifier using minimal discriminative training data. To enable industry-scale deployment, we then propose a router-ranking cascade system that integrates MLLMs with a lightweight router model. Offline experiments demonstrate that our MLLM-based approach improves F1 score by 66.50% over traditional classifiers while requiring only 2% of the fine-tuning data. Online evaluations show that our system increases automatic content moderation volume by 41%, while the cascading deployment reduces computational cost to only 1.5% of direct full-scale deployment.

[Arxiv](https://arxiv.org/abs/2507.17204)