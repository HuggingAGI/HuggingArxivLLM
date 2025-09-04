# OneCAT：面向统一理解与生成的仅解码器自回归模型

发布时间：2025年09月03日

`LLM应用` `基础理论`

> OneCAT: Decoder-Only Auto-Regressive Model for Unified Understanding and Generation

# 摘要

> 我们提出OneCAT——一款统一的多模态模型，它在全新的纯解码器Transformer架构中无缝整合了理解、生成与编辑功能。该框架在推理阶段无需依赖视觉Transformer（ViT）或视觉分词器等外部组件，这一独特设计大幅提升了效率，尤其适用于高分辨率输入场景。这一突破借助特定模态的混合专家（MoE）结构实现，该结构采用单一自回归（AR）目标训练，同时原生支持动态分辨率。此外，我们在大型语言模型（LLM）中首创多尺度视觉自回归机制，与基于扩散的方法相比，该机制在保持顶尖性能的同时，大幅减少了解码步骤。研究结果表明，纯自回归建模作为构建统一多模态智能的高效且优雅的基础，展现出巨大潜力。因此，OneCAT树立了新的性能标杆，在多模态生成、编辑及理解任务的各项基准测试中，均超越了现有的开源统一多模态模型。

> We introduce OneCAT, a unified multimodal model that seamlessly integrates understanding, generation, and editing within a novel, pure decoder-only transformer architecture. Our framework uniquely eliminates the need for external components such as Vision Transformers (ViT) or vision tokenizer during inference, leading to significant efficiency gains, especially for high-resolution inputs. This is achieved through a modality-specific Mixture-of-Experts (MoE) structure trained with a single autoregressive (AR) objective, which also natively supports dynamic resolutions. Furthermore, we pioneer a multi-scale visual autoregressive mechanism within the Large Language Model (LLM) that drastically reduces decoding steps compared to diffusion-based methods while maintaining state-of-the-art performance. Our findings demonstrate the powerful potential of pure autoregressive modeling as a sufficient and elegant foundation for unified multimodal intelligence. As a result, OneCAT sets a new performance standard, outperforming existing open-source unified multimodal models across benchmarks for multimodal generation, editing, and understanding.

[Arxiv](https://arxiv.org/abs/2509.03498)