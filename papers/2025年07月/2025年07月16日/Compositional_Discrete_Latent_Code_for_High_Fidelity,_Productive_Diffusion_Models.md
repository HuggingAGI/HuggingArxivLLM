# 组合式离散潜在代码：提升扩散模型的生成质量和效率

发布时间：2025年07月16日

`其他` `图像生成` `跨模态生成`

> Compositional Discrete Latent Code for High Fidelity, Productive Diffusion Models

# 摘要

> 我们认为扩散模型的成功主要得益于其输入条件。本文从理想表示应提升样本保真度、易于生成且具有组合性的角度，研究了用于条件扩散模型的表示方法。我们提出了一种名为离散潜在代码（DLC）的图像表示方法，它是基于自监督学习目标训练的单纯形嵌入。DLCs 是离散标记的序列，与传统的连续图像嵌入不同。它们易于生成，且其组合性使得能够对训练分布之外的新颖图像进行采样。使用 DLCs 训练的扩散模型在样本保真度上表现更优，在ImageNet上达到了无条件图像生成的新技术水平。此外，我们展示了通过组合 DLCs，图像生成器能够生成分布外的样本，这些样本以多样化的方式连贯地结合了图像的语义信息。最后，我们展示了如何利用大规模预训练语言模型通过DLCs实现文本到图像的生成。我们对文本扩散语言模型进行了高效的微调，使其能够生成超出图像生成器训练分布的新样本的DLCs。

> We argue that diffusion models' success in modeling complex distributions is, for the most part, coming from their input conditioning. This paper investigates the representation used to condition diffusion models from the perspective that ideal representations should improve sample fidelity, be easy to generate, and be compositional to allow out-of-training samples generation. We introduce Discrete Latent Code (DLC), an image representation derived from Simplicial Embeddings trained with a self-supervised learning objective. DLCs are sequences of discrete tokens, as opposed to the standard continuous image embeddings. They are easy to generate and their compositionality enables sampling of novel images beyond the training distribution. Diffusion models trained with DLCs have improved generation fidelity, establishing a new state-of-the-art for unconditional image generation on ImageNet. Additionally, we show that composing DLCs allows the image generator to produce out-of-distribution samples that coherently combine the semantics of images in diverse ways. Finally, we showcase how DLCs can enable text-to-image generation by leveraging large-scale pretrained language models. We efficiently finetune a text diffusion language model to generate DLCs that produce novel samples outside of the image generator training distribution.

[Arxiv](https://arxiv.org/abs/2507.12318)