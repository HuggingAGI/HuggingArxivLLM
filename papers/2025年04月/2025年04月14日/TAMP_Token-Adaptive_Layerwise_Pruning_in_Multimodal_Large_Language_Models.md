# TAMP：面向多模态大语言模型的令牌自适应分层剪枝方法

发布时间：2025年04月14日

`其他` `多模态` `视觉-语言`

> TAMP: Token-Adaptive Layerwise Pruning in Multimodal Large Language Models

# 摘要

> 多模态大型语言模型（MLLMs）在处理多样化多模态数据和任务时表现出色，但同时也带来了模型规模的显著增长。传统后训练剪枝方法在单模态模型中效果良好，但在多模态模型中应用时往往效果有限。通过深入分析，我们发现传统方法未能充分考虑多模态模型中各层和各模态间独特的令牌属性。基于这一发现，我们提出了TAMP，一个专为多模态模型设计的简洁而高效的剪枝框架。该框架包含两个核心组件：（1）多样性感知稀疏性，根据多模态输出令牌间的多样性动态调整每层的稀疏比，保留高多样性层的更多参数；（2）自适应多模态输入激活，利用注意力分数识别具有代表性的多模态输入令牌，以指导非结构化权重剪枝。我们在两种先进的多模态模型上验证了我们的方法：专为视觉-语言任务设计的LLaVA-NeXT，以及能够处理音频、视觉和语言模态的VideoLLaMA2。在多种多模态评估基准上的实证实验表明，我们方法的每一部分都显著优于现有的剪枝技术。

> Multimodal Large Language Models (MLLMs) have shown remarkable versatility in understanding diverse multimodal data and tasks. However, these capabilities come with an increased model scale. While post-training pruning reduces model size in unimodal models, its application to MLLMs often yields limited success. Our analysis discovers that conventional methods fail to account for the unique token attributes across layers and modalities inherent to MLLMs. Inspired by this observation, we propose TAMP, a simple yet effective pruning framework tailored for MLLMs, featuring two key components: (1) Diversity-Aware Sparsity, which adjusts sparsity ratio per layer based on diversities among multimodal output tokens, preserving more parameters in high-diversity layers; and (2) Adaptive Multimodal Input Activation, which identifies representative multimodal input tokens using attention scores to guide unstructured weight pruning. We validate our method on two state-of-the-art MLLMs: LLaVA-NeXT, designed for vision-language tasks, and VideoLLaMA2, capable of processing audio, visual, and language modalities. Empirical experiments across various multimodal evaluation benchmarks demonstrate that each component of our approach substantially outperforms existing pruning techniques.

[Arxiv](https://arxiv.org/abs/2504.09897)