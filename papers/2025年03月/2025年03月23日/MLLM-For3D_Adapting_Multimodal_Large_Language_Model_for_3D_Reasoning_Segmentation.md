# MLLM-For3D：多模态大型语言模型在3D推理分割中的应用

发布时间：2025年03月23日

`LLM应用` `计算机视觉` `人工智能`

> MLLM-For3D: Adapting Multimodal Large Language Model for 3D Reasoning Segmentation

# 摘要

> 推理分割旨在根据人类意图和空间推理在复杂场景中分割目标物体。尽管多模态大型语言模型（MLLMs）在2D图像推理分割方面表现出色，但将其能力扩展到3D场景仍是一个未充分探索的领域。本文提出了MLLM-For3D，一个简单而有效的框架，用于将2D MLLMs的知识迁移到3D场景理解中。

具体而言，我们利用MLLMs生成多视图伪分割掩膜及其对应的文本嵌入，随后将2D掩膜反投影至3D空间并与文本嵌入对齐。主要挑战在于缺乏3D上下文以及多视图之间空间一致性不足，这导致模型产生不存在的物体或无法一致地定位目标物体。使用这些不相关的物体训练3D模型会导致性能下降。

为了解决这一问题，我们引入了一种空间一致性策略，以确保分割掩膜在3D空间中保持一致，从而有效捕捉场景的几何结构。此外，我们开发了一种Token-for-Query方法，用于多模态语义对齐，使模型能够跨不同视图一致地识别同一物体。

在多个具有挑战性的室内场景基准上的广泛评估表明，即使没有标注的3D训练数据，MLLM-For3D也优于现有的3D推理分割方法，能够有效解释用户意图、理解3D场景并推理空间关系。

> Reasoning segmentation aims to segment target objects in complex scenes based on human intent and spatial reasoning. While recent multimodal large language models (MLLMs) have demonstrated impressive 2D image reasoning segmentation, adapting these capabilities to 3D scenes remains underexplored. In this paper, we introduce MLLM-For3D, a simple yet effective framework that transfers knowledge from 2D MLLMs to 3D scene understanding. Specifically, we utilize MLLMs to generate multi-view pseudo segmentation masks and corresponding text embeddings, then unproject 2D masks into 3D space and align them with the text embeddings. The primary challenge lies in the absence of 3D context and spatial consistency across multiple views, causing the model to hallucinate objects that do not exist and fail to target objects consistently. Training the 3D model with such irrelevant objects leads to performance degradation. To address this, we introduce a spatial consistency strategy to enforce that segmentation masks remain coherent in the 3D space, effectively capturing the geometry of the scene. Moreover, we develop a Token-for-Query approach for multimodal semantic alignment, enabling consistent identification of the same object across different views. Extensive evaluations on various challenging indoor scene benchmarks demonstrate that, even without any labeled 3D training data, MLLM-For3D outperforms existing 3D reasoning segmentation methods, effectively interpreting user intent, understanding 3D scenes, and reasoning about spatial relationships.

[Arxiv](https://arxiv.org/abs/2503.18135)