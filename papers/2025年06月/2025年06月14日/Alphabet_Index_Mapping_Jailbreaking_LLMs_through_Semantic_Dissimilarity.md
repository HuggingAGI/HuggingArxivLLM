# 字母索引映射：利用语义差异突破LLMs

发布时间：2025年06月14日

`LLM理论` `模型安全` `对抗攻击`

> Alphabet Index Mapping: Jailbreaking LLMs through Semantic Dissimilarity

# 摘要

> 大型语言模型 (LLMs) 虽然能力非凡，但其易受对抗攻击，尤其是越狱攻击，带来了严重的安全和伦理问题。尽管现有的越狱方法众多，但许多方法因计算成本高、令牌使用量大或解码方案复杂而难以广泛应用。Liu 等人 (2024) 提出的 FlipAttack 作为一种黑盒方法，通过简单的提示操作实现了高攻击成功率 (ASR)。本文深入探究了 FlipAttack 的有效性机制，重点分析了其翻转模式引发的语义变化。我们假设，原始提示与操纵后提示之间的语义差异与攻击成功率 (ASR) 呈负相关。通过嵌入空间可视化 (UMAP, KDE) 和余弦相似度分析，我们验证了这一假设。此外，我们提出了一种新型对抗攻击方法——字母索引映射 (AIM)，旨在在保持简单可解码性的同时最大化语义差异。实验结果表明，在 GPT-4 上使用 AdvBench 的一部分进行测试时，AIM 及其变体 AIM+FWO 在该子集上实现了 94% 的 ASR，显著优于 FlipAttack 和其他方法。研究结果表明，高语义差异虽是越狱成功的关键，但与解码简单性的平衡同样至关重要。这项研究不仅深化了我们对对抗提示机制的理解，还提供了一种新的有效越狱技术，为未来的研究和应用提供了重要参考。

> Large Language Models (LLMs) have demonstrated remarkable capabilities, yet their susceptibility to adversarial attacks, particularly jailbreaking, poses significant safety and ethical concerns. While numerous jailbreak methods exist, many suffer from computational expense, high token usage, or complex decoding schemes. Liu et al. (2024) introduced FlipAttack, a black-box method that achieves high attack success rates (ASR) through simple prompt manipulation. This paper investigates the underlying mechanisms of FlipAttack's effectiveness by analyzing the semantic changes induced by its flipping modes. We hypothesize that semantic dissimilarity between original and manipulated prompts is inversely correlated with ASR. To test this, we examine embedding space visualizations (UMAP, KDE) and cosine similarities for FlipAttack's modes. Furthermore, we introduce a novel adversarial attack, Alphabet Index Mapping (AIM), designed to maximize semantic dissimilarity while maintaining simple decodability. Experiments on GPT-4 using a subset of AdvBench show AIM and its variant AIM+FWO achieve a 94% ASR, outperforming FlipAttack and other methods on this subset. Our findings suggest that while high semantic dissimilarity is crucial, a balance with decoding simplicity is key for successful jailbreaking. This work contributes to a deeper understanding of adversarial prompt mechanics and offers a new, effective jailbreak technique.

[Arxiv](https://arxiv.org/abs/2506.12685)