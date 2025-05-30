# cadrille：多模态 CAD 建模与在线强化学习结合的创新框架

发布时间：2025年05月28日

`LLM应用`

> cadrille: Multi-modal CAD Reconstruction with Online Reinforcement Learning

# 摘要

> 计算机辅助设计（CAD）在工程和制造领域发挥着关键作用，它让精确且可编辑的3D模型创建成为现实。通过将传感器数据或用户提供的数据作为CAD重建的输入，我们可以让更多人便捷地使用设计工具。然而，现有方法通常局限于单一输入模式，如点云、图像或文本，这限制了它们的适用性和稳定性。借助视觉语言模型（VLM）的最新进展，我们提出了一种多模态CAD重建模型，能够同时处理这三种输入模式。受大型语言模型（LLM）训练范式的启发，我们采用了两阶段流水线：首先在大规模程序生成的数据上进行监督微调（SFT），然后使用在线反馈进行强化学习（RL）微调。此外，我们是首个探索将RL微调应用于CAD任务的团队，证明在线RL算法如组相对偏好优化（GRPO）优于离线方法。在DeepCAD基准测试中，我们的SFT模型在所有三种输入模式上均优于现有单模态方法。更重要的是，经过RL微调后，CadRille在三个具有挑战性的数据集上达到了新的技术水平，包括一个真实世界的数据集。

> Computer-Aided Design (CAD) plays a central role in engineering and manufacturing, making it possible to create precise and editable 3D models. Using a variety of sensor or user-provided data as inputs for CAD reconstruction can democratize access to design applications. However, existing methods typically focus on a single input modality, such as point clouds, images, or text, which limits their generalizability and robustness. Leveraging recent advances in vision-language models (VLM), we propose a multi-modal CAD reconstruction model that simultaneously processes all three input modalities. Inspired by large language model (LLM) training paradigms, we adopt a two-stage pipeline: supervised fine-tuning (SFT) on large-scale procedurally generated data, followed by reinforcement learning (RL) fine-tuning using online feedback, obtained programatically. Furthermore, we are the first to explore RL fine-tuning of LLMs for CAD tasks demonstrating that online RL algorithms such as Group Relative Preference Optimization (GRPO) outperform offline alternatives. In the DeepCAD benchmark, our SFT model outperforms existing single-modal approaches in all three input modalities simultaneously. More importantly, after RL fine-tuning, cadrille sets new state-of-the-art on three challenging datasets, including a real-world one.

[Arxiv](https://arxiv.org/abs/2505.22914)