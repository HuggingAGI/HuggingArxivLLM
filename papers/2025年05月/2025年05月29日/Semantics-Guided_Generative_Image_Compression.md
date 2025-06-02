# 生成式图像压缩：基于语义引导的方法

发布时间：2025年05月29日

`LLM应用` `图像压缩` `图像处理`

> Semantics-Guided Generative Image Compression

# 摘要

> 基于大规模多模态模型的文本到图像生成AI正迅速渗透到图像压缩领域，能够在极低比特率下生成高质量的图像表示。这项研究为现有的多模态图像语义压缩（MISC）方法引入了新颖组件，提升了生成图像在PSNR和感知指标上的质量。新增组件包括用于生成解码器的语义分割引导，以及基于图像特性控制扩散步骤数量的内容自适应扩散。实验结果表明，新引入的方法显著提升了基线MISC模型的性能，同时降低了复杂度。因此，编码和解码时间均减少了超过36%。此外，所提出的压缩框架在感知相似性和质量方面优于主流编解码器。代码和视觉示例已公开。

> Advancements in text-to-image generative AI with large multimodal models are spreading into the field of image compression, creating high-quality representation of images at extremely low bit rates. This work introduces novel components to the existing multimodal image semantic compression (MISC) approach, enhancing the quality of the generated images in terms of PSNR and perceptual metrics. The new components include semantic segmentation guidance for the generative decoder, as well as content-adaptive diffusion, which controls the number of diffusion steps based on image characteristics. The results show that our newly introduced methods significantly improve the baseline MISC model while also decreasing the complexity. As a result, both the encoding and decoding time are reduced by more than 36%. Moreover, the proposed compression framework outperforms mainstream codecs in terms of perceptual similarity and quality. The code and visual examples are available.

[Arxiv](https://arxiv.org/abs/2505.24015)