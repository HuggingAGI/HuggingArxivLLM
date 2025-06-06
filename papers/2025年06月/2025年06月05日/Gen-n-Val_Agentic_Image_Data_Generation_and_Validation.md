# Gen-n-Val：图像数据生成与验证的智能体方法

发布时间：2025年06月05日

`LLM应用

理由：这篇论文主要探讨了如何利用大型语言模型（LLMs）和视觉大型语言模型（VLLMs）来解决计算机视觉任务中的数据生成问题。虽然提到了智能体（Agents）的概念，但这些智能体是作为数据生成框架的一部分，而不是研究智能体本身的行为或理论。因此，这篇论文更偏向于LLM的应用，特别是展示了LLMs在数据生成和优化中的实际应用。` `计算机视觉`

> Gen-n-Val: Agentic Image Data Generation and Validation

# 摘要

> 大型语言模型（LLMs）和视觉大型语言模型（VLLMs）在各类任务中展现出卓越性能，但在目标检测和实例分割等计算机视觉任务中，数据稀缺性和标签噪声仍是主要挑战。为解决这一问题，我们提出了Gen-n-Val，一个创新的智能体数据生成框架。该框架结合层扩散（Layer Diffusion，LD）、LLMs和VLLMs，生成高质量的单目标掩膜和多样化背景。Gen-n-Val由两个智能体组成：（1）LD提示智能体，一个LLM，优化LD的提示词，生成高质量的前景实例图像和分割掩膜，确保单目标合成数据的精确性和背景的干净度。（2）数据验证智能体，一个VLLM，用于筛选低质量的合成实例图像。两个智能体的提示词均通过TextGrad优化。此外，我们使用图像 harmonization 技术将多个实例整合到同一场景中。相比MosaicFusion等现有方法，Gen-n-Val将无效合成数据比例从50%降至7%，并在COCO实例分割任务中使用YOLOv9c和YOLO11m时，稀有类别mAP提升了1%。在开放词汇目标检测基准测试中，使用YOLO11m时，Gen-n-Val相较于YOLO-Worldv2-M实现了7.1%的mAP提升。此外，Gen-n-Val显著提升了YOLOv9和YOLO11系列模型在实例分割和目标检测任务中的性能。

> Recently, Large Language Models (LLMs) and Vision Large Language Models (VLLMs) have demonstrated impressive performance as agents across various tasks while data scarcity and label noise remain significant challenges in computer vision tasks, such as object detection and instance segmentation. A common solution for resolving these issues is to generate synthetic data. However, current synthetic data generation methods struggle with issues, such as multiple objects per mask, inaccurate segmentation, and incorrect category labels, limiting their effectiveness. To address these issues, we introduce Gen-n-Val, a novel agentic data generation framework that leverages Layer Diffusion (LD), LLMs, and VLLMs to produce high-quality, single-object masks and diverse backgrounds. Gen-n-Val consists of two agents: (1) The LD prompt agent, an LLM, optimizes prompts for LD to generate high-quality foreground instance images and segmentation masks. These optimized prompts ensure the generation of single-object synthetic data with precise instance masks and clean backgrounds. (2) The data validation agent, a VLLM, which filters out low-quality synthetic instance images. The system prompts for both agents are refined through TextGrad. Additionally, we use image harmonization to combine multiple instances within scenes. Compared to state-of-the-art synthetic data approaches like MosaicFusion, our approach reduces invalid synthetic data from 50% to 7% and improves performance by 1% mAP on rare classes in COCO instance segmentation with YOLOv9c and YOLO11m. Furthermore, Gen-n-Val shows significant improvements (7. 1% mAP) over YOLO-Worldv2-M in open-vocabulary object detection benchmarks with YOLO11m. Moreover, Gen-n-Val improves the performance of YOLOv9 and YOLO11 families in instance segmentation and object detection.

[Arxiv](https://arxiv.org/abs/2506.04676)