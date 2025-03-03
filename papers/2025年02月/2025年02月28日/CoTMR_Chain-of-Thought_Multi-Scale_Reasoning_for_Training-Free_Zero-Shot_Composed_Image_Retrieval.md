# CoTMR：用于无训练零样本组合图像检索的多尺度链式推理

发布时间：2025年02月28日

`LLM应用` `图像检索` `多模态`

> CoTMR: Chain-of-Thought Multi-Scale Reasoning for Training-Free Zero-Shot Composed Image Retrieval

# 摘要

> 零样本组合图像检索（ZS-CIR）的目标是通过整合参考图像和修改文本的信息来检索目标图像，且无需依赖训练样本。目前的方法主要结合caption模型和大型语言模型（LLMs）根据复合查询生成目标描述，但存在不兼容、视觉信息丢失和推理能力不足等问题。针对这些挑战，我们提出了一种无需训练的框架CoTMR，专为ZS-CIR设计，采用创新的思维链（CoT）和多尺度推理技术。与传统依赖caption模型进行模态转换的方法不同，CoTMR利用大视觉-语言模型（LVLM）实现对复合查询的统一理解和推理。为了提升推理的可靠性，我们设计了CIRCoT，通过预定义的子任务引导LVLM进行逐步推理。考虑到现有方法仅关注全局推理，我们的CoTMR引入了多尺度推理机制，通过对象尺度对关键元素的存在或缺失进行细粒度预测，从而实现更全面的推理。此外，我们还设计了一种多粒度评分（MGS）机制，整合上述推理输出与候选图像的CLIP相似度分数，实现精确检索。大量实验结果表明，我们的CoTMR不仅在四个知名基准测试中大幅超越了先前方法，还提供了令人满意的可解释性。

> Zero-Shot Composed Image Retrieval (ZS-CIR) aims to retrieve target images by integrating information from a composed query (reference image and modification text) without training samples. Existing methods primarily combine caption models and large language models (LLMs) to generate target captions based on composed queries but face various issues such as incompatibility, visual information loss, and insufficient reasoning. In this work, we propose CoTMR, a training-free framework crafted for ZS-CIR with novel Chain-of-thought (CoT) and Multi-scale Reasoning. Instead of relying on caption models for modality transformation, CoTMR employs the Large Vision-Language Model (LVLM) to achieve unified understanding and reasoning for composed queries. To enhance the reasoning reliability, we devise CIRCoT, which guides the LVLM through a step-by-step inference process using predefined subtasks. Considering that existing approaches focus solely on global-level reasoning, our CoTMR incorporates multi-scale reasoning to achieve more comprehensive inference via fine-grained predictions about the presence or absence of key elements at the object scale. Further, we design a Multi-Grained Scoring (MGS) mechanism, which integrates CLIP similarity scores of the above reasoning outputs with candidate images to realize precise retrieval. Extensive experiments demonstrate that our CoTMR not only drastically outperforms previous methods across four prominent benchmarks but also offers appealing interpretability.

[Arxiv](https://arxiv.org/abs/2502.20826)