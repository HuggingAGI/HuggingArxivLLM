# DeepSeek-VL2：用于高级多模态理解的专家混合式视觉语言模型

发布时间：2024年12月13日

`LLM应用` `视觉语言` `人工智能`

> DeepSeek-VL2: Mixture-of-Experts Vision-Language Models for Advanced Multimodal Understanding

# 摘要

> 我们推出了 DeepSeek-VL2，这是一系列先进的大型专家混合（MoE）视觉语言模型，它通过两大关键升级，显著超越了前身 DeepSeek-VL。在视觉组件方面，我们引入了专为处理不同宽高比的高分辨率图像而设计的动态平铺视觉编码策略。在语言组件方面，我们借助具有多头潜在注意力机制的 DeepSeekMoE 模型，该机制能将键值缓存压缩为潜在向量，从而实现高效推理和高吞吐量。通过在改进的视觉语言数据集上训练，DeepSeek-VL2 在包括但不限于视觉问答、光学字符识别、文档/表格/图表理解和视觉定位等各种任务中展现出卓越的能力。我们的模型系列包含三个变体：DeepSeek-VL2-Tiny、DeepSeek-VL2-Small 和 DeepSeek-VL2，分别拥有 1.0B、2.8B 和 4.5B 的激活参数。与现有的开源密集型和基于 MoE 的模型相比，DeepSeek-VL2 在激活参数相近或更少的情况下，实现了具有竞争力或领先的性能。代码和预训练模型可在 https://github.com/deepseek-ai/DeepSeek-VL2 公开获取。

> We present DeepSeek-VL2, an advanced series of large Mixture-of-Experts (MoE) Vision-Language Models that significantly improves upon its predecessor, DeepSeek-VL, through two key major upgrades. For the vision component, we incorporate a dynamic tiling vision encoding strategy designed for processing high-resolution images with different aspect ratios. For the language component, we leverage DeepSeekMoE models with the Multi-head Latent Attention mechanism, which compresses Key-Value cache into latent vectors, to enable efficient inference and high throughput. Trained on an improved vision-language dataset, DeepSeek-VL2 demonstrates superior capabilities across various tasks, including but not limited to visual question answering, optical character recognition, document/table/chart understanding, and visual grounding. Our model series is composed of three variants: DeepSeek-VL2-Tiny, DeepSeek-VL2-Small and DeepSeek-VL2, with 1.0B, 2.8B and 4.5B activated parameters respectively. DeepSeek-VL2 achieves competitive or state-of-the-art performance with similar or fewer activated parameters compared to existing open-source dense and MoE-based models. Codes and pre-trained models are publicly accessible at https://github.com/deepseek-ai/DeepSeek-VL2.

[Arxiv](https://arxiv.org/abs/2412.10302)