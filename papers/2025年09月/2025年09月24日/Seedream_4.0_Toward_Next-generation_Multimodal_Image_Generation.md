# Seedream 4.0：迈向下一代多模态图像生成

发布时间：2025年09月24日

`其他` `媒体与娱乐`

> Seedream 4.0: Toward Next-generation Multimodal Image Generation

# 摘要

> 我们推出Seedream 4.0——一款高效高性能的多模态图像生成系统，它在单一框架内实现了文本到图像（T2I）合成、图像编辑与多图组合的一体化。该系统采用高效扩散Transformer架构，搭配强大的VAE模型，可大幅减少图像token数量，不仅让模型训练更高效，还能快速生成原生高分辨率图像（如1K-4K）。Seedream 4.0基于数十亿涵盖多样分类体系与知识核心概念的文本-图像对完成预训练，通过在数百个垂直场景中全面采集数据，配合优化策略，确保了模型的稳定大规模训练与优异泛化性能。此外，我们通过融入精心微调的VLM模型，开展多模态后训练，实现T2I与图像编辑任务的联合优化。在推理加速方面，系统融合对抗蒸馏、分布匹配、量化技术与推测解码方法，生成2K图像时推理时间仅需1.8秒（无需LLM/VLM作为PE模型）。综合评估表明，Seedream 4.0在T2I与多模态图像编辑任务中均达到了当前最佳水平，尤其在复杂任务中展现出卓越的多模态能力，包括精准图像编辑、上下文推理，还支持多图参考与多输出图像生成。这将传统T2I系统升级为更具交互性与多维性的创作工具，为生成式AI在创意设计与专业应用领域开辟了新可能。Seedream 4.0现已在https://www.volcengine.com/experience/ark?launch=seedream开放使用。

> We introduce Seedream 4.0, an efficient and high-performance multimodal image generation system that unifies text-to-image (T2I) synthesis, image editing, and multi-image composition within a single framework. We develop a highly efficient diffusion transformer with a powerful VAE which also can reduce the number of image tokens considerably. This allows for efficient training of our model, and enables it to fast generate native high-resolution images (e.g., 1K-4K). Seedream 4.0 is pretrained on billions of text-image pairs spanning diverse taxonomies and knowledge-centric concepts. Comprehensive data collection across hundreds of vertical scenarios, coupled with optimized strategies, ensures stable and large-scale training, with strong generalization. By incorporating a carefully fine-tuned VLM model, we perform multi-modal post-training for training both T2I and image editing tasks jointly. For inference acceleration, we integrate adversarial distillation, distribution matching, and quantization, as well as speculative decoding. It achieves an inference time of up to 1.8 seconds for generating a 2K image (without a LLM/VLM as PE model). Comprehensive evaluations reveal that Seedream 4.0 can achieve state-of-the-art results on both T2I and multimodal image editing. In particular, it demonstrates exceptional multimodal capabilities in complex tasks, including precise image editing and in-context reasoning, and also allows for multi-image reference, and can generate multiple output images. This extends traditional T2I systems into an more interactive and multidimensional creative tool, pushing the boundary of generative AI for both creativity and professional applications. Seedream 4.0 is now accessible on https://www.volcengine.com/experience/ark?launch=seedream.

[Arxiv](https://arxiv.org/abs/2509.20427)