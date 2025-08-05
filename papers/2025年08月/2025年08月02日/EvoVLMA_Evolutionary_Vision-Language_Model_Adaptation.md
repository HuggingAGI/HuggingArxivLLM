# # EvoVLMA: Evolutionary Vision-Language Model Adaptation
# EvoVLMA：进化视觉语言模型的适配方法

发布时间：2025年08月02日

`LLM应用

分类理由：这篇论文探讨了如何利用大语言模型（LLMs）在代码生成领域的最新进展，来自动搜索无需训练的视觉语言模型（VLMs）适应算法。论文提出了一种进化视觉语言模型适应（EvoVLMA）方法，通过LLM辅助的两阶段进化算法，自动优化VLMs的适应过程。这属于LLM的应用研究，即利用LLMs的能力来解决其他领域的问题。` `计算机视觉` `软件工程`

> EvoVLMA: Evolutionary Vision-Language Model Adaptation

# 摘要

> 预训练的视觉语言模型（VLMs）已被成功应用于各种计算机视觉任务（如少量样本识别），通过模型适应方法（如提示微调和适配器）实现。然而，现有的适应方法由人工设计，耗时且需要大量经验。受到大语言模型（LLMs）在代码生成领域的最新进展启发，我们提出了一种进化视觉语言模型适应（EvoVLMA）方法，用于自动搜索无需训练的有效VLM适应算法。我们发现特征选择和对数几率计算是训练-free VLM适应中的关键函数，并提出了一种基于LLM辅助的两阶段进化算法，通过分治策略按顺序优化这些部分，有效应对搜索空间庞大的挑战。此外，为了提高搜索过程的稳定性和效率，我们提出了低精度代码转换、基于网络的代码执行和过程监控，构建了一个高效自动化的算法设计系统。大量实验表明，EvoVLMA发现的算法在性能上优于之前人工设计的算法。具体而言，在8-shot图像分类任务中，经典的APE算法的识别精度提升了1.91个百分点。这项研究为预训练多模态模型适应算法的自动化优化开辟了新的可能性。代码可在以下链接获取：https://github.com/kding1225/EvoVLMA

> Pre-trained Vision-Language Models (VLMs) have been exploited in various Computer Vision tasks (e.g., few-shot recognition) via model adaptation, such as prompt tuning and adapters. However, existing adaptation methods are designed by human experts, requiring significant time cost and experience. Inspired by recent advances in Large Language Models (LLMs) based code generation, we propose an Evolutionary Vision-Language Model Adaptation (EvoVLMA) method to automatically search training-free efficient adaptation algorithms for VLMs. We recognize feature selection and logits computation as the key functions in training-free VLM adaptation, and propose a two-stage LLM-assisted evolutionary algorithm for optimizing these parts in a sequential manner, effectively addressing the challenge posed by the expansive search space through a divide-and-conquer strategy. Besides, to enhance the stability and efficiency of searching process, we propose low-precision code conversion, web based code execution and process monitoring, leading to a highly effective automatic algorithm design system. Extensive experiments demonstrate that the algorithms found by EvoVLMA can obtain promising results compared to previous manually-designed ones. More specifically, in the 8-shot image classification setting, the classical APE algorithm can be improved by 1.91 points in recognition accuracy. This research opens new possibilities for automating the optimization of adaptation algorithms of pre-trained multimodal models. Code is available at: https://github.com/kding1225/EvoVLMA

[Arxiv](https://arxiv.org/abs/2508.01558)