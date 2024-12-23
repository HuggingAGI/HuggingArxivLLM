# 用于可控艺术图像风格化与生成的内容风格解耦表示

发布时间：2024年12月18日

`其他` `图像生成`

> Content-style disentangled representation for controllable artistic image stylization and generation

# 摘要

> 可控的艺术图像风格化与生成，旨在以习得的艺术风格来渲染文本或图像所提供的内容，其中内容与风格的解耦是获取理想效果的关键。然而，当下用于内容和风格解缠的方法主要依赖图像信息进行监督，由此引发了两个问题：1）模型仅能支持一种模态作为风格或内容的输入；2）解缠不彻底，致使参考图像存在语义干扰。为应对上述问题，本文提出了一种用于可控艺术图像风格化和生成的内容 - 风格表示解缠方法。我们构建了 WikiStyle + 数据集，其中包含具有相应风格和内容文本描述的艺术品。基于多模态数据集，我们提出了一种解缠的内容和风格表示引导的扩散模型。解缠表示先由 Q-Formers 学习，然后通过可学习的多步交叉注意力层注入到预训练的扩散模型中，以实现更优的可控风格化。这种方式使模型能够适应不同模态的输入。实验结果显示，我们的方法在多模态监督下，实现了参考图像中内容和风格的完全解缠，从而在生成的输出中达成内容和风格的和谐融合，成功生成风格一致且富有表现力的风格化图像。

> Controllable artistic image stylization and generation aims to render the content provided by text or image with the learned artistic style, where content and style decoupling is the key to achieve satisfactory results. However, current methods for content and style disentanglement primarily rely on image information for supervision, which leads to two problems: 1) models can only support one modality for style or content input;2) incomplete disentanglement resulting in semantic interference from the reference image. To address the above issues, this paper proposes a content-style representation disentangling method for controllable artistic image stylization and generation. We construct a WikiStyle+ dataset consists of artworks with corresponding textual descriptions for style and content. Based on the multimodal dataset, we propose a disentangled content and style representations guided diffusion model. The disentangled representations are first learned by Q-Formers and then injected into a pre-trained diffusion model using learnable multi-step cross-attention layers for better controllable stylization. This approach allows model to accommodate inputs from different modalities. Experimental results show that our method achieves a thorough disentanglement of content and style in reference images under multimodal supervision, thereby enabling a harmonious integration of content and style in the generated outputs, successfully producing style-consistent and expressive stylized images.

[Arxiv](https://arxiv.org/abs/2412.14496)