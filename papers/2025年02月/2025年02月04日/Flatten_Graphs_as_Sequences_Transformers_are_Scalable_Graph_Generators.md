# 图展平为序列：Transformer 作为可扩展的图生成器

发布时间：2025年02月04日

`LLM应用

理由：这篇论文介绍了AutoGraph，一个利用仅解码器的变压器生成大型属性图的框架。虽然它涉及图生成，但其核心是利用了类似于自然语言处理中的自回归模型（如Transformer）来生成图结构。这表明该研究是将大型语言模型（LLM）的技术应用于图生成领域，因此应归类为“LLM应用”。` `图生成` `分子建模`

> Flatten Graphs as Sequences: Transformers are Scalable Graph Generators

# 摘要

> 我们推出了AutoGraph，一个创新的自回归框架，利用仅解码器的变压器生成大型属性图。其核心是一个可逆的“扁平化”过程，将图转化为随机序列。通过从这些序列中采样和学习，AutoGraph让变压器能够像处理自然语言一样建模和生成复杂的图结构。与依赖高计算节点特征的扩散模型不同，我们的方法仅在这些序列上运行。采样复杂度和序列长度与边数线性相关，使AutoGraph在生成大型稀疏图时极具扩展性。实验证明，AutoGraph在多种合成和分子图生成基准测试中表现卓越，生成速度比主流扩散模型快100倍，训练速度提升3倍。此外，它还展现出强大的迁移能力，支持无需额外微调的子结构条件生成。通过将语言建模技术应用于图生成，这项研究为开发图基础模型奠定了基础。

> We introduce AutoGraph, a novel autoregressive framework for generating large attributed graphs using decoder-only transformers. At the core of our approach is a reversible "flattening" process that transforms graphs into random sequences. By sampling and learning from these sequences, AutoGraph enables transformers to model and generate complex graph structures in a manner akin to natural language. In contrast to diffusion models that rely on computationally intensive node features, our approach operates exclusively on these sequences. The sampling complexity and sequence length scale linearly with the number of edges, making AutoGraph highly scalable for generating large sparse graphs. Empirically, AutoGraph achieves state-of-the-art performance across diverse synthetic and molecular graph generation benchmarks, while delivering a 100-fold generation and a 3-fold training speedup compared to leading diffusion models. Additionally, it demonstrates promising transfer capabilities and supports substructure-conditioned generation without additional fine-tuning. By extending language modeling techniques to graph generation, this work paves the way for developing graph foundation models.

[Arxiv](https://arxiv.org/abs/2502.02216)