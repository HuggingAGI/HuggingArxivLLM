# # UniWorld：高分辨率语义编码器助力统一视觉理解和生成

发布时间：2025年06月04日

`LLM应用

摘要讨论了如何利用多模态大型语言模型（如GPT-4o-Image）的图像感知与操作能力，提出了UniWorld框架，并展示了其在多个任务中的应用。这属于将LLM应用于实际任务的范畴。` `图像处理` `计算机视觉`

> UniWorld: High-Resolution Semantic Encoders for Unified Visual Understanding and Generation

# 摘要

> 现有统一模型在视觉语言理解和文本到图像生成方面表现优异，但在图像感知与操作能力上仍显不足，而这些能力在实际应用中需求日益增长。近期，OpenAI推出了强大的GPT-4o-Image模型，其在图像感知与操作方面展现出卓越能力，引发广泛关注。通过精心设计的实验，我们发现GPT-4o-Image可能采用语义编码器而非变分自编码器（VAEs）进行特征提取，尽管VAEs通常被认为是图像操作任务中的关键组件。基于此，我们提出了UniWorld——一个基于强大多模态大型语言模型提取的语义特征和对比语义编码器构建的统一生成框架。仅使用2.7M训练数据，UniWorld在图像理解、生成、操作和感知等多样化任务中均展现出卓越性能。我们已完全开源UniWorld框架，包括模型权重、训练与评估脚本及数据集，以促进研究与应用的可重复性与进一步发展。

> Although existing unified models achieve strong performance in vision-language understanding and text-to-image generation, they remain limited in addressing image perception and manipulation -- capabilities increasingly demanded in practical applications. Recently, OpenAI introduced the powerful GPT-4o-Image model, which showcases advanced capabilities in comprehensive image perception and manipulation, sparking widespread interest. Through carefully designed experiments, we observe that GPT-4o-Image likely relies on semantic encoders rather than VAEs for feature extraction, despite VAEs being commonly regarded as crucial for image manipulation tasks. Inspired by this insight, we propose UniWorld, a unified generative framework built upon semantic features extracted from powerful multimodal large language models and contrastive semantic encoders. Using only 2.7M training data, UniWorld achieves impressive performance across diverse tasks, including image understanding, generation, manipulation, and perception. We fully open-source the UniWorld framework, including model weights, training and evaluation scripts, and datasets to promote reproducibility and further research.

[Arxiv](https://arxiv.org/abs/2506.03147)