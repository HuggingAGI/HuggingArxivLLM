# 高效整合大型语言模型与视觉感知：训练范式视角综述

发布时间：2025年02月03日

`LLM应用

理由：这篇论文主要讨论了如何将视觉模态整合到大型语言模型（LLMs）中，并回顾了不同的训练范式及其参数效率。这涉及到LLMs在多模态学习中的应用，特别是视觉-语言模态的整合。因此，这篇论文属于LLM应用的范畴。` `多模态学习`

> Efficiently Integrate Large Language Models with Visual Perception: A Survey from the Training Paradigm Perspective

# 摘要

> # 摘要
视觉-语言模态的整合一直是多模态学习的核心议题，传统上依赖视觉-语言预训练模型。然而，随着大型语言模型（LLMs）的崛起，将LLMs与视觉模态结合的范式发生了显著转变。随之而来的是，将视觉模态整合到LLMs中的训练范式也在不断演进。最初的方法是单阶段调优，通过预训练模态整合器来实现模态融合。随后，这一方法分化为两阶段调优（注重性能提升）和直接适应（注重参数效率）。然而，现有研究多聚焦于采用两阶段调优的最新视觉大型语言模型（VLLMs），而对训练范式的演变及其参数效率的独特考量缺乏深入探讨。本文从训练范式的角度，对来自顶级会议、期刊和高引用Arxiv论文的34个VLLMs进行了分类与回顾，重点关注适应过程中的参数效率。我们首先介绍了LLMs的架构和参数高效学习方法，随后探讨了视觉编码器，并对模态整合器进行了系统分类。接着，我们回顾了三种训练范式及其效率考量，并总结了VLLM领域的基准测试。为了更深入地评估参数效率，我们对比并讨论了代表性模型的实验结果，其中直接适应范式的实验被复现。本文为研究人员和实践者提供了关于视觉模态高效整合到LLMs中的最新进展与实践应用的宝贵指南。

> The integration of vision-language modalities has been a significant focus in multimodal learning, traditionally relying on Vision-Language Pretrained Models. However, with the advent of Large Language Models (LLMs), there has been a notable shift towards incorporating LLMs with vision modalities. Following this, the training paradigms for incorporating vision modalities into LLMs have evolved. Initially, the approach was to integrate the modalities through pretraining the modality integrator, named Single-stage Tuning. It has since branched out into methods focusing on performance enhancement, denoted as Two-stage Tuning, and those prioritizing parameter efficiency, referred to as Direct Adaptation. However, existing surveys primarily address the latest Vision Large Language Models (VLLMs) with Two-stage Tuning, leaving a gap in understanding the evolution of training paradigms and their unique parameter-efficient considerations. This paper categorizes and reviews 34 VLLMs from top conferences, journals, and highly cited Arxiv papers, focusing on parameter efficiency during adaptation from the training paradigm perspective. We first introduce the architecture of LLMs and parameter-efficient learning methods, followed by a discussion on vision encoders and a comprehensive taxonomy of modality integrators. We then review three training paradigms and their efficiency considerations, summarizing benchmarks in the VLLM field. To gain deeper insights into their effectiveness in parameter efficiency, we compare and discuss the experimental results of representative models, among which the experiment of the Direct Adaptation paradigm is replicated. Providing insights into recent developments and practical uses, this survey is a vital guide for researchers and practitioners navigating the efficient integration of vision modalities into LLMs.

[Arxiv](https://arxiv.org/abs/2502.01524)