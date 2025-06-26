# # 基于扩散模型的超快速语言模型——水星

发布时间：2025年06月17日

`LLM应用

理由：这篇论文介绍了Mercury Coder，这是一个专门用于编码应用的大规模语言模型。论文详细描述了该模型的架构、性能提升以及在实际应用中的表现，属于将大型语言模型应用于特定领域的范畴，因此归类为LLM应用。` `软件开发` `人工智能`

> Mercury: Ultra-Fast Language Models Based on Diffusion

# 摘要

> 我们很高兴推出Mercury，新一代基于扩散的商用大规模语言模型（LLMs）。这些模型采用Transformer架构进行参数化，并能够并行预测多个标记。在本报告中，我们将重点介绍Mercury Coder，这是我们首个专为编码应用设计的扩散LLMs系列。目前，Mercury Coder分为Mini和Small两个版本。这些模型在速度与质量的前沿领域树立了新的标杆。

根据Artificial Analysis的独立评估，Mercury Coder Mini和Mercury Coder Small在NVIDIA H100 GPU上分别实现了每秒1109个和737个标记的最先进吞吐量。它们不仅比速度优化的前沿模型快10倍，同时保持了相当的质量水平。我们还展示了在多种语言和应用场景下的各种代码基准测试结果，以及开发者在Copilot Arena上的实际验证。目前，该模型在质量上排名第二，并且是整体最快的模型。

此外，我们发布了公共API（https://platform.inceptionlabs.ai/）和免费试用平台（https://chat.inceptionlabs.ai），方便大家体验和使用。

> We present Mercury, a new generation of commercial-scale large language models (LLMs) based on diffusion. These models are parameterized via the Transformer architecture and trained to predict multiple tokens in parallel. In this report, we detail Mercury Coder, our first set of diffusion LLMs designed for coding applications. Currently, Mercury Coder comes in two sizes: Mini and Small. These models set a new state-of-the-art on the speed-quality frontier. Based on independent evaluations conducted by Artificial Analysis, Mercury Coder Mini and Mercury Coder Small achieve state-of-the-art throughputs of 1109 tokens/sec and 737 tokens/sec, respectively, on NVIDIA H100 GPUs and outperform speed-optimized frontier models by up to 10x on average while maintaining comparable quality. We discuss additional results on a variety of code benchmarks spanning multiple languages and use-cases as well as real-world validation by developers on Copilot Arena, where the model currently ranks second on quality and is the fastest model overall. We also release a public API at https://platform.inceptionlabs.ai/ and free playground at https://chat.inceptionlabs.ai

[Arxiv](https://arxiv.org/abs/2506.17298)