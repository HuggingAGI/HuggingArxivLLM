# 利用大型视觉语言模型理解交通场景

发布时间：2025年01月28日

`LLM应用

**理由**：这篇论文主要讨论了大型视觉语言模型（LVLMs）在自动驾驶领域的应用，特别是如何利用这些模型进行场景理解和分类，以提升自动驾驶系统的跨领域可靠性。论文的核心是评估和验证LVLMs在实际数据集上的表现，并提出了一种可扩展的标注管道。因此，这篇论文属于**LLM应用**类别。` `自动驾驶` `城市交通`

> Scenario Understanding of Traffic Scenes Through Large Visual Language Models

# 摘要

> # 摘要
自动驾驶的深度学习模型（涵盖感知、规划与控制）依赖海量数据实现高性能，但其泛化能力常受限于特定领域的数据分布。因此，基于场景的样本分类成为提升跨领域可靠性的关键。手动标注虽有效，却耗时耗力，成为数据标注的瓶颈。大型视觉语言模型（LVLMs）通过上下文查询自动完成图像分析与分类，通常无需为新类别重新训练，提供了高效的解决方案。本研究评估了LVLMs（如GPT-4和LLaVA）在内部数据集和BDD100K上对城市交通场景的理解与分类能力，并提出了一种可扩展的标注管道，集成前沿模型，支持灵活部署于新数据集。结合定量指标与定性分析，我们验证了LVLMs理解城市交通场景的有效性，并凸显了其作为自动驾驶数据驱动进展的高效工具的潜力。

> Deep learning models for autonomous driving, encompassing perception, planning, and control, depend on vast datasets to achieve their high performance. However, their generalization often suffers due to domain-specific data distributions, making an effective scene-based categorization of samples necessary to improve their reliability across diverse domains. Manual captioning, though valuable, is both labor-intensive and time-consuming, creating a bottleneck in the data annotation process. Large Visual Language Models (LVLMs) present a compelling solution by automating image analysis and categorization through contextual queries, often without requiring retraining for new categories. In this study, we evaluate the capabilities of LVLMs, including GPT-4 and LLaVA, to understand and classify urban traffic scenes on both an in-house dataset and the BDD100K. We propose a scalable captioning pipeline that integrates state-of-the-art models, enabling a flexible deployment on new datasets. Our analysis, combining quantitative metrics with qualitative insights, demonstrates the effectiveness of LVLMs to understand urban traffic scenarios and highlights their potential as an efficient tool for data-driven advancements in autonomous driving.

[Arxiv](https://arxiv.org/abs/2501.17131)