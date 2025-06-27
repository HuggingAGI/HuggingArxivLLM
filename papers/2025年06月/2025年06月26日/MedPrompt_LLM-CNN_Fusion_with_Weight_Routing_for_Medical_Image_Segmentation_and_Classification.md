# MedPrompt：LLM 与 CNN 的权重路由融合方法，应用于医学图像分割与分类任务

发布时间：2025年06月26日

`LLM应用` `医学图像分析` `医学影像`

> MedPrompt: LLM-CNN Fusion with Weight Routing for Medical Image Segmentation and Classification

# 摘要

> 现有的医学图像分析系统多为任务定制化设计，需为分类与分割分别训练独立模型，且难以支持灵活的用户自定义工作流程。为应对这些挑战，我们推出了MedPrompt——一个创新性框架，融合了基于少量样本提示的大语言模型（Llama-4-17B）进行高层任务规划，以及模块化卷积神经网络（DeepFusionLab）负责底层图像处理。该系统通过大语言模型解析用户指令并生成结构化输出，实现任务特定预训练权重的动态路由。这种智能路由机制避免了新增任务时对整个框架的重新训练，仅需补充任务特定权重，显著提升了系统的扩展性和部署效率。我们在涵盖5种成像模态的19个公开数据集、12项任务上对MedPrompt进行了全面评估。结果显示，该系统在提示驱动指令的解释与执行上达到了97%的端到端准确率，平均推理延迟仅2.5秒，可满足近实时应用需求。DeepFusionLab在医学图像分割与分类任务中表现尤为出色，例如肺部分割Dice值达0.9856，结核病分类F1值达0.9744。总体而言，MedPrompt通过整合大语言模型的可解释性与模块化卷积神经网络的高效处理能力，开创了一种全新的、可扩展的提示驱动医学影像分析范式。

> Current medical image analysis systems are typically task-specific, requiring separate models for classification and segmentation, and lack the flexibility to support user-defined workflows. To address these challenges, we introduce MedPrompt, a unified framework that combines a few-shot prompted Large Language Model (Llama-4-17B) for high-level task planning with a modular Convolutional Neural Network (DeepFusionLab) for low-level image processing. The LLM interprets user instructions and generates structured output to dynamically route task-specific pretrained weights. This weight routing approach avoids retraining the entire framework when adding new tasks-only task-specific weights are required, enhancing scalability and deployment. We evaluated MedPrompt across 19 public datasets, covering 12 tasks spanning 5 imaging modalities. The system achieves a 97% end-to-end correctness in interpreting and executing prompt-driven instructions, with an average inference latency of 2.5 seconds, making it suitable for near real-time applications. DeepFusionLab achieves competitive segmentation accuracy (e.g., Dice 0.9856 on lungs) and strong classification performance (F1 0.9744 on tuberculosis). Overall, MedPrompt enables scalable, prompt-driven medical imaging by combining the interpretability of LLMs with the efficiency of modular CNNs.

[Arxiv](https://arxiv.org/abs/2506.21199)