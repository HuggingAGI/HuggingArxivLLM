# 路径数据扩散中的高计算成本：理解与缓解

发布时间：2025年02月02日

`其他

理由：这篇论文主要讨论了路径生成（PG）问题，并提出了一种潜在空间路径扩散（LPD）模型来降低计算成本。虽然论文中提到了扩散模型的应用，但整体内容与Agent、RAG、LLM应用、LLM理论等分类关系不大。因此，将其归类为其他更为合适。` `智能交通` `城市移动`

> Understanding and Mitigating the High Computational Cost in Path Data Diffusion

# 摘要

> # 摘要
移动服务、导航系统和智能交通技术的飞速发展，使得海量路径数据的收集成为可能。路径生成（PG）问题，即对这些路径数据的分布进行建模，对于理解城市移动模式和开发智能交通系统至关重要。近期研究探索了扩散模型在解决PG问题中的应用，得益于其捕捉多模态分布和支持条件生成的能力。一项最新研究在图形空间中明确设计了扩散过程，并取得了顶尖性能。然而，这种方法在时间和内存上的高计算成本限制了其应用。本文从理论和实验角度分析了该方法，发现其高计算成本的主要原因是图形空间中明确设计的扩散过程。为此，我们提出了一种潜在空间路径扩散（LPD）模型，该模型在潜在空间而非图形空间中运行。LPD显著降低了时间和内存成本，分别高达82.8%和83.1%，且性能未受影响。在大多数场景下，LPD比现有最佳方法提升了24.5%~34.0%。

> Advancements in mobility services, navigation systems, and smart transportation technologies have made it possible to collect large amounts of path data. Modeling the distribution of this path data, known as the Path Generation (PG) problem, is crucial for understanding urban mobility patterns and developing intelligent transportation systems. Recent studies have explored using diffusion models to address the PG problem due to their ability to capture multimodal distributions and support conditional generation. A recent work devises a diffusion process explicitly in graph space and achieves state-of-the-art performance. However, this method suffers a high computation cost in terms of both time and memory, which prohibits its application. In this paper, we analyze this method both theoretically and experimentally and find that the main culprit of its high computation cost is its explicit design of the diffusion process in graph space. To improve efficiency, we devise a Latent-space Path Diffusion (LPD) model, which operates in latent space instead of graph space. Our LPD significantly reduces both time and memory costs by up to 82.8% and 83.1%, respectively. Despite these reductions, our approach does not suffer from performance degradation. It outperforms the state-of-the-art method in most scenarios by 24.5%~34.0%.

[Arxiv](https://arxiv.org/abs/2502.00725)