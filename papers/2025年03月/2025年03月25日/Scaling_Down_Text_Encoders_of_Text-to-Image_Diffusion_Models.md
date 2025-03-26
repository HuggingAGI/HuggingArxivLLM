# 文本扩散模型文本编码器的压缩

发布时间：2025年03月25日

`LLM应用` `图像生成`

> Scaling Down Text Encoders of Text-to-Image Diffusion Models

# 摘要

> 扩散模型中的文本编码器经历了从CLIP到T5-XXL的快速迭代，虽然显著提升了模型对复杂提示的理解和文本生成能力，但也带来了参数数量的激增。尽管T5系列编码器是在包含大量非视觉数据的C4语料库上训练，但配备T5编码器的扩散模型却无法响应这些非视觉提示，显示出其表征能力的冗余。这引发了一个重要问题："我们需要如此庞大的文本编码器吗？"为解答这一疑问，我们采用视觉知识蒸馏方法训练了一系列T5编码器模型。为全面继承其能力，我们基于图像质量、语义理解和文字呈现三大标准构建了数据集。实验结果表明，蒸馏后的T5-base模型在图像生成质量上可与T5-XXL相媲美，而模型大小仅为后者的1/50。这种大幅的模型压缩显著降低了运行如FLUX和SD3等前沿模型所需的GPU资源，让高质量的文本到图像生成变得更加普及。

> Text encoders in diffusion models have rapidly evolved, transitioning from CLIP to T5-XXL. Although this evolution has significantly enhanced the models' ability to understand complex prompts and generate text, it also leads to a substantial increase in the number of parameters. Despite T5 series encoders being trained on the C4 natural language corpus, which includes a significant amount of non-visual data, diffusion models with T5 encoder do not respond to those non-visual prompts, indicating redundancy in representational power. Therefore, it raises an important question: "Do we really need such a large text encoder?" In pursuit of an answer, we employ vision-based knowledge distillation to train a series of T5 encoder models. To fully inherit its capabilities, we constructed our dataset based on three criteria: image quality, semantic understanding, and text-rendering. Our results demonstrate the scaling down pattern that the distilled T5-base model can generate images of comparable quality to those produced by T5-XXL, while being 50 times smaller in size. This reduction in model size significantly lowers the GPU requirements for running state-of-the-art models such as FLUX and SD3, making high-quality text-to-image generation more accessible.

[Arxiv](https://arxiv.org/abs/2503.19897)