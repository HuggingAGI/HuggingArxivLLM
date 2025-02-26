# LDGen：通过大型语言模型驱动的语言表征增强文本到图像的合成

发布时间：2025年02月25日

`LLM应用

理由：这篇论文提出了一种结合大型语言模型（LLMs）与文本到图像扩散模型的新方法，专注于跨语言图像生成。它探讨了LLMs在多语言处理中的应用，属于将LLM技术应用于具体任务的范畴，因此归类为LLM应用。` `计算机视觉` `生成对抗网络`

> LDGen: Enhancing Text-to-Image Synthesis via Large Language Model-Driven Language Representation

# 摘要

> 本文提出了一种全新方法 LDGen，将大型语言模型 (LLMs) 与现有文本到图像扩散模型相结合，同时大幅降低计算成本。传统文本编码器如 CLIP 和 T5 在多语言处理方面存在局限性，限制了跨语言图像生成能力。我们通过充分发挥 LLMs 的潜力，提出了一种基于层次化标题优化和人类指令技术的语言表示策略，以精准提取语义信息。随后，我们引入轻量级适配器和跨模态优化器，实现 LLMs 与图像特征之间的高效交互与对齐。LDGen 不仅显著缩短了训练时间，还支持零样本多语言图像生成。实验结果表明，该方法在提示遵循度和图像美学质量方面均超越现有基线模型，且完美支持多语言环境。项目页面：https://zrealli.github.io/LDGen。

> In this paper, we introduce LDGen, a novel method for integrating large language models (LLMs) into existing text-to-image diffusion models while minimizing computational demands. Traditional text encoders, such as CLIP and T5, exhibit limitations in multilingual processing, hindering image generation across diverse languages. We address these challenges by leveraging the advanced capabilities of LLMs. Our approach employs a language representation strategy that applies hierarchical caption optimization and human instruction techniques to derive precise semantic information,. Subsequently, we incorporate a lightweight adapter and a cross-modal refiner to facilitate efficient feature alignment and interaction between LLMs and image features. LDGen reduces training time and enables zero-shot multilingual image generation. Experimental results indicate that our method surpasses baseline models in both prompt adherence and image aesthetic quality, while seamlessly supporting multiple languages. Project page: https://zrealli.github.io/LDGen.

[Arxiv](https://arxiv.org/abs/2502.18302)