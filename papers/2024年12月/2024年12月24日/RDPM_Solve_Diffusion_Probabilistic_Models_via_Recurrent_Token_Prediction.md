# RDPM：借助循环令牌预测来解决扩散概率模型

发布时间：2024年12月24日

`其他` `图像生成` `多模态生成`

> RDPM: Solve Diffusion Probabilistic Models via Recurrent Token Prediction

# 摘要

> 扩散概率模型（DPMs）已成为高保真图像合成的主流方法，其在连续的 VAE 潜在空间上进行扩散过程，这与大型语言模型（LLMs）的文本生成方式大不相同。在本文中，我们推出了一种全新的生成框架——递归扩散概率模型（RDPM），它借助递归令牌预测机制强化了扩散过程，由此开创了离散扩散领域。通过逐步向图像的潜在表示中引入高斯噪声，并以递归方式将其编码为向量量化令牌，RDPM 在离散值域上推动了独特的扩散过程。该过程会迭代预测后续时间步的令牌代码，将初始的标准高斯噪声转化为源数据分布，在损失函数方面与 GPT 式模型相符。RDPM 性能卓越，同时得益于只需几个推理步骤的速度优势。此模型不仅利用扩散过程保障高质量生成，还将连续信号转化为一系列高保真离散令牌，从而与其他离散令牌（如文本）保持统一的优化策略。我们期望这项工作能助力开发多模态生成的统一模型，尤其是通过将图像、视频和音频等连续信号域与文本相融合。我们会将代码和模型权重向开源社区公布。

> Diffusion Probabilistic Models (DPMs) have emerged as the de facto approach for high-fidelity image synthesis, operating diffusion processes on continuous VAE latent, which significantly differ from the text generation methods employed by Large Language Models (LLMs). In this paper, we introduce a novel generative framework, the Recurrent Diffusion Probabilistic Model (RDPM), which enhances the diffusion process through a recurrent token prediction mechanism, thereby pioneering the field of Discrete Diffusion. By progressively introducing Gaussian noise into the latent representations of images and encoding them into vector-quantized tokens in a recurrent manner, RDPM facilitates a unique diffusion process on discrete-value domains. This process iteratively predicts the token codes for subsequent timesteps, transforming the initial standard Gaussian noise into the source data distribution, aligning with GPT-style models in terms of the loss function. RDPM demonstrates superior performance while benefiting from the speed advantage of requiring only a few inference steps. This model not only leverages the diffusion process to ensure high-quality generation but also converts continuous signals into a series of high-fidelity discrete tokens, thereby maintaining a unified optimization strategy with other discrete tokens, such as text. We anticipate that this work will contribute to the development of a unified model for multimodal generation, specifically by integrating continuous signal domains such as images, videos, and audio with text. We will release the code and model weights to the open-source community.

[Arxiv](https://arxiv.org/abs/2412.18390)