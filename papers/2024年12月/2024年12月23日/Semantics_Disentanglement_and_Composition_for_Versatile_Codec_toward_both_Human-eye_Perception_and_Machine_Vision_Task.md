# 针对人眼感知和机器视觉任务的通用编解码器的语义解缠与组合

发布时间：2024年12月23日

`其他` `图像压缩` `机器视觉`

> Semantics Disentanglement and Composition for Versatile Codec toward both Human-eye Perception and Machine Vision Task

# 摘要

> 虽然已学习的图像压缩方法在人类视觉感知或机器视觉任务中成绩斐然，但通常只专长于一个领域。这一短板限制了它们在不同场景中的通用性和泛化能力，而且为适应新应用而重新训练的过程，在现实场景中增添了极大的复杂性和成本。在本研究中，我们推出了创新的语义解缠与组合通用编解码器（DISCOVER），以同步提升人眼感知和机器视觉任务。此方法通过多模态大模型为每个任务得出一组标签，接着应用这些基础模型进行精准定位，得以在编码器端全面理解和拆解图像组件。在解码阶段，借助这些编码组件以及生成模型的先验知识，实现图像的全面重构，从而优化人类视觉感知和基于机器的分析任务的性能。大量的实验评估证明了 DISCOVER 的稳健性和有效性，显示其在达成人类和机器视觉需求的双重目标上表现卓越。

> While learned image compression methods have achieved impressive results in either human visual perception or machine vision tasks, they are often specialized only for one domain. This drawback limits their versatility and generalizability across scenarios and also requires retraining to adapt to new applications-a process that adds significant complexity and cost in real-world scenarios. In this study, we introduce an innovative semantics DISentanglement and COmposition VERsatile codec (DISCOVER) to simultaneously enhance human-eye perception and machine vision tasks. The approach derives a set of labels per task through multimodal large models, which grounding models are then applied for precise localization, enabling a comprehensive understanding and disentanglement of image components at the encoder side. At the decoding stage, a comprehensive reconstruction of the image is achieved by leveraging these encoded components alongside priors from generative models, thereby optimizing performance for both human visual perception and machine-based analytical tasks. Extensive experimental evaluations substantiate the robustness and effectiveness of DISCOVER, demonstrating superior performance in fulfilling the dual objectives of human and machine vision requirements.

[Arxiv](https://arxiv.org/abs/2412.18158)