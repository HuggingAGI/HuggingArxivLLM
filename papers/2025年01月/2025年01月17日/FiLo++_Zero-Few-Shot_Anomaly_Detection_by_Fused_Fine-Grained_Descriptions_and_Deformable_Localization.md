# FiLo++: 融合细粒度描述与可变形定位，实现零-shot/少-shot异常检测

发布时间：2025年01月17日

`LLM应用

理由：这篇论文主要讨论了如何利用大型语言模型（LLM）来生成异常描述，并结合其他技术（如视觉基础模型）来改进异常检测方法。虽然论文涉及多模态模型和视觉基础模型，但其核心创新点在于利用LLM生成更准确的任务特定文本描述，并将其应用于异常检测任务中。因此，这篇论文应归类为“LLM应用”。` `异常检测` `计算机视觉`

> FiLo++: Zero-/Few-Shot Anomaly Detection by Fused Fine-Grained Descriptions and Deformable Localization

# 摘要

> 异常检测方法通常需要大量目标类的正常样本进行训练，这限制了其在需要快速适应的场景（如冷启动）中的适用性。零-shot 和少-shot 异常检测无需预先获取目标类的标记样本，因此成为一个极具潜力的研究方向。现有的零-shot 和少-shot 方法通常依赖强大的多模态模型，通过图像-文本相似性比较来检测和定位异常。然而，这些方法的手工通用描述难以捕捉不同对象中可能出现的多样化异常，而简单的图像-文本匹配在定位不同形状和大小的异常区域时也常常力不从心。为解决这些问题，本文提出了 FiLo++ 方法，包含两个关键组件。第一个组件是融合细粒度描述（FusDes），它利用大型语言模型为每个对象类别生成异常描述，结合固定和可学习的提示模板，并采用运行时提示过滤方法，生成更准确且任务特定的文本描述。第二个组件是可变形定位（DefLoc），它将视觉基础模型 Grounding DINO 与位置增强的文本描述和多尺度可变形跨模态交互（MDCI）模块相结合，能够准确定位各种形状和大小的异常。此外，我们还设计了一种位置增强的补丁匹配方法，以提升少-shot 异常检测的性能。在多个数据集上的实验表明，FiLo++ 相比现有方法实现了显著的性能提升。代码将在 https://github.com/CASIA-IVA-Lab/FiLo 上提供。

> Anomaly detection methods typically require extensive normal samples from the target class for training, limiting their applicability in scenarios that require rapid adaptation, such as cold start. Zero-shot and few-shot anomaly detection do not require labeled samples from the target class in advance, making them a promising research direction. Existing zero-shot and few-shot approaches often leverage powerful multimodal models to detect and localize anomalies by comparing image-text similarity. However, their handcrafted generic descriptions fail to capture the diverse range of anomalies that may emerge in different objects, and simple patch-level image-text matching often struggles to localize anomalous regions of varying shapes and sizes. To address these issues, this paper proposes the FiLo++ method, which consists of two key components. The first component, Fused Fine-Grained Descriptions (FusDes), utilizes large language models to generate anomaly descriptions for each object category, combines both fixed and learnable prompt templates and applies a runtime prompt filtering method, producing more accurate and task-specific textual descriptions. The second component, Deformable Localization (DefLoc), integrates the vision foundation model Grounding DINO with position-enhanced text descriptions and a Multi-scale Deformable Cross-modal Interaction (MDCI) module, enabling accurate localization of anomalies with various shapes and sizes. In addition, we design a position-enhanced patch matching approach to improve few-shot anomaly detection performance. Experiments on multiple datasets demonstrate that FiLo++ achieves significant performance improvements compared with existing methods. Code will be available at https://github.com/CASIA-IVA-Lab/FiLo.

[Arxiv](https://arxiv.org/abs/2501.10067)