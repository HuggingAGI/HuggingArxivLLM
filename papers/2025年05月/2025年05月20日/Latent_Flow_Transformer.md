# 潜在流变换器

发布时间：2025年05月20日

`LLM理论

理由：这篇论文探讨了Transformer架构的优化，特别是通过引入新的方法（如Latent Flow Transformer和Flow Walking算法）来减少层数并提升效率。这属于对大型语言模型（LLM）内部机制和结构的理论研究，旨在改进模型的性能和效率，因此归类为LLM理论。` `模型架构` `流式生成`

> Latent Flow Transformer

# 摘要

> Transformers 作为 LLMs 的标准架构，通常由数十到数百个离散层构成。虽然增加层数能提升性能，但这种方法因效率问题饱受诟病，尤其在扩散模型和流式模型通过连续层展现图像生成优势后。我们提出了一种名为 Latent Flow Transformer (LFT) 的创新方法，该方法通过流匹配训练的单一可学习传输算子替代一组层，实现显著压缩的同时保持与原始架构的兼容性。此外，我们通过引入 Flow Walking (FW) 算法，成功解决了现有流式方法在 	extit{保持耦合} 方面的局限性。在 Pythia-410M 模型上，流匹配训练的 LFT 压缩了 24 层中的 6 层，并在 LM logits 的 KL 散度（0.407 vs. 0.529）方面优于直接跳过 2 层的表现，验证了该设计的可行性。当通过 FW 算法进行训练时，LFT 进一步将 12 层压缩为一层，同时将 KL 散度降低至 0.736，超越了跳过 3 层的 KL 散度（0.932），显著缩小了自回归生成与流式生成范式之间的差距。

> Transformers, the standard implementation for large language models (LLMs), typically consist of tens to hundreds of discrete layers. While more layers can lead to better performance, this approach has been challenged as far from efficient, especially given the superiority of continuous layers demonstrated by diffusion and flow-based models for image generation. We propose the Latent Flow Transformer (LFT), which replaces a block of layers with a single learned transport operator trained via flow matching, offering significant compression while maintaining compatibility with the original architecture. Additionally, we address the limitations of existing flow-based methods in \textit{preserving coupling} by introducing the Flow Walking (FW) algorithm. On the Pythia-410M model, LFT trained with flow matching compresses 6 of 24 layers and outperforms directly skipping 2 layers (KL Divergence of LM logits at 0.407 vs. 0.529), demonstrating the feasibility of this design. When trained with FW, LFT further distills 12 layers into one while reducing the KL to 0.736 surpassing that from skipping 3 layers (0.932), significantly narrowing the gap between autoregressive and flow-based generation paradigms.

[Arxiv](https://arxiv.org/abs/2505.14513)