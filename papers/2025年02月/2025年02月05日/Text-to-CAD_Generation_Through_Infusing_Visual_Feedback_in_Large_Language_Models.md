# 通过在大语言模型中融入视觉反馈实现文本到CAD的生成

发布时间：2025年02月05日

`LLM应用

理由：这篇论文主要讨论了如何利用大型语言模型（LLMs）来改进计算机辅助设计（CAD）模型的生成过程。具体来说，论文提出了一个名为CADFusion的框架，该框架通过交替进行顺序学习（SL）阶段和视觉反馈（VF）阶段来训练LLMs，使其能够生成逻辑上一致的参数序列，并评估渲染的视觉对象。这种方法直接应用了LLMs来解决实际问题，属于LLM应用的范畴。` `计算机辅助设计` `制造业`

> Text-to-CAD Generation Through Infusing Visual Feedback in Large Language Models

# 摘要

> 创建计算机辅助设计（CAD）模型需要深厚的专业知识和大量努力。文本到CAD技术，即将文本描述转化为CAD参数序列，对于简化这一过程至关重要。最近的研究利用真实参数序列（称为顺序信号）作为监督来实现这一目标。然而，CAD模型本质上是多模态的，包含参数序列和相应的渲染视觉对象。此外，从参数序列到视觉对象的渲染过程是多对一的。因此，顺序信号和视觉信号对于有效训练都至关重要。在本研究中，我们提出了CADFusion框架，该框架以大型语言模型（LLMs）为核心，并在两个训练阶段之间交替：顺序学习（SL）阶段和视觉反馈（VF）阶段。在SL阶段，我们使用真实参数序列训练LLMs，使其能够生成逻辑上一致的参数序列。在VF阶段，我们奖励那些渲染成视觉上更受青睐的对象的参数序列，并惩罚那些不这样做的序列，使LLMs能够学习如何感知和评估渲染的视觉对象。这两个阶段在整个训练过程中交替进行，确保平衡学习并保留两种信号的好处。实验表明，CADFusion在质量和数量上都显著提高了性能。

> Creating Computer-Aided Design (CAD) models requires significant expertise and effort. Text-to-CAD, which converts textual descriptions into CAD parametric sequences, is crucial in streamlining this process. Recent studies have utilized ground-truth parametric sequences, known as sequential signals, as supervision to achieve this goal. However, CAD models are inherently multimodal, comprising parametric sequences and corresponding rendered visual objects. Besides,the rendering process from parametric sequences to visual objects is many-to-one. Therefore, both sequential and visual signals are critical for effective training. In this work, we introduce CADFusion, a framework that uses Large Language Models (LLMs) as the backbone and alternates between two training stages: the sequential learning (SL) stage and the visual feedback (VF) stage. In the SL stage, we train LLMs using ground-truth parametric sequences, enabling the generation of logically coherent parametric sequences. In the VF stage, we reward parametric sequences that render into visually preferred objects and penalize those that do not, allowing LLMs to learn how rendered visual objects are perceived and evaluated. These two stages alternate throughout the training, ensuring balanced learning and preserving benefits of both signals. Experiments demonstrate that CADFusion significantly improves performance, both qualitatively and quantitatively.

[Arxiv](https://arxiv.org/abs/2501.19054)