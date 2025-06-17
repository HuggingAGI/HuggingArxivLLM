# 通用越狱后缀：强大的注意力劫持工具

发布时间：2025年06月15日

`LLM应用`

> Universal Jailbreak Suffixes Are Strong Attention Hijackers

# 摘要

> 我们研究了基于后缀的越狱攻击$unicode{x2013}$一种针对大型语言模型 (LLMs) 的强大攻击系列，通过优化对抗性后缀来规避安全对齐。聚焦于广泛使用的GCG基础攻击（Zou et al., 2023），我们发现后缀在效果上存在显著差异：某些后缀明显更具通用性，能够推广到许多未见过的有害指令。我们揭示了GCG的有效性源于一种浅层的关键机制，该机制基于从对抗性后缀到生成前最终聊天模板标记的信息流动。通过量化生成过程中这一机制的主导性，我们发现GCG不规则且激进地劫持了上下文化过程。更重要的是，我们将劫持与普遍性现象联系起来，更普遍的后缀展现出更强的劫持能力。进一步研究发现，这些发现具有重要实际意义：GCG的普遍性可以高效增强（某些情况下提升$	imes$5），且无需额外计算成本；同时，也可以精准缓解，至少将攻击成功率减半，同时最小化效用损失。我们已在http://github.com/matanbt/interp-jailbreak发布了相关代码和数据。

> We study suffix-based jailbreaks$\unicode{x2013}$a powerful family of attacks against large language models (LLMs) that optimize adversarial suffixes to circumvent safety alignment. Focusing on the widely used foundational GCG attack (Zou et al., 2023), we observe that suffixes vary in efficacy: some markedly more universal$\unicode{x2013}$generalizing to many unseen harmful instructions$\unicode{x2013}$than others. We first show that GCG's effectiveness is driven by a shallow, critical mechanism, built on the information flow from the adversarial suffix to the final chat template tokens before generation. Quantifying the dominance of this mechanism during generation, we find GCG irregularly and aggressively hijacks the contextualization process. Crucially, we tie hijacking to the universality phenomenon, with more universal suffixes being stronger hijackers. Subsequently, we show that these insights have practical implications: GCG universality can be efficiently enhanced (up to $\times$5 in some cases) at no additional computational cost, and can also be surgically mitigated, at least halving attack success with minimal utility loss. We release our code and data at http://github.com/matanbt/interp-jailbreak.

[Arxiv](https://arxiv.org/abs/2506.12880)