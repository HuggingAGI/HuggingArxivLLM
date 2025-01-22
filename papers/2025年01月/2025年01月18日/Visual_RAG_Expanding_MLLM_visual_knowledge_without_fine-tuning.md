# Visual RAG: 无需微调，扩展多模态大语言模型的视觉知识

发布时间：2025年01月18日

`RAG

**理由：**
- 论文摘要中提到了一种新方法——Visual RAG，结合了多模态大型语言模型（MLLMs）的上下文学习能力与检索机制。
- RAG（Retrieval-Augmented Generation）是一种结合检索和生成的技术，通常用于增强模型的知识获取和生成能力。
- 本文提出的Visual RAG方法通过检索与查询最相关的示范示例，推动模型通过类比学习，这符合RAG的核心思想。
- 因此，这篇论文应归类为RAG。` `计算机视觉` `多模态学习`

> Visual RAG: Expanding MLLM visual knowledge without fine-tuning

# 摘要

> # 摘要
多模态大型语言模型（MLLMs）在跨视觉和文本模态的计算机视觉任务中表现出色，但其能力受限于预训练数据，更新需大量微调。近期研究探索了上下文学习（ICL）的应用，通过提供示范示例作为上下文，显著提升了MLLMs在多个任务中的表现，尤其是多-shot ICL相比少-shot ICL效果更佳。然而，依赖大量示范示例和MLLMs有限的上下文窗口仍是主要挑战。本文提出了一种新方法——Visual RAG，结合MLLMs的上下文学习能力与检索机制，通过精选与查询最相关的示范示例，推动模型通过类比学习。这种方法不仅使系统能够动态更新知识，无需微调，还大幅降低了计算成本，并将模型知识扩展到未训练的新视觉领域和任务。在多个领域和图像分类任务的最新技术中，对八个数据集的实验表明，Visual RAG相比最新的多-shot ICL技术，准确率接近甚至更高（平均提升约2%），同时示范示例数量大幅减少（平均仅约23%）。

> Multimodal Large Language Models (MLLMs) have achieved notable performance in computer vision tasks that require reasoning across visual and textual modalities, yet their capabilities are limited to their pre-trained data, requiring extensive fine-tuning for updates. Recent researches have explored the use of In-Context Learning (ICL) to overcome these challenges by providing a set of demonstrating examples as context to augment MLLMs performance in several tasks, showing that many-shot ICL leads to substantial improvements compared to few-shot ICL. However, the reliance on numerous demonstrating examples and the limited MLLMs context windows presents significant obstacles. This paper aims to address these challenges by introducing a novel approach, Visual RAG, that synergically combines the MLLMs capability to learn from the context, with a retrieval mechanism. The crux of this approach is to ensure to augment the MLLM knowledge by selecting only the most relevant demonstrating examples for the query, pushing it to learn by analogy. In this way, relying on the new information provided dynamically during inference time, the resulting system is not limited to the knowledge extracted from the training data, but can be updated rapidly and easily without fine-tuning. Furthermore, this greatly reduces the computational costs for improving the model image classification performance, and augments the model knowledge to new visual domains and tasks it was not trained for. Extensive experiments on eight different datasets in the state of the art spanning several domains and image classification tasks show that the proposed Visual RAG, compared to the most recent state of the art (i.e., many-shot ICL), is able to obtain an accuracy that is very close or even higher (approx. +2% improvement on average) while using a much smaller set of demonstrating examples (approx. only 23% on average).

[Arxiv](https://arxiv.org/abs/2501.10834)