# DriveMM：自动驾驶的一体化大型多模态模型

发布时间：2024年12月10日

`LLM应用` `自动驾驶` `多模态模型`

> DriveMM: All-in-One Large Multimodal Model for Autonomous Driving

# 摘要

> 大型多模态模型（LMMs）借助大型语言模型，在自动驾驶（AD）领域展现出非凡的理解与阐释能力。然而，当下数据驱动的自动驾驶方式通常聚焦于单个数据集和特定任务，忽视了其整体性能和泛化能力。为填补这些空缺，我们推出了 DriveMM，这是一款通用的大型多模态模型，能够处理诸如图像和多视角视频等多样的数据输入，同时执行包括感知、预测和规划在内的广泛自动驾驶任务。起初，该模型进行课程预训练，以处理各类视觉信号并完成基本的视觉理解与感知任务。接着，我们扩充并规范各种与自动驾驶相关的数据集来对模型进行微调，由此打造出一个用于自动驾驶的一体化 LMM。为评估其通用能力和泛化能力，我们在六个公共基准上展开评估，并在一个未曾见过的数据集上进行零样本迁移，DriveMM 在所有任务中均取得了顶尖水平的表现。我们期望 DriveMM 能成为未来现实世界中端到端自动驾驶应用的理想解决方案。

> Large Multimodal Models (LMMs) have demonstrated exceptional comprehension and interpretation capabilities in Autonomous Driving (AD) by incorporating large language models. Despite the advancements, current data-driven AD approaches tend to concentrate on a single dataset and specific tasks, neglecting their overall capabilities and ability to generalize. To bridge these gaps, we propose DriveMM, a general large multimodal model designed to process diverse data inputs, such as images and multi-view videos, while performing a broad spectrum of AD tasks, including perception, prediction, and planning. Initially, the model undergoes curriculum pre-training to process varied visual signals and perform basic visual comprehension and perception tasks. Subsequently, we augment and standardize various AD-related datasets to fine-tune the model, resulting in an all-in-one LMM for autonomous driving. To assess the general capabilities and generalization ability, we conduct evaluations on six public benchmarks and undertake zero-shot transfer on an unseen dataset, where DriveMM achieves state-of-the-art performance across all tasks. We hope DriveMM as a promising solution for future end-toend autonomous driving applications in the real world.

[Arxiv](https://arxiv.org/abs/2412.07689)