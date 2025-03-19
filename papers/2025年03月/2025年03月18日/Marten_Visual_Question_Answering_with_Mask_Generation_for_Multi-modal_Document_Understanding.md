# Marten：结合视觉问答与掩码生成的多模态文档理解

发布时间：2025年03月18日

`LLM应用` `文档处理` `信息处理`

> Marten: Visual Question Answering with Mask Generation for Multi-modal Document Understanding

# 摘要

> 多模态大型语言模型（MLLMs）为文档理解开辟了新天地，它们赋予了大型语言模型视觉理解的能力。然而，如何设计一个适合文档级MLLMs的图像-文本预训练任务，以实现视觉与语言模态的高效融合，仍是当前研究中的空白。本研究提出了一种创新的视觉-语言对齐方法，将这一核心问题转化为视觉问答与掩码生成（VQAMask）任务，同步优化基于VQA的文本解析和掩码生成两大环节。其中，文本解析任务让模型在语义层面实现图像与文本的自然对齐，而掩码生成任务则通过引入额外的掩码生成器（仅用于训练阶段），确保图像中的视觉文本与对应图像区域在空间感知层面上的精准对齐。这种双重优化机制不仅有效防止了模型在解析视觉文本时产生幻觉，还显著提升了空间感知特征表示的学习效果。为支持这一创新的VQAMask任务，我们构建了一个完整的图像-掩码生成流水线，并推出了包含600万数据的大型数据集（MTMask6M）。实验证明，引入这一掩码生成任务显著提升了文档级理解的性能。基于VQAMask，我们推出了Marten——一款专为文档级理解优化的高效训练多模态大型语言模型。在一系列实验中，Marten在文档为中心的任务中表现卓越，显著超越了现有8B-MLLMs的性能。相关代码和数据集已开源，访问地址为https://github.com/PriNing/Marten。

> Multi-modal Large Language Models (MLLMs) have introduced a novel dimension to document understanding, i.e., they endow large language models with visual comprehension capabilities; however, how to design a suitable image-text pre-training task for bridging the visual and language modality in document-level MLLMs remains underexplored. In this study, we introduce a novel visual-language alignment method that casts the key issue as a Visual Question Answering with Mask generation (VQAMask) task, optimizing two tasks simultaneously: VQA-based text parsing and mask generation. The former allows the model to implicitly align images and text at the semantic level. The latter introduces an additional mask generator (discarded during inference) to explicitly ensure alignment between visual texts within images and their corresponding image regions at a spatially-aware level. Together, they can prevent model hallucinations when parsing visual text and effectively promote spatially-aware feature representation learning. To support the proposed VQAMask task, we construct a comprehensive image-mask generation pipeline and provide a large-scale dataset with 6M data (MTMask6M). Subsequently, we demonstrate that introducing the proposed mask generation task yields competitive document-level understanding performance. Leveraging the proposed VQAMask, we introduce Marten, a training-efficient MLLM tailored for document-level understanding. Extensive experiments show that our Marten consistently achieves significant improvements among 8B-MLLMs in document-centric tasks. Code and datasets are available at https://github.com/PriNing/Marten.

[Arxiv](https://arxiv.org/abs/2503.14140)