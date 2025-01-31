# 多模态适应与泛化的演进：从传统方法到基础模型

发布时间：2025年01月30日

`其他

理由：这篇论文主要讨论的是多模态领域适应和泛化的研究进展，涵盖了多模态领域适应、测试时间适应、领域泛化以及多模态基础模型的适应等方面。虽然提到了CLIP等大规模预训练多模态基础模型，但论文的核心内容并不直接涉及大型语言模型（LLM）的理论、应用或相关技术（如RAG或Agent）。因此，将其分类为“其他”更为合适。` `计算机视觉` `多模态学习`

> Advances in Multimodal Adaptation and Generalization: From Traditional Approaches to Foundation Models

# 摘要

> 在现实场景中，领域适应和泛化面临巨大挑战，因为模型需要适应或泛化到未知的目标分布。将这些能力扩展到未见的多模态分布（即多模态领域适应和泛化）则更具挑战性，因为不同模态的特性各异。近年来，从动作识别到语义分割等领域已取得显著进展。此外，CLIP等大规模预训练多模态基础模型的出现，推动了利用这些模型提升适应和泛化性能或将其应用于下游任务的研究。本文首次全面回顾了从传统方法到基础模型的最新进展，涵盖：（1）多模态领域适应；（2）多模态测试时间适应；（3）多模态领域泛化；（4）借助多模态基础模型的领域适应和泛化；（5）多模态基础模型的适应。针对每个主题，我们正式定义问题并深入回顾现有方法，同时分析相关数据集和应用，指出开放挑战与未来研究方向。我们维护了一个活跃的文献库，地址为https://github.com/donghao51/Awesome-Multimodal-Adaptation。

> In real-world scenarios, achieving domain adaptation and generalization poses significant challenges, as models must adapt to or generalize across unknown target distributions. Extending these capabilities to unseen multimodal distributions, i.e., multimodal domain adaptation and generalization, is even more challenging due to the distinct characteristics of different modalities. Significant progress has been made over the years, with applications ranging from action recognition to semantic segmentation. Besides, the recent advent of large-scale pre-trained multimodal foundation models, such as CLIP, has inspired works leveraging these models to enhance adaptation and generalization performances or adapting them to downstream tasks. This survey provides the first comprehensive review of recent advances from traditional approaches to foundation models, covering: (1) Multimodal domain adaptation; (2) Multimodal test-time adaptation; (3) Multimodal domain generalization; (4) Domain adaptation and generalization with the help of multimodal foundation models; and (5) Adaptation of multimodal foundation models. For each topic, we formally define the problem and thoroughly review existing methods. Additionally, we analyze relevant datasets and applications, highlighting open challenges and potential future research directions. We maintain an active repository that contains up-to-date literature at https://github.com/donghao51/Awesome-Multimodal-Adaptation.

[Arxiv](https://arxiv.org/abs/2501.18592)