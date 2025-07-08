# VectorLLM：通过多模态大语言模型实现结构化建筑轮廓的类人提取

发布时间：2025年07月07日

`LLM应用` `城市科学`

> VectorLLM: Human-like Extraction of Structured Building Contours vis Multimodal LLMs

# 摘要

> 自动提取遥感图像中的矢量化建筑轮廓在城市规划、人口估算和灾害评估中具有重要意义。然而，现有最先进的方法依赖于复杂的多阶段管道，包括像素分割、矢量化和多边形优化，这限制了其扩展性和实际应用性。受大型语言模型（LLMs）出色推理能力的启发，我们推出了VectorLLM——首个专为从遥感图像中提取常规建筑轮廓设计的多模态大型语言模型（MLLM）。与现有方法不同，VectorLLM通过模拟人工标注员的标注过程，直接进行建筑轮廓的角点回归。我们的架构由视觉基础主干、MLP连接器和一个LLM组成，并通过可学习的位置嵌入增强了空间理解能力。通过在WHU、WHU-Mix和CrowdAI数据集上全面探索包括预训练、监督微调和偏好优化在内的训练策略，VectorLLM在三个数据集上分别以5.6 AP、7.1 AP和13.6 AP显著超越了之前的最先进方法。值得注意的是，VectorLLM在飞机、水域和油罐等未见过的对象上表现出强大的零样本性能，凸显了其在统一建模多种遥感目标轮廓提取任务中的潜力。总体而言，这项工作为遥感中的矢量提取确立了新范式，利用LLMs的拓扑推理能力实现了高精度和卓越的泛化能力。所有代码和权重将公开发布以促进社区发展。

> Automatically extracting vectorized building contours from remote sensing imagery is crucial for urban planning, population estimation, and disaster assessment. Current state-of-the-art methods rely on complex multi-stage pipelines involving pixel segmentation, vectorization, and polygon refinement, which limits their scalability and real-world applicability. Inspired by the remarkable reasoning capabilities of Large Language Models (LLMs), we introduce VectorLLM, the first Multi-modal Large Language Model (MLLM) designed for regular building contour extraction from remote sensing images. Unlike existing approaches, VectorLLM performs corner-point by corner-point regression of building contours directly, mimicking human annotators' labeling process. Our architecture consists of a vision foundation backbone, an MLP connector, and an LLM, enhanced with learnable position embeddings to improve spatial understanding capability. Through comprehensive exploration of training strategies including pretraining, supervised fine-tuning, and preference optimization across WHU, WHU-Mix, and CrowdAI datasets, VectorLLM significantly outperformed the previous SOTA methods by 5.6 AP, 7.1 AP, 13.6 AP, respectively in the three datasets. Remarkably, VectorLLM exhibits strong zero-shot performance on unseen objects including aircraft, water bodies, and oil tanks, highlighting its potential for unified modeling of diverse remote sensing object contour extraction tasks. Overall, this work establishes a new paradigm for vector extraction in remote sensing, leveraging the topological reasoning capabilities of LLMs to achieve both high accuracy and exceptional generalization. All the codes and weights will be published for promoting community development.

[Arxiv](https://arxiv.org/abs/2507.04664)