# 深入 MoE：通过多样性增强实现从密集结构到专家混合结构的大型语言模型重建

发布时间：2025年06月10日

`LLM理论

理由：这篇论文探讨了大型语言模型（LLMs）的混合专家架构（MoE）的重构方法，提出了一种增强多样性的方法DIVE，重点在于优化模型的训练效率和结构，属于LLM的理论研究。` `人工智能`

> DIVE into MoE: Diversity-Enhanced Reconstruction of Large Language Models from Dense into Mixture-of-Experts

# 摘要

> 混合专家架构（MoE）的大型语言模型（LLMs）通过选择性激活部分参数，实现了高成本效益。尽管MoE架构的LLMs在推理效率上表现出色，但从头训练大量专家却带来了巨大的计算开销。然而，将密集型LLM重构为MoE架构的LLM，能够显著降低训练预算。然而，现有的重构方法往往忽视了专家之间的多样性，可能导致冗余。

在本文中，我们发现经过不同校准数据集剪枝后的特定LLM表现出显著的多样性。基于此，我们提出了一种增强多样性的重构方法，名为DIVE。DIVE的方法包括领域亲和力挖掘、基于剪枝的专家重构以及高效的再训练。具体而言，重构过程包括对前馈网络（FFN）模块的剪枝和重新组装。重构后，我们对路由器、专家和归一化模块进行高效的再训练。

我们基于开源训练语料库，在Llama风格的LLMs上实现了DIVE。实验表明，DIVE在保持精度的同时，实现了训练效率的提升。在保持激活参数数量相同的情况下，优于现有的剪枝和MoE重构方法。

> Large language models (LLMs) with the Mixture-of-Experts (MoE) architecture achieve high cost-efficiency by selectively activating a subset of the parameters. Despite the inference efficiency of MoE LLMs, the training of extensive experts from scratch incurs substantial overhead, whereas reconstructing a dense LLM into an MoE LLM significantly reduces the training budget. However, existing reconstruction methods often overlook the diversity among experts, leading to potential redundancy. In this paper, we come up with the observation that a specific LLM exhibits notable diversity after being pruned on different calibration datasets, based on which we present a Diversity-Enhanced reconstruction method named DIVE. The recipe of DIVE includes domain affinity mining, pruning-based expert reconstruction, and efficient retraining. Specifically, the reconstruction includes pruning and reassembly of the feed-forward network (FFN) module. After reconstruction, we efficiently retrain the model on routers, experts and normalization modules. We implement DIVE on Llama-style LLMs with open-source training corpora. Experiments show that DIVE achieves training efficiency with minimal accuracy trade-offs, outperforming existing pruning and MoE reconstruction methods with the same number of activated parameters.

[Arxiv](https://arxiv.org/abs/2506.09351)