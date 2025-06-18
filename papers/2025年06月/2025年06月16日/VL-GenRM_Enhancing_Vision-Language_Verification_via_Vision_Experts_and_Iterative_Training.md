# VL-GenRM：借助视觉专家和迭代训练提升视觉语言验证能力

发布时间：2025年06月16日

`LLM应用

理由：这篇论文探讨了如何将强化学习和特定的训练方法应用于视觉语言模型，以优化其对齐和性能。研究涉及模型的应用层面，特别是多模态推理和幻觉检测，属于LLM应用的范畴。` `视觉语言模型`

> VL-GenRM: Enhancing Vision-Language Verification via Vision Experts and Iterative Training

# 摘要

> 基于可验证奖励的强化微调（RFT）推动了大型语言模型的发展，但对于视觉语言（VL）模型而言，这一方法仍未得到充分探索。视觉语言奖励模型（VL-RM）在对齐VL模型方面发挥关键作用，然而，训练有效的VL-RMs面临两大主要挑战。首先，自举困境的根源在于，高质量的训练数据依赖于已经非常强大的VL模型，这形成了一个自我强化的循环，进一步加剧了现有偏见。其次，当VL模型生成错误的视觉属性时，模态偏见和负例放大问题随之而来，导致偏好数据出现偏差，进而误导训练。针对这些问题，我们提出了一种结合视觉专家、链式思维（CoT）推理和基于边界的拒绝采样的迭代训练框架。我们的方法能够优化偏好数据集，增强结构化反馈，并通过迭代训练提升推理能力。在VL-RM基准测试中的实验结果表明，我们的方法在幻觉检测和多模态推理方面表现出色，进一步推动了强化学习在VL模型对齐中的应用。


> Reinforcement Fine-Tuning (RFT) with verifiable rewards has advanced large language models but remains underexplored for Vision-Language (VL) models. The Vision-Language Reward Model (VL-RM) is key to aligning VL models by providing structured feedback, yet training effective VL-RMs faces two major challenges. First, the bootstrapping dilemma arises as high-quality training data depends on already strong VL models, creating a cycle where self-generated supervision reinforces existing biases. Second, modality bias and negative example amplification occur when VL models hallucinate incorrect visual attributes, leading to flawed preference data that further misguides training. To address these issues, we propose an iterative training framework leveraging vision experts, Chain-of-Thought (CoT) rationales, and Margin-based Rejection Sampling. Our approach refines preference datasets, enhances structured critiques, and iteratively improves reasoning. Experiments across VL-RM benchmarks demonstrate superior performance in hallucination detection and multimodal reasoning, advancing VL model alignment with reinforcement learning.

[Arxiv](https://arxiv.org/abs/2506.13888)