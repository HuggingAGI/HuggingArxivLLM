# PhysID：从单视图图像中构建基于物理的交互动力学

发布时间：2025年06月21日

`LLM应用` `计算机视觉` `增强现实/虚拟现实`

> PhysID: Physics-based Interactive Dynamics from a Single-view Image

# 摘要

> # 摘要
将静态图像转化为交互式体验一直是计算机视觉领域的难题。解决这一难题有望通过互动应用及增强现实/虚拟现实 (AR/VR) 提升移动用户体验。当前方法主要通过预先录制的视频响应或要求多视图图像输入来实现目标。本文提出 PhysID，利用大型生成模型进行 3D 网格生成和物理属性预测，从单一视图图像中简化了基于物理的交互式动力学创建。这显著降低了 3D 建模和固有属性校准等工程密集型任务的专业知识需求，使流程能够以最少人工干预扩展。我们集成了一个基于物理的实时渲染引擎，支持用户互动并实现物理上合理的实时渲染。PhysID 在移动设备上的交互式动力学方面实现了重大突破，提供实时、非确定性互动体验和用户个性化设置，同时保持高效设备内存使用。实验评估了多种多模态大型语言模型 (MLLMs) 的零样本能力和 3D 重建模型性能。结果展示了端到端框架内所有模块的协同工作，证明了其有效性。


> Transforming static images into interactive experiences remains a challenging task in computer vision. Tackling this challenge holds the potential to elevate mobile user experiences, notably through interactive and AR/VR applications. Current approaches aim to achieve this either using pre-recorded video responses or requiring multi-view images as input. In this paper, we present PhysID, that streamlines the creation of physics-based interactive dynamics from a single-view image by leveraging large generative models for 3D mesh generation and physical property prediction. This significantly reduces the expertise required for engineering-intensive tasks like 3D modeling and intrinsic property calibration, enabling the process to be scaled with minimal manual intervention. We integrate an on-device physics-based engine for physically plausible real-time rendering with user interactions. PhysID represents a leap forward in mobile-based interactive dynamics, offering real-time, non-deterministic interactions and user-personalization with efficient on-device memory consumption. Experiments evaluate the zero-shot capabilities of various Multimodal Large Language Models (MLLMs) on diverse tasks and the performance of 3D reconstruction models. These results demonstrate the cohesive functioning of all modules within the end-to-end framework, contributing to its effectiveness.

[Arxiv](https://arxiv.org/abs/2506.17746)