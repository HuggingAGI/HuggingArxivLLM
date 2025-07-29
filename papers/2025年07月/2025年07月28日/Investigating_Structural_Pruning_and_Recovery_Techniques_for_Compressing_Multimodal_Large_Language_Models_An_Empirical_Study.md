# 探究用于压缩多模态大型语言模型的结构剪枝与恢复技术：实证研究
本研究通过实证方法，深入探究了结构剪枝与恢复技术在压缩多模态大型语言模型中的应用与效果。

发布时间：2025年07月28日

`LLM应用` `模型压缩与优化` `多模态模型`

> Investigating Structural Pruning and Recovery Techniques for Compressing Multimodal Large Language Models: An Empirical Study

# 摘要

> 多模态大型语言模型（MLLMs）虽然能力出众，但其对计算和内存的高需求限制了实际应用。当前主流的参数缩减方法主要通过从小型语言模型（SLMs）训练MLLMs，但这些方法灵活性差且计算成本高昂。为解决这一难题，我们提出了一种通过结构化剪枝结合高效恢复训练直接压缩现有MLLMs的方法。具体来说，我们探索了两种结构化剪枝范式——逐层剪枝和宽度剪枝——并将其应用于MLLMs的语言模型架构，同时结合监督微调和知识蒸馏技术。此外，我们还研究了仅使用少量数据进行恢复训练的可能性。实验结果显示，在计算资源有限或微调数据不足的低资源场景下，宽度剪枝通常能保持更佳性能。关于恢复训练，仅需对多模态投影器进行微调即可在较小压缩比例（<20%）下实现有效恢复。特别地，结合监督微调和隐藏状态蒸馏能够在各种剪枝级别下实现最优恢复效果。值得注意的是，仅需使用原始训练数据的5%，即可实现超过95%的原始性能。通过对具有代表性的两个MLLMs——LLaVA-v1.5-7B和Bunny-v1.0-3B——的实证研究，本研究为希望在计算资源有限或数据不足情况下有效压缩MLLMs的实践者提供了切实可行的见解。

> While Multimodal Large Language Models (MLLMs) demonstrate impressive capabilities, their substantial computational and memory requirements pose significant barriers to practical deployment. Current parameter reduction techniques primarily involve training MLLMs from Small Language Models (SLMs), but these methods offer limited flexibility and remain computationally intensive. To address this gap, we propose to directly compress existing MLLMs through structural pruning combined with efficient recovery training. Specifically, we investigate two structural pruning paradigms--layerwise and widthwise pruning--applied to the language model backbone of MLLMs, alongside supervised finetuning and knowledge distillation. Additionally, we assess the feasibility of conducting recovery training with only a small fraction of the available data. Our results show that widthwise pruning generally maintains better performance in low-resource scenarios with limited computational resources or insufficient finetuning data. As for the recovery training, finetuning only the multimodal projector is sufficient at small compression levels (< 20%). Furthermore, a combination of supervised finetuning and hidden-state distillation yields optimal recovery across various pruning levels. Notably, effective recovery can be achieved with as little as 5% of the original training data, while retaining over 95% of the original performance. Through empirical study on two representative MLLMs, i.e., LLaVA-v1.5-7B and Bunny-v1.0-3B, this study offers actionable insights for practitioners aiming to compress MLLMs effectively without extensive computation resources or sufficient data.

[Arxiv](https://arxiv.org/abs/2507.20749)