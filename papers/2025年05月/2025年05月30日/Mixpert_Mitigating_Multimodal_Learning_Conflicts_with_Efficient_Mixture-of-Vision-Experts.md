# Mixpert：高效视觉专家混合模型缓解多模态学习冲突

发布时间：2025年05月30日

`LLM应用` `多模态`

> Mixpert: Mitigating Multimodal Learning Conflicts with Efficient Mixture-of-Vision-Experts

# 摘要

> 多模态大型语言模型（MLLMs）需要精准解析复杂图像信息，通常借助视觉编码器识别各种视觉场景。然而，单一视觉编码器难以应对多样化任务领域，难免引发冲突。近期研究通过整合多个领域专用视觉编码器提升数据感知能力，但增加了复杂性并限制了优化空间。本文提出Mixpert，一种高效视觉专家混合架构，它继承单一视觉编码器的联合学习优势，同时构建多专家范式实现不同视觉任务的特定微调。我们还设计了动态路由机制，将输入图像分配至最合适的视觉专家。Mixpert在多任务学习中有效缓解单一视觉编码器的领域冲突，仅需极小额外计算成本，相较于多编码器方案更为高效。此外，Mixpert可无缝集成至任意MLLM，实验结果表明其在各类任务中均实现显著性能提升。

> Multimodal large language models (MLLMs) require a nuanced interpretation of complex image information, typically leveraging a vision encoder to perceive various visual scenarios. However, relying solely on a single vision encoder to handle diverse task domains proves difficult and inevitably leads to conflicts. Recent work enhances data perception by directly integrating multiple domain-specific vision encoders, yet this structure adds complexity and limits the potential for joint optimization. In this paper, we introduce Mixpert, an efficient mixture-of-vision-experts architecture that inherits the joint learning advantages from a single vision encoder while being restructured into a multi-expert paradigm for task-specific fine-tuning across different visual tasks. Additionally, we design a dynamic routing mechanism that allocates input images to the most suitable visual expert. Mixpert effectively alleviates domain conflicts encountered by a single vision encoder in multi-task learning with minimal additional computational cost, making it more efficient than multiple encoders. Furthermore, Mixpert integrates seamlessly into any MLLM, with experimental results demonstrating substantial performance gains across various tasks.

[Arxiv](https://arxiv.org/abs/2505.24541)