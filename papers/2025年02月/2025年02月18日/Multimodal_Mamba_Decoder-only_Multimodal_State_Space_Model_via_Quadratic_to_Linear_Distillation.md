# Multimodal Mamba：通过二次到线性蒸馏构建仅解码器的多模态状态空间模型

发布时间：2025年02月18日

`LLM应用` `人工智能` `计算机视觉`

> Multimodal Mamba: Decoder-only Multimodal State Space Model via Quadratic to Linear Distillation

# 摘要

> 多模态大型语言模型（MLLMs）虽表现优异，但因计算复杂度、缓存需求及视觉编码器依赖，部署面临挑战。我们提出mmMamba框架，通过渐进式蒸馏，使用适度资源开发线性复杂度的多模态模型。直接转换解码器型MLLMs，无需预训练组件。创新播种策略与三阶段蒸馏方案，确保知识迁移与多模态能力。支持混合架构，实现效率与性能的灵活平衡。mmMamba-linear性能媲美现有模型，而mmMamba-hybrid更接近HoVLE，速度提升显著，内存节省明显。代码与模型已开源，详情请访问https://github.com/hustvl/mmMamba。


> Recent Multimodal Large Language Models (MLLMs) have achieved remarkable performance but face deployment challenges due to their quadratic computational complexity, growing Key-Value cache requirements, and reliance on separate vision encoders. We propose mmMamba, a framework for developing linear-complexity native multimodal state space models through progressive distillation from existing MLLMs using moderate academic computational resources. Our approach enables the direct conversion of trained decoder-only MLLMs to linear-complexity architectures without requiring pre-trained RNN-based LLM or vision encoders. We propose an seeding strategy to carve Mamba from trained Transformer and a three-stage distillation recipe, which can effectively transfer the knowledge from Transformer to Mamba while preserving multimodal capabilities. Our method also supports flexible hybrid architectures that combine Transformer and Mamba layers for customizable efficiency-performance trade-offs. Distilled from the Transformer-based decoder-only HoVLE, mmMamba-linear achieves competitive performance against existing linear and quadratic-complexity VLMs, while mmMamba-hybrid further improves performance significantly, approaching HoVLE's capabilities. At 103K tokens, mmMamba-linear demonstrates 20.6$\times$ speedup and 75.8% GPU memory reduction compared to HoVLE, while mmMamba-hybrid achieves 13.5$\times$ speedup and 60.2% memory savings. Code and models are released at https://github.com/hustvl/mmMamba

[Arxiv](https://arxiv.org/abs/2502.13145)