# RAIDX：结合检索增强生成与 GRPO 强化学习的可解释深度伪造检测框架

发布时间：2025年08月06日

`RAG` `图像处理`

> RAIDX: A Retrieval-Augmented Generation and GRPO Reinforcement Learning Framework for Explainable Deepfake Detection

# 摘要

> 人工智能生成模型的快速发展使得创造超现实主义图像成为可能，这一技术通过广泛传播的虚假信息带来了伦理风险。当前的深度伪造检测方法可分为面向特定人脸的检测器或通用AI生成检测器，它们通过将检测任务视为分类问题而缺乏透明度，未能对检测决策进行解释。尽管一些基于LLM的方法提供了可解释性，但它们存在粒度较粗的分析和对劳动密集型标注的依赖问题。本文提出了RAIDX（基于检索增强的图像深度伪造检测与可解释性框架），这是一种将检索增强生成（RAG）与组相对策略优化（GRPO）相结合的新型深度伪造检测框架，旨在提高检测准确性和决策可解释性。具体而言，RAIDX利用RAG整合外部知识以提升检测精度，并借助GRPO自主生成细粒度的文本解释和显著性图谱，从而避免了繁琐的手动标注需求。在多个基准测试中的实验结果表明，RAIDX在识别真实或伪造图像方面表现出色，同时能够通过文本描述和显著性图谱提供可解释的推理依据，实现了最先进的检测性能，同时推动了深度伪造识别的透明化。RAIDX是首个将RAG与GRPO协同结合的统一框架，有效填补了检测准确性和可解释性方面的关键空白。我们的代码和模型将公开发布。

> The rapid advancement of AI-generation models has enabled the creation of hyperrealistic imagery, posing ethical risks through widespread misinformation. Current deepfake detection methods, categorized as face specific detectors or general AI-generated detectors, lack transparency by framing detection as a classification task without explaining decisions. While several LLM-based approaches offer explainability, they suffer from coarse-grained analyses and dependency on labor-intensive annotations. This paper introduces RAIDX (Retrieval-Augmented Image Deepfake Detection and Explainability), a novel deepfake detection framework integrating Retrieval-Augmented Generation (RAG) and Group Relative Policy Optimization (GRPO) to enhance detection accuracy and decision explainability. Specifically, RAIDX leverages RAG to incorporate external knowledge for improved detection accuracy and employs GRPO to autonomously generate fine-grained textual explanations and saliency maps, eliminating the need for extensive manual annotations. Experiments on multiple benchmarks demonstrate RAIDX's effectiveness in identifying real or fake, and providing interpretable rationales in both textual descriptions and saliency maps, achieving state-of-the-art detection performance while advancing transparency in deepfake identification. RAIDX represents the first unified framework to synergize RAG and GRPO, addressing critical gaps in accuracy and explainability. Our code and models will be publicly available.

[Arxiv](https://arxiv.org/abs/2508.04524)