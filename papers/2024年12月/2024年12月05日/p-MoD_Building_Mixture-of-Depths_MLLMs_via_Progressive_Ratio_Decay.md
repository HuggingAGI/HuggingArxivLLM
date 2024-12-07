# p-MoD：借助渐进比率衰减打造深度混合的多语言大型语言模型

发布时间：2024年12月05日

`LLM应用` `计算机视觉`

> p-MoD: Building Mixture-of-Depths MLLMs via Progressive Ratio Decay

# 摘要

> 尽管多模态大型语言模型（MLLMs）在各类任务中表现抢眼，但高昂的训练和推理成本却制约了其发展。其中，大量的计算量源自于变压器解码器所处理的海量视觉标记。在本文中，我们提议借助深度混合（MoD）机制来构建高效的 MLLMs，即让每个变压器解码器层挑选出必要的视觉标记来处理，而跳过冗余的标记。然而，将 MoD 融入 MLLMs 并非易事。为应对训练和推理的稳定性问题以及有限的训练数据，我们用两种新颖的设计来适配 MoD 模块：双曲正切门控权重归一化（TanhNorm）和对称标记重新加权（STRing）。另外，我们发现视觉标记在更深的层中冗余度更高，于是设计了一种渐进比率衰减（PRD）策略，采用偏移余弦调度，逐层逐步降低标记保留比率。这一关键设计充分激发了 MoD 的潜力，大幅提升了我们模型的效率和性能。为验证我们方法的有效性，我们用两个基线模型在 14 个基准上开展了广泛的实验。我们的模型 p-MoD 在推理时仅需 55.6％的 TFLOPs 和 53.8％的 KV 缓存存储，训练时仅需 77.7％的 GPU 小时，却能与基线模型的性能持平甚至更优。

> Despite the remarkable performance of multimodal large language models (MLLMs) across diverse tasks, the substantial training and inference costs impede their advancement. The majority of computation stems from the overwhelming volume of vision tokens processed by the transformer decoder. In this paper, we propose to build efficient MLLMs by leveraging the Mixture-of-Depths (MoD) mechanism, where each transformer decoder layer selects essential vision tokens to process while skipping redundant ones. However, integrating MoD into MLLMs is non-trivial. To address the challenges of training and inference stability as well as limited training data, we adapt the MoD module with two novel designs: tanh-gated weight normalization (TanhNorm) and symmetric token reweighting (STRing). Moreover, we observe that vision tokens exhibit higher redundancy in deeper layer and thus design a progressive ratio decay (PRD) strategy, which gradually reduces the token retention ratio layer by layer, employing a shifted cosine schedule. This crucial design fully unleashes the potential of MoD, significantly boosting the efficiency and performance of our models. To validate the effectiveness of our approach, we conduct extensive experiments with two baseline models across 14 benchmarks. Our model, p-MoD, matches or even surpasses the performance of the baseline models, with only 55.6% TFLOPs and 53.8% KV cache storage during inference, and 77.7% GPU hours during training.

[Arxiv](https://arxiv.org/abs/2412.04449)