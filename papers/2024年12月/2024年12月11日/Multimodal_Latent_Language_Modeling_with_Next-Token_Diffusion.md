# 多模态潜在语言建模及下一个标记扩散

发布时间：2024年12月11日

`LLM应用` `多模态` `生成模型`

> Multimodal Latent Language Modeling with Next-Token Diffusion

# 摘要

> 多模态生成模型需要统一的方法来处理离散数据（如文本、代码）和连续数据（如图像、音频、视频）。在本研究中，我们提出了潜在语言建模（LatentLM），它借助因果 Transformer 实现了连续和离散数据的无缝融合。具体而言，我们运用变分自编码器（VAE）将连续数据表示为潜在向量，并引入下一令牌扩散来进行这些向量的自回归生成。此外，我们还开发了$σ$-VAE 以应对方差崩溃的难题，这对自回归建模至关重要。大量实验表明，LatentLM 在各种模态中均成效显著。在图像生成方面，LatentLM 在性能和可扩展性上都超越了 Diffusion Transformers。当融入多模态大型语言模型时，LatentLM 提供了一个通用接口，统一了多模态的生成与理解。实验结果显示，在增加训练令牌的设定下，LatentLM 相较于 Transfusion 和向量量化模型表现出色。在文本到语音合成中，LatentLM 在说话者相似度和鲁棒性上优于前沿的 VALL-E 2 模型，且解码步骤减少了 10 倍。这些成果确立了 LatentLM 是推进大型多模态模型的高效且可扩展的途径。

> Multimodal generative models require a unified approach to handle both discrete data (e.g., text and code) and continuous data (e.g., image, audio, video). In this work, we propose Latent Language Modeling (LatentLM), which seamlessly integrates continuous and discrete data using causal Transformers. Specifically, we employ a variational autoencoder (VAE) to represent continuous data as latent vectors and introduce next-token diffusion for autoregressive generation of these vectors. Additionally, we develop $σ$-VAE to address the challenges of variance collapse, which is crucial for autoregressive modeling. Extensive experiments demonstrate the effectiveness of LatentLM across various modalities. In image generation, LatentLM surpasses Diffusion Transformers in both performance and scalability. When integrated into multimodal large language models, LatentLM provides a general-purpose interface that unifies multimodal generation and understanding. Experimental results show that LatentLM achieves favorable performance compared to Transfusion and vector quantized models in the setting of scaling up training tokens. In text-to-speech synthesis, LatentLM outperforms the state-of-the-art VALL-E 2 model in speaker similarity and robustness, while requiring 10x fewer decoding steps. The results establish LatentLM as a highly effective and scalable approach to advance large multimodal models.

[Arxiv](https://arxiv.org/abs/2412.08635)