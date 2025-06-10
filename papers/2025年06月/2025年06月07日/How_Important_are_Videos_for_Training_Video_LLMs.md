# 视频在训练视频LLMs中扮演怎样的关键角色？

发布时间：2025年06月07日

`LLM应用` `视频分析` `计算机视觉`

> How Important are Videos for Training Video LLMs?

# 摘要

> 视频大型语言模型（Video LLMs）的研究发展迅猛，短短几年间已涌现出众多模型与基准测试。通常，这些模型基于预先训练的纯文本LLM进行初始化，并在图像和视频描述数据集上进行微调。本文的研究发现表明，与预期相反，仅经过图像训练的Video LLMs在时间推理方面的能力更强，而专门针对视频的训练改进却出人意料地微小。具体来说，我们发现使用最近的LongVU算法训练的两个LLM的图像训练版本在TVBench（一个时间推理基准测试）上的表现显著高于随机水平。此外，我们引入了一种简单的微调方案，涉及标注图像序列和针对时间能力的问题。这一基线方法在时间推理性能上接近，有时甚至超越了视频训练的LLMs。这表明，当前模型对真实视频中丰富的时序特征的利用效率可能不高。我们的分析促使进一步研究使图像训练的LLM能够进行时间推理的机制，以及导致当前视频训练方案低效的瓶颈。

> Research into Video Large Language Models (LLMs) has progressed rapidly, with numerous models and benchmarks emerging in just a few years. Typically, these models are initialized with a pretrained text-only LLM and finetuned on both image- and video-caption datasets. In this paper, we present findings indicating that Video LLMs are more capable of temporal reasoning after image-only training than one would assume, and that improvements from video-specific training are surprisingly small. Specifically, we show that image-trained versions of two LLMs trained with the recent LongVU algorithm perform significantly above chance level on TVBench, a temporal reasoning benchmark. Additionally, we introduce a simple finetuning scheme involving sequences of annotated images and questions targeting temporal capabilities. This baseline results in temporal reasoning performance close to, and occasionally higher than, what is achieved by video-trained LLMs. This suggests suboptimal utilization of rich temporal features found in real video by current models. Our analysis motivates further research into the mechanisms that allow image-trained LLMs to perform temporal reasoning, as well as into the bottlenecks that render current video training schemes inefficient.

[Arxiv](https://arxiv.org/abs/2506.06928)