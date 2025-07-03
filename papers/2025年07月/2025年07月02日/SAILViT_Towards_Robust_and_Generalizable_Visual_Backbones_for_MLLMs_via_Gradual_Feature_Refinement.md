# # SAILViT：通过逐步优化特征实现稳健通用的多语言大模型视觉主干
SAILViT 是一种通过逐步优化特征的方式，致力于为多语言大模型（MLLMs）打造稳健且通用的视觉主干模型的方法。

发布时间：2025年07月02日

`LLM应用` `人工智能` `模型优化`

> SAILViT: Towards Robust and Generalizable Visual Backbones for MLLMs via Gradual Feature Refinement

# 摘要

> 视觉Transformer（ViTs）在多模态大型语言模型（MLLMs）的视觉理解能力构建中扮演着基础主干模型的关键角色。尽管大多数ViTs通过基于图像-文本对的对比学习或自监督机制展现出了令人瞩目的性能，但它们在直接与LLMs进行基于连接器的协同训练时面临挑战，主要源于参数初始化冲突和模态语义差距。为解决这些难题，本文提出了一种基于渐进特征学习增强的ViT——SAILViT，旨在助力MLLMs突破复杂多模态交互中的性能瓶颈。SAILViT通过渐进特征细化实现了从粗到细的特征对齐和世界知识注入，更好地满足目标训练需求。我们进行了全面的实证分析，以验证SAILViT在参数规模、模型架构、训练策略和数据规模等不同维度上的强大鲁棒性和泛化能力。配备SAILViT的现有MLLMs在广泛的下游任务中对OpenCompass基准展现了显著且一致的性能提升。SAILViT系列模型已在https://huggingface.co/BytedanceDouyinContent上发布。

> Vision Transformers (ViTs) are essential as foundation backbones in establishing the visual comprehension capabilities of Multimodal Large Language Models (MLLMs). Although most ViTs achieve impressive performance through image-text pair-based contrastive learning or self-supervised mechanisms, they struggle to engage in connector-based co-training directly with LLMs due to potential parameter initialization conflicts and modality semantic gaps. To address the above challenges, this paper proposes SAILViT, a gradual feature learning-enhanced ViT for facilitating MLLMs to break through performance bottlenecks in complex multimodal interactions. SAILViT achieves coarse-to-fine-grained feature alignment and world knowledge infusion with gradual feature refinement, which better serves target training demands. We perform thorough empirical analyses to confirm the powerful robustness and generalizability of SAILViT across different dimensions, including parameter sizes, model architectures, training strategies, and data scales. Equipped with SAILViT, existing MLLMs show significant and consistent performance improvements on the OpenCompass benchmark across extensive downstream tasks. SAILViT series models are released at https://huggingface.co/BytedanceDouyinContent.

[Arxiv](https://arxiv.org/abs/2507.01643)