# HOLA：通过分层上下文聚合和高效预训练方法提升音频-视觉深度伪造检测效果

发布时间：2025年07月30日

`其他

理由：这篇论文主要讨论的是视频级深度伪造检测的技术，提出了一个名为HOLA的解决方案，并没有直接涉及到大型语言模型（LLM）的应用或理论，也没有涉及智能体（Agent）或检索增强生成（RAG）。因此，它更适合归类为“其他”。` `视频处理` `计算机视觉`

> HOLA: Enhancing Audio-visual Deepfake Detection via Hierarchical Contextual Aggregations and Efficient Pre-training

# 摘要

> 生成式AI的突破性进展使得视频级深度伪造检测更具挑战性，暴露出现有检测技术的不足。本文中，我们提出了HOLA，作为应对2025年1M-Deepfakes Detection Challenge视频级深度伪造检测赛道的解决方案。借鉴通用领域中大规模预训练的成功经验，我们在多模态视频级深度伪造检测中扩展了视听自监督预训练的规模，充分利用了我们自建的181万样本数据集，构建了一个统一的两阶段框架。具体而言，HOLA具备以下特点：迭代感知的跨模态学习模块，用于选择性视听交互；基于局部全局视角的门控聚合机制的层次化上下文建模；以及金字塔式细化模块，用于尺度感知的跨粒度语义增强。此外，我们还提出了伪监督信号注入策略，进一步提升模型性能。在专家模型和多语言大模型上的大量实验令人印象深刻地验证了我们提出的HOLA的有效性。我们还进行了一系列消融实验，深入探索了所引入组件的关键设计因素。值得一提的是，我们的HOLA在TestA数据集上以0.0476的AUC优势排名第一，超越了第二名。

> Advances in Generative AI have made video-level deepfake detection increasingly challenging, exposing the limitations of current detection techniques. In this paper, we present HOLA, our solution to the Video-Level Deepfake Detection track of 2025 1M-Deepfakes Detection Challenge. Inspired by the success of large-scale pre-training in the general domain, we first scale audio-visual self-supervised pre-training in the multimodal video-level deepfake detection, which leverages our self-built dataset of 1.81M samples, thereby leading to a unified two-stage framework. To be specific, HOLA features an iterative-aware cross-modal learning module for selective audio-visual interactions, hierarchical contextual modeling with gated aggregations under the local-global perspective, and a pyramid-like refiner for scale-aware cross-grained semantic enhancements. Moreover, we propose the pseudo supervised singal injection strategy to further boost model performance. Extensive experiments across expert models and MLLMs impressivly demonstrate the effectiveness of our proposed HOLA. We also conduct a series of ablation studies to explore the crucial design factors of our introduced components. Remarkably, our HOLA ranks 1st, outperforming the second by 0.0476 AUC on the TestA set.

[Arxiv](https://arxiv.org/abs/2507.22781)