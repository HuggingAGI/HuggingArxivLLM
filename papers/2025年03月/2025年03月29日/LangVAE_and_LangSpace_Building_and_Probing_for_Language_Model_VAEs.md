# LangVAE 与 LangSpace：构建与探究语言模型 VAE

发布时间：2025年03月29日

`LLM理论` `文本表示`

> LangVAE and LangSpace: Building and Probing for Language Model VAEs

# 摘要

> 我们提出了一种名为LangVAE的新颖框架，用于在预训练的大型语言模型（LLMs）之上构建变分自编码器（VAEs）。这种基于语言模型的VAE能够将预训练组件的知识编码为更紧凑且语义解纠缠的表示形式。通过这种方式获得的表示可以使用LangVAE的配套框架：LangSpace进行分析，该框架支持向量遍历和插值、解纠缠度量以及聚类可视化等多种探查方法。LangVAE和LangSpace提供了一种灵活、高效且可扩展的方式来构建和分析文本表示，支持与HuggingFace Hub上可用的模型进行简单集成。此外，我们还进行了一系列实验，测试了不同编码器和解码器的组合以及标注输入，揭示了在一般化和解纠缠方面跨越不同架构家族和规模的广泛交互作用。我们的研究结果展示了一个有前景的框架，用于系统化地进行实验和理解文本表示。

> We present LangVAE, a novel framework for modular construction of variational autoencoders (VAEs) on top of pre-trained large language models (LLMs). Such language model VAEs can encode the knowledge of their pre-trained components into more compact and semantically disentangled representations. The representations obtained in this way can be analysed with the LangVAE companion framework: LangSpace, which implements a collection of probing methods, such as vector traversal and interpolation, disentanglement measures, and cluster visualisations. LangVAE and LangSpace offer a flexible, efficient and scalable way of building and analysing textual representations, with simple integration for models available on the HuggingFace Hub. Additionally, we conducted a set of experiments with different encoder and decoder combinations, as well as annotated inputs, revealing a wide range of interactions across architectural families and sizes w.r.t. generalisation and disentanglement. Our findings demonstrate a promising framework for systematising the experimentation and understanding of textual representations.

[Arxiv](https://arxiv.org/abs/2505.00004)