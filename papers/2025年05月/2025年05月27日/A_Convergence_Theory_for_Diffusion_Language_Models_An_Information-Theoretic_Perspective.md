# # 扩散语言模型的收敛性理论：信息论视角
扩散语言模型的收敛性理论：从信息论角度出发

发布时间：2025年05月27日

`LLM理论` `大型语言模型`

> A Convergence Theory for Diffusion Language Models: An Information-Theoretic Perspective

# 摘要

> 扩散模型作为现代生成建模的强大力量，尤其在大型语言模型（LLMs）领域展现出巨大潜力。与传统的自回归模型按顺序生成不同，扩散模型通过并行采样实现更快生成，突破了从左到右的限制。尽管在实践中表现优异，但其理论基础仍待完善。本研究从信息论角度为扩散语言模型提供收敛性保证。分析显示，以KL散度衡量的采样误差与迭代次数$T$成反比，并与目标文本中令牌的互信息线性相关。我们还通过匹配的上下界（相差常数因子）证明了分析的严谨性。这些成果为扩散语言模型的实际效果提供了全新理论视角。

> Diffusion models have emerged as a powerful paradigm for modern generative modeling, demonstrating strong potential for large language models (LLMs). Unlike conventional autoregressive (AR) models that generate tokens sequentially, diffusion models enable parallel token sampling, leading to faster generation and eliminating left-to-right generation constraints. Despite their empirical success, the theoretical understanding of diffusion model approaches remains underdeveloped. In this work, we develop convergence guarantees for diffusion language models from an information-theoretic perspective. Our analysis demonstrates that the sampling error, measured by the Kullback-Leibler (KL) divergence, decays inversely with the number of iterations $T$ and scales linearly with the mutual information between tokens in the target text sequence. In particular, we establish matching upper and lower bounds, up to some constant factor, to demonstrate the tightness of our convergence analysis. These results offer novel theoretical insights into the practical effectiveness of diffusion language models.

[Arxiv](https://arxiv.org/abs/2505.21400)