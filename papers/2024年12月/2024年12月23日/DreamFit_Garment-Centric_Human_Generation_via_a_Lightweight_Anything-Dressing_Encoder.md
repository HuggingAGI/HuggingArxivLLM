# DreamFit：借助轻量级的任意着装编码器实现以服装为中心的人体生成

发布时间：2024年12月23日

`其他` `人体生成`

> DreamFit: Garment-Centric Human Generation via a Lightweight Anything-Dressing Encoder

# 摘要

> 基于文本或图像提示的以服装为中心的人体生成扩散模型，因其巨大的应用潜力而备受关注。然而，现有的方法常面临困境：像适配器这类轻量级方法，容易产生不一致的纹理；基于微调的方法则训练成本高，且难以维持预训练扩散模型的泛化能力，限制了其在不同场景中的表现。为应对这些挑战，我们提出了 DreamFit，它融合了专为以服装为中心的人体生成定制的轻量级 Anything-Dressing 编码器。DreamFit 有三大关键优势：（1）	extbf{轻量训练}：借助所提出的自适应注意力和 LoRA 模块，DreamFit 将模型复杂度大幅降至 8340 万个可训练参数。（2）	extbf{万能着装}：我们的模型对各类（非）服装、创意风格和提示指令的泛化能力极佳，在不同场景中均能持续提供高质量结果。（3）	extbf{即插即用}：DreamFit 专为与任何用于扩散模型的社区控制插件顺利集成而设计，确保轻松兼容，降低采用门槛。为进一步提升生成质量，DreamFit 利用预训练的大型多模态模型（LMMs），用细粒度的服装描述丰富提示，从而缩小训练和推理之间的提示差距。我们在 $768×512$ 的高分辨率基准和野外图像上开展了全面实验。DreamFit 超越了所有现有方法，彰显了其在以服装为中心的人体生成方面的顶尖能力。

> Diffusion models for garment-centric human generation from text or image prompts have garnered emerging attention for their great application potential. However, existing methods often face a dilemma: lightweight approaches, such as adapters, are prone to generate inconsistent textures; while finetune-based methods involve high training costs and struggle to maintain the generalization capabilities of pretrained diffusion models, limiting their performance across diverse scenarios. To address these challenges, we propose DreamFit, which incorporates a lightweight Anything-Dressing Encoder specifically tailored for the garment-centric human generation. DreamFit has three key advantages: (1) \textbf{Lightweight training}: with the proposed adaptive attention and LoRA modules, DreamFit significantly minimizes the model complexity to 83.4M trainable parameters. (2)\textbf{Anything-Dressing}: Our model generalizes surprisingly well to a wide range of (non-)garments, creative styles, and prompt instructions, consistently delivering high-quality results across diverse scenarios. (3) \textbf{Plug-and-play}: DreamFit is engineered for smooth integration with any community control plugins for diffusion models, ensuring easy compatibility and minimizing adoption barriers. To further enhance generation quality, DreamFit leverages pretrained large multi-modal models (LMMs) to enrich the prompt with fine-grained garment descriptions, thereby reducing the prompt gap between training and inference. We conduct comprehensive experiments on both $768 \times 512$ high-resolution benchmarks and in-the-wild images. DreamFit surpasses all existing methods, highlighting its state-of-the-art capabilities of garment-centric human generation.

[Arxiv](https://arxiv.org/abs/2412.17644)