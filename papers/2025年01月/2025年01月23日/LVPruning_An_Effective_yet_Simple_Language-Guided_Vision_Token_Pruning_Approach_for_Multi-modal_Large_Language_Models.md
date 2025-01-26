# LVPruning: 一种简洁高效的语言引导视觉令牌剪枝方法，专为多模态大语言模型设计

发布时间：2025年01月23日

`LLM应用

**理由**：该论文主要关注多模态大型语言模型（MLLMs）的计算效率优化问题，提出了一种语言引导的视觉标记剪枝方法（LVPruning），旨在降低计算开销并保持模型性能。这属于对现有LLM技术的应用和优化，因此归类为LLM应用。` `计算机视觉`

> LVPruning: An Effective yet Simple Language-Guided Vision Token Pruning Approach for Multi-modal Large Language Models

# 摘要

> 多模态大型语言模型（MLLMs）通过融合视觉与文本模态取得了显著成就。然而，大量视觉标记的处理带来了巨大的计算开销，限制了其在资源受限环境中的应用。为此，我们提出了语言引导的视觉标记剪枝（LVPruning），这是一种简单高效的方法，能在保持模型性能的同时大幅降低计算负担。LVPruning利用交叉注意力模块，根据视觉标记与语言标记的交互计算其重要性，从而决定哪些标记可以剪枝。更重要的是，LVPruning无需修改原始MLLM参数，便于灵活应用或移除。实验表明，LVPruning在LLaVA-1.5的中间层可减少高达90%的视觉标记，推理TFLOPs降低62.1%，而在九个多模态基准测试中，平均性能损失仅为0.45%。

> Multi-modal Large Language Models (MLLMs) have achieved remarkable success by integrating visual and textual modalities. However, they incur significant computational overhead due to the large number of vision tokens processed, limiting their practicality in resource-constrained environments. We introduce Language-Guided Vision Token Pruning (LVPruning) for MLLMs, an effective yet simple method that significantly reduces the computational burden while preserving model performance. LVPruning employs cross-attention modules to compute the importance of vision tokens based on their interaction with language tokens, determining which to prune. Importantly, LVPruning can be integrated without modifying the original MLLM parameters, which makes LVPruning simple to apply or remove. Our experiments show that LVPruning can effectively reduce up to 90% of vision tokens by the middle layer of LLaVA-1.5, resulting in a 62.1% decrease in inference Tera Floating-Point Operations Per Second (TFLOPs), with an average performance loss of just 0.45% across nine multi-modal benchmarks.

[Arxiv](https://arxiv.org/abs/2501.13652)