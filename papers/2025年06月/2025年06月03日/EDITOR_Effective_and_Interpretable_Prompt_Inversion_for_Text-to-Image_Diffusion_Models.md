# 编辑器：文本到图像扩散模型的高效且易于解释的提示反转方法

发布时间：2025年06月03日

`LLM应用` `计算机视觉` `图像生成`

> EDITOR: Effective and Interpretable Prompt Inversion for Text-to-Image Diffusion Models

# 摘要

> 文本到图像生成模型（如 Stable Diffusion）已实现显著突破，能够基于文本描述生成高质量且逼真的图像。提示反转任务——即识别生成特定图像所用的文本提示——在数据归属、模型溯源和水印验证等领域具有重要应用价值。近期研究提出了延迟投影方案以优化代表词汇空间的提示，但语义流畅性和效率问题仍待解决。尽管先进的图像描述生成模型或视觉大型语言模型能生成高度可解释的提示，但其图像相似性表现有限。本文提出了一种针对文本到图像扩散模型的提示反转技术——\sys，该技术通过预训练图像描述模型初始化嵌入，经潜在空间逆向工程优化后，利用嵌入到文本模型生成提示。我们在 MS COCO、LAION 和 Flickr 等常用数据集上的实验表明，与现有方法相比，我们的方法在图像相似性、文本对齐、提示可解释性和通用性方面均表现更优。此外，我们还展示了生成提示在跨概念图像合成、概念操控、进化多概念生成和无监督分割等任务中的应用。

> Text-to-image generation models~(e.g., Stable Diffusion) have achieved significant advancements, enabling the creation of high-quality and realistic images based on textual descriptions. Prompt inversion, the task of identifying the textual prompt used to generate a specific artifact, holds significant potential for applications including data attribution, model provenance, and watermarking validation. Recent studies introduced a delayed projection scheme to optimize for prompts representative of the vocabulary space, though challenges in semantic fluency and efficiency remain. Advanced image captioning models or visual large language models can generate highly interpretable prompts, but they often lack in image similarity. In this paper, we propose a prompt inversion technique called \sys for text-to-image diffusion models, which includes initializing embeddings using a pre-trained image captioning model, refining them through reverse-engineering in the latent space, and converting them to texts using an embedding-to-text model. Our experiments on the widely-used datasets, such as MS COCO, LAION, and Flickr, show that our method outperforms existing methods in terms of image similarity, textual alignment, prompt interpretability and generalizability. We further illustrate the application of our generated prompts in tasks such as cross-concept image synthesis, concept manipulation, evolutionary multi-concept generation and unsupervised segmentation.

[Arxiv](https://arxiv.org/abs/2506.03067)