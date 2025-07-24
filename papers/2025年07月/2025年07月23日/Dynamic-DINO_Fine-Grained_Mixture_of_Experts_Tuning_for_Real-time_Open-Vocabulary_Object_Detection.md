# 动态-DINO：实时开放词汇对象检测的细粒度专家混合调优

发布时间：2025年07月23日

`LLM应用

LLM应用` `视觉检测` `计算机视觉`

> Dynamic-DINO: Fine-Grained Mixture of Experts Tuning for Real-time Open-Vocabulary Object Detection

# 摘要

> 混合专家（MoE）架构在大型视觉语言模型（LVLMs）中表现出色，但在实时开放词汇目标检测器中的潜力尚未得到探索。本研究深入探讨这一领域，揭示了引人注目的见解。在浅层，专家倾向于与多样化的同伴合作以扩展搜索空间；而在深层，固定的合作结构逐渐形成，每个专家维持2-3个固定合作伙伴，不同的专家组合专门处理特定模式。具体来说，我们提出了Dynamic-DINO，它通过高效的MoE-Tuning策略，将密集型模型Grounding DINO 1.5 Edge扩展为动态推理框架。此外，我们设计了一种粒度分解机制，将基础模型的前馈网络（FFN）分解为多个较小的专家网络，从而扩展子网络的搜索空间。为了避免微调初期性能下降，我们进一步提出了一种预训练权重分配策略，并结合特定的路由初始化。在推理过程中，仅激活与输入相关的专家以形成紧凑的子网络。实验表明，仅使用1.56M开源数据进行预训练的Dynamic-DINO，其性能优于基于私有Grounding20M数据集预训练的Grounding DINO 1.5 Edge.

> The Mixture of Experts (MoE) architecture has excelled in Large Vision-Language Models (LVLMs), yet its potential in real-time open-vocabulary object detectors, which also leverage large-scale vision-language datasets but smaller models, remains unexplored. This work investigates this domain, revealing intriguing insights. In the shallow layers, experts tend to cooperate with diverse peers to expand the search space. While in the deeper layers, fixed collaborative structures emerge, where each expert maintains 2-3 fixed partners and distinct expert combinations are specialized in processing specific patterns. Concretely, we propose Dynamic-DINO, which extends Grounding DINO 1.5 Edge from a dense model to a dynamic inference framework via an efficient MoE-Tuning strategy. Additionally, we design a granularity decomposition mechanism to decompose the Feed-Forward Network (FFN) of base model into multiple smaller expert networks, expanding the subnet search space. To prevent performance degradation at the start of fine-tuning, we further propose a pre-trained weight allocation strategy for the experts, coupled with a specific router initialization. During inference, only the input-relevant experts are activated to form a compact subnet. Experiments show that, pretrained with merely 1.56M open-source data, Dynamic-DINO outperforms Grounding DINO 1.5 Edge, pretrained on the private Grounding20M dataset.

[Arxiv](https://arxiv.org/abs/2507.17436)