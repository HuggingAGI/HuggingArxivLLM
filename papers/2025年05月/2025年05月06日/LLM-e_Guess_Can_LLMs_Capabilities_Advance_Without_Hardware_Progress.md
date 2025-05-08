# LLM-e 探索：在没有硬件升级的情况下，LLM 的能力是否还能突破瓶颈？

发布时间：2025年05月06日

`LLM理论

理由：这篇论文探讨了大型语言模型（LLM）在计算资源受限条件下的算法创新和进展，分析了不同类型的算法创新对模型性能的影响，并提出了新的分类框架和量化指标。这些内容属于对LLM理论的深入研究，因此归类为LLM理论。` `人工智能`

> LLM-e Guess: Can LLMs Capabilities Advance Without Hardware Progress?

# 摘要

> 本文探讨了在不增加计算资源的情况下，大型语言模型（LLM）的能力是否能够继续进步，通过分析前沿LLMs所使用的算法的发展和作用。鉴于监管努力主要集中在限制高性能硬件的访问，我们提出以下问题：LLMs能否在计算资源受限的环境下取得进展？在这样的条件下，算法创新的表现如何？

    为了解答这些问题，我们提出了一种新的分类框架，区分了两类算法创新：计算资源依赖型创新（例如Transformer架构和专家混合模型），它们在高计算资源水平下能获得不成比例的收益；以及计算资源无关型创新（例如旋转位置编码、FlashAttention或层归一化），这些创新在所有计算规模下都能提高效率。我们使用计算等效增益（CEG）这一指标来量化这些贡献，该指标估计了在没有这些算法进步的情况下，实现类似改进所需的额外计算资源。

    为了验证这一框架，我们使用缩小版的GPT-2模型进行了小规模的训练实验。结果显示，计算资源无关型创新在资源受限的环境中仍能带来显著的性能提升，与基线模型相比，CEG高达【数学公式】。相比之下，计算资源依赖型创新在小规模下效果有限，甚至可能降低性能，这进一步凸显了计算资源对某些算法改进的重要性。

> This paper examines whether large language model (LLM) capabilities can continue to advance without additional compute by analyzing the development and role of algorithms used in state-of-the-art LLMs. Motivated by regulatory efforts that have largely focused on restricting access to high-performance hardware, we ask: Can LLMs progress in a compute-constrained environment, and how do algorithmic innovations perform under such conditions?
  To address these questions, we introduce a novel classification framework that distinguishes between compute-dependent innovations -- which yield disproportionate benefits at high compute levels (e.g., the Transformer architecture and mixture-of-experts models) and compute-independent innovations, which improve efficiency across all compute scales (e.g., rotary positional encoding, FlashAttention, or layer normalization). We quantify these contributions using a metric called compute-equivalent gain (CEG), which estimates the additional compute that would be required to achieve similar improvements without these algorithmic advancements.
  To validate this framework, we conduct small-scale training experiments with a scaled-down GPT-2 model. Our results confirm that compute-independent advancements yield meaningful performance gains even in resource-constrained settings, with a CEG of up to $3.5\times$ over a baseline model. By contrast, compute-dependent advancements provided little benefit or even degraded performance at the small scale, reinforcing the importance of compute availability for certain algorithmic gains.

[Arxiv](https://arxiv.org/abs/2505.04075)