# 基于推理增强的多模态大型语言模型的多功能病理协 pilot

发布时间：2025年07月23日

`LLM应用` `计算病理学` `AI医疗`

> A Versatile Pathology Co-pilot via Reasoning Enhanced Multimodal Large Language Model

# 摘要

> 多模态大型语言模型（MLLMs）在计算病理学领域展现出巨大潜力，为整合病理图像与语言上下文以实现全面诊断分析提供了前所未有的机遇。这些模型在自动化传统上需要病理学家专家解读的复杂任务方面展现出巨大潜力。然而，目前病理学中MLLM方法的推理能力受到显著限制，这主要归因于其对昂贵的链式思维注释的依赖。此外，现有方法仍局限于在感兴趣区域（ROI）级别的简单视觉问答（VQA）应用，未能涵盖诊断需求的全谱，如ROI分类、检测、分割、全幻灯片图像（WSI）分类以及临床实践中的VQA。

在本研究中，我们提出了SmartPath-R1，一种 versatile 的MLLM，能够同时处理ROI级别和WSI级别的任务，同时展现出强大的病理推理能力。我们的框架结合了尺度依赖的监督微调和任务感知的强化微调，通过利用MLLM内部的知识，规避了对链式思维监督的需求。此外，SmartPath-R1通过专家混合机制集成了多尺度和多任务分析，实现了对多样化任务的动态处理。我们整理了一个包含230万个ROI样本和18.8万个WSI样本的大型数据集用于训练和评估。在72项任务上的广泛实验验证了所提方法的有效性和优越性。这项工作朝着开发 versatile、推理增强的AI系统以实现精准病理学迈出了重要一步。

> Multimodal large language models (MLLMs) have emerged as powerful tools for computational pathology, offering unprecedented opportunities to integrate pathological images with language context for comprehensive diagnostic analysis. These models hold particular promise for automating complex tasks that traditionally require expert interpretation of pathologists. However, current MLLM approaches in pathology demonstrate significantly constrained reasoning capabilities, primarily due to their reliance on expensive chain-of-thought annotations. Additionally, existing methods remain limited to simplex application of visual question answering (VQA) at region-of-interest (ROI) level, failing to address the full spectrum of diagnostic needs such as ROI classification, detection, segmentation, whole-slide-image (WSI) classification and VQA in clinical practice. In this study, we present SmartPath-R1, a versatile MLLM capable of simultaneously addressing both ROI-level and WSI-level tasks while demonstrating robust pathological reasoning capability. Our framework combines scale-dependent supervised fine-tuning and task-aware reinforcement fine-tuning, which circumvents the requirement for chain-of-thought supervision by leveraging the intrinsic knowledge within MLLM. Furthermore, SmartPath-R1 integrates multiscale and multitask analysis through a mixture-of-experts mechanism, enabling dynamic processing for diverse tasks. We curate a large-scale dataset comprising 2.3M ROI samples and 188K WSI samples for training and evaluation. Extensive experiments across 72 tasks validate the effectiveness and superiority of the proposed approach. This work represents a significant step toward developing versatile, reasoning-enhanced AI systems for precision pathology.

[Arxiv](https://arxiv.org/abs/2507.17303)