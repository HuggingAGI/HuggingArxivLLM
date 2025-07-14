# DatasetAgent：一个从真实世界图像自动构建数据集的多智能体系统

发布时间：2025年07月11日

`Agent

理由：这篇论文主要讨论了构建图像数据集的自动化方法，通过一个多智能体协作系统（DatasetAgent）实现。该系统由四个配备多模态大型语言模型（MLLMs）的智能体组成，其核心创新点在于多智能体的协作机制和系统设计，而非专注于LLM的应用或理论。因此，它更符合“Agent”类别，侧重于智能体的协作和应用。` `计算机视觉`

> DatasetAgent: A Novel Multi-Agent System for Auto-Constructing Datasets from Real-World Images

# 摘要

> 众所周知，构建图像数据集通常依赖于耗时且低效的手动收集与标注。大型模型通过数据生成提供了解决方案，但与人工智能够生成的数据相比，现实世界数据更具价值，尤其是在图像数据集构建方面。为此，我们提出了一种从现实世界图像中自动构建数据集的新方法——DatasetAgent，该方法由一个多智能体协作系统实现。通过协调四个配备多模态大型语言模型（MLLMs）的智能体，以及一个图像优化工具包，DatasetAgent能够根据用户需求构建高质量图像数据集。特别地，我们在多种开源数据集上进行了两类实验：扩展现有数据集与从零创建新数据集。结果表明，DatasetAgent构建的图像数据集可用于训练多种视觉模型，包括图像分类、目标检测和图像分割任务。

> Common knowledge indicates that the process of constructing image datasets usually depends on the time-intensive and inefficient method of manual collection and annotation. Large models offer a solution via data generation. Nonetheless, real-world data are obviously more valuable comparing to artificially intelligence generated data, particularly in constructing image datasets. For this reason, we propose a novel method for auto-constructing datasets from real-world images by a multiagent collaborative system, named as DatasetAgent. By coordinating four different agents equipped with Multi-modal Large Language Models (MLLMs), as well as a tool package for image optimization, DatasetAgent is able to construct high-quality image datasets according to user-specified requirements. In particular, two types of experiments are conducted, including expanding existing datasets and creating new ones from scratch, on a variety of open-source datasets. In both cases, multiple image datasets constructed by DatasetAgent are used to train various vision models for image classification, object detection, and image segmentation.

[Arxiv](https://arxiv.org/abs/2507.08648)