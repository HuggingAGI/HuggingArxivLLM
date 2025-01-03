# COEF-VQ: 基于级联多模态LLM框架的高性价比视频质量理解

发布时间：2024年12月11日

`LLM应用

理由：这篇论文主要讨论了如何利用多模态大型语言模型（MLLM）技术来提升TikTok视频质量的理解能力，并提出了一个名为COEF-VQ的级联MLLM框架。该框架通过融合视觉、文本和音频信号，并采用轻量级模型预过滤和MLLM精细处理的方法，显著降低了GPU资源需求，同时保持了MLLM的卓越性能。论文的重点在于如何在实际应用中（如TikTok的视频管理平台）有效地部署和优化MLLM，因此属于LLM应用的范畴。` `社交媒体` `视频处理`

> COEF-VQ: Cost-Efficient Video Quality Understanding through a Cascaded Multimodal LLM Framework

# 摘要

> # 摘要
随着多模态大型语言模型（MLLM）技术的兴起，利用其视频理解能力进行多样化分类任务成为可能。然而，在线部署MLLMs时，巨大的GPU资源需求成为一大挑战。本文提出了一种名为COEF-VQ的级联MLLM框架，旨在提升TikTok视频质量的理解能力。我们首先设计了一种融合视觉、文本和音频信号的MLLM，随后构建了一个包含轻量级模型预过滤和MLLM精细处理的级联框架，显著降低了GPU资源需求，同时保持了MLLM的卓越性能。为验证COEF-VQ的有效性，我们将其部署于TikTok的视频管理平台（VMP），并在两个内部视频质量理解任务上进行了详尽实验。结果表明，COEF-VQ在资源有限的情况下，显著提升了任务性能。

> Recently, with the emergence of recent Multimodal Large Language Model (MLLM) technology, it has become possible to exploit its video understanding capability on different classification tasks. In practice, we face the difficulty of huge requirements for GPU resource if we need to deploy MLLMs online. In this paper, we propose COEF-VQ, a novel cascaded MLLM framework for better video quality understanding on TikTok. To this end, we first propose a MLLM fusing all visual, textual and audio signals, and then develop a cascade framework with a lightweight model as pre-filtering stage and MLLM as fine-consideration stage, significantly reducing the need for GPU resource, while retaining the performance demonstrated solely by MLLM. To demonstrate the effectiveness of COEF-VQ, we deployed this new framework onto the video management platform (VMP) at TikTok, and performed a series of detailed experiments on two in-house tasks related to video quality understanding. We show that COEF-VQ leads to substantial performance gains with limit resource consumption in these two tasks.

[Arxiv](https://arxiv.org/abs/2412.10435)