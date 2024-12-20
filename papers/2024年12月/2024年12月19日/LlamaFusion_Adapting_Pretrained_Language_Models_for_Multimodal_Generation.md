# LlamaFusion：用于多模态生成的预训练语言模型调整

发布时间：2024年12月19日

`LLM应用` `多模态` `图像生成`

> LlamaFusion: Adapting Pretrained Language Models for Multimodal Generation

# 摘要

> 我们推出了 LlamaFusion 框架，它能赋予仅预训练文本的大型语言模型（LLMs）多模态生成能力，让其能够随意理解和生成文本与图像。LlamaFusion 借助现有的 Llama-3 权重来自动回归处理文本，同时引入额外的并行变压器模块用扩散方式处理图像。训练时，每种模态的数据都被导向其专用模块：特定模态的前馈层、查询-键-值投影和归一化层分别处理各自模态，而共享的自注意力层实现文本和图像特征的交互。通过冻结文本专用模块，仅训练图像专用模块，LlamaFusion 在保留仅文本 LLMs 语言能力的同时，具备了强大的视觉理解和生成能力。相较于从头预训练多模态生成模型的方法，我们的实验表明，LlamaFusion 仅用 50%的 FLOPs，就将图像理解提升了 20%，图像生成提高了 3.6%，并且保持了 Llama-3 的语言能力。我们还证实此框架能让现有的视觉语言模型具备多模态生成能力。总之，该框架不仅利用了仅文本 LLMs 现有的计算投入，还能并行发展语言和视觉能力，为高效的多模态模型开发指明了有前景的方向。

> We present LlamaFusion, a framework for empowering pretrained text-only large language models (LLMs) with multimodal generative capabilities, enabling them to understand and generate both text and images in arbitrary sequences. LlamaFusion leverages existing Llama-3's weights for processing texts autoregressively while introducing additional and parallel transformer modules for processing images with diffusion. During training, the data from each modality is routed to its dedicated modules: modality-specific feedforward layers, query-key-value projections, and normalization layers process each modality independently, while the shared self-attention layers allow interactions across text and image features. By freezing the text-specific modules and only training the image-specific modules, LlamaFusion preserves the language capabilities of text-only LLMs while developing strong visual understanding and generation abilities. Compared to methods that pretrain multimodal generative models from scratch, our experiments demonstrate that, LlamaFusion improves image understanding by 20% and image generation by 3.6% using only 50% of the FLOPs while maintaining Llama-3's language capabilities. We also demonstrate that this framework can adapt existing vision-language models with multimodal generation ability. Overall, this framework not only leverages existing computational investments in text-only LLMs but also enables the parallel development of language and vision capabilities, presenting a promising direction for efficient multimodal model development.

[Arxiv](https://arxiv.org/abs/2412.15188)