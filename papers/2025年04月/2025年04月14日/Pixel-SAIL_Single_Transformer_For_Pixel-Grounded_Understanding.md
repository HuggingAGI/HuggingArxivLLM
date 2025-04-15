# Pixel-SAIL：单一变换器实现像素级理解

发布时间：2025年04月14日

`LLM应用` `计算机视觉` `图像处理`

> Pixel-SAIL: Single Transformer For Pixel-Grounded Understanding

# 摘要

> 多模态大型语言模型（MLLMs）在细粒度像素级理解任务中表现出色。然而，现有方法严重依赖额外组件（如视觉编码器CLIP和分割专家），导致系统复杂度高且限制了模型扩展。本研究提出了一种高度简化的MLLM——Pixel-SAIL，无需额外组件即可实现像素级任务。我们的工作受到Single trAnsformer作为统一视觉-语言模型（SAIL）设计的启发，通过在transformers中联合学习视觉令牌和文本令牌。Pixel-SAIL具有三项关键技术改进：1）可学习上采样模块优化视觉特征；2）新型视觉提示注入策略实现早期融合；3）视觉专家蒸馏策略提升特征提取能力。我们还构建了一个全面的像素理解基准PerBench，包含详细物体描述、基于视觉提示的问题回答和视觉-文本引用分割三个任务。在多个基准测试中，Pixel-SAIL在更简单的流水线下实现了与现有方法相当甚至更优的结果。代码和模型即将在GitHub上开源。

> Multimodal Large Language Models (MLLMs) achieve remarkable performance for fine-grained pixel-level understanding tasks. However, all the works rely heavily on extra components, such as vision encoder (CLIP), segmentation experts, leading to high system complexity and limiting model scaling. In this work, our goal is to explore a highly simplified MLLM without introducing extra components. Our work is motivated by the recent works on Single trAnsformer as a unified vIsion-Language Model (SAIL) design, where these works jointly learn vision tokens and text tokens in transformers. We present Pixel-SAIL, a single transformer for pixel-wise MLLM tasks. In particular, we present three technical improvements on the plain baseline. First, we design a learnable upsampling module to refine visual token features. Secondly, we propose a novel visual prompt injection strategy to enable the single transformer to understand visual prompt inputs and benefit from the early fusion of visual prompt embeddings and vision tokens. Thirdly, we introduce a vision expert distillation strategy to efficiently enhance the single transformer's fine-grained feature extraction capability. In addition, we have collected a comprehensive pixel understanding benchmark (PerBench), using a manual check. It includes three tasks: detailed object description, visual prompt-based question answering, and visual-text referring segmentation. Extensive experiments on four referring segmentation benchmarks, one visual prompt benchmark, and our PerBench show that our Pixel-SAIL achieves comparable or even better results with a much simpler pipeline. Code and model will be released at https://github.com/magic-research/Sa2VA.

[Arxiv](https://arxiv.org/abs/2504.10465)