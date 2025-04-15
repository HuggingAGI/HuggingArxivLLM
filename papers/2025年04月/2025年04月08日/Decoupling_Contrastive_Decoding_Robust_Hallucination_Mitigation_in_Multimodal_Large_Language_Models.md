# # 解耦对比解码：多模态大语言模型中的稳健幻觉缓解  
多模态大语言模型中的解耦对比解码与稳健幻觉缓解

发布时间：2025年04月08日

`LLM应用

理由：这篇论文主要探讨多模态大型语言模型（MLLMs）中的幻觉问题，并提出了一种新的方法（DCD）来解决这一问题。幻觉问题属于模型应用中的常见挑战，而提出的解耦对比解码方法旨在改进模型的应用效果，因此归类为LLM应用。` `人工智能`

> Decoupling Contrastive Decoding: Robust Hallucination Mitigation in Multimodal Large Language Models

# 摘要

> 多模态大型语言模型（MLLMs）在复杂多模态理解任务中表现优异，但其幻觉问题仍待解决，即生成的输出常与视觉或事实证据相悖。现有基于训练的方法如直接偏好优化（DPO）通过配对偏好数据抑制幻觉，但可能因似然位移而削弱通用推理能力。无训练方法如对比解码则通过从扭曲输入中减去估计的幻觉模式实现目标，但手工扰动（如图像加噪）往往难以准确捕捉真实幻觉模式。为克服现有方法的局限，我们提出了解耦对比解码（DCD），旨在实现稳健幻觉缓解并保持通用推理性能。DCD 解耦了偏好数据集中正负样本的学习，并分别训练正负图像投影。负投影隐式建模真实幻觉模式，使对比解码推理阶段实现视觉感知的负图像。通过避免成对优化，DCD 缓解似然位移并在无需手工降级的情况下实现稳健泛化。实验表明，DCD 在抑制幻觉的同时保留通用能力，效果优于手工对比解码方法。

> Although multimodal large language models (MLLMs) exhibit remarkable reasoning capabilities on complex multimodal understanding tasks, they still suffer from the notorious hallucination issue: generating outputs misaligned with obvious visual or factual evidence. Currently, training-based solutions, like direct preference optimization (DPO), leverage paired preference data to suppress hallucinations. However, they risk sacrificing general reasoning capabilities due to the likelihood displacement. Meanwhile, training-free solutions, like contrastive decoding, achieve this goal by subtracting the estimated hallucination pattern from a distorted input. Yet, these handcrafted perturbations (e.g., add noise to images) may poorly capture authentic hallucination patterns. To avoid these weaknesses of existing methods, and realize robust hallucination mitigation (i.e., maintaining general reasoning performance), we propose a novel framework: Decoupling Contrastive Decoding (DCD). Specifically, DCD decouples the learning of positive and negative samples in preference datasets, and trains separate positive and negative image projections within the MLLM. The negative projection implicitly models real hallucination patterns, which enables vision-aware negative images in the contrastive decoding inference stage. Our DCD alleviates likelihood displacement by avoiding pairwise optimization and generalizes robustly without handcrafted degradation. Extensive ablations across hallucination benchmarks and general reasoning tasks demonstrate the effectiveness of DCD, i.e., it matches DPO's hallucination suppression while preserving general capabilities and outperforms the handcrafted contrastive decoding methods.

[Arxiv](https://arxiv.org/abs/2504.08809)