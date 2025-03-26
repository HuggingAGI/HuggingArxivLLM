# LoRA雕刻：在多模态大语言模型中融合通用与专业知识

发布时间：2025年03月21日

`LLM理论` `信息检索` `内容生成`

> LoRASculpt: Sculpting LoRA for Harmonizing General and Specialized Knowledge in Multimodal Large Language Models

# 摘要

> 多模态大型语言模型（MLLMs）在跨模态和跨任务的泛化方面表现出色，但如何在保持通用知识的同时有效适应特定下游任务仍具挑战。尽管低秩适应（LoRA）广泛用于获取MLLMs的专用知识，但其在视觉指令微调过程中引入的大量冗余参数会加剧通用知识遗忘并降低下游任务性能。为解决这一问题，我们提出LoRASculpt，通过消除冗余参数实现通用与专用知识的和谐统一。具体而言，我们在LoRA中引入稀疏更新机制，基于理论保证有效丢弃冗余参数。此外，我们提出冲突缓解正则化器来优化LoRA的更新轨迹，缓解与预训练权重的知识冲突。实验结果表明，即使在极高稀疏度（≤5%）下，我们的方法仍能同时提升模型的泛化能力和下游任务性能，有效缓解灾难性遗忘问题并促进MLLMs中的知识和谐。

> While Multimodal Large Language Models (MLLMs) excel at generalizing across modalities and tasks, effectively adapting them to specific downstream tasks while simultaneously retaining both general and specialized knowledge remains challenging. Although Low-Rank Adaptation (LoRA) is widely used to efficiently acquire specialized knowledge in MLLMs, it introduces substantial harmful redundancy during visual instruction tuning, which exacerbates the forgetting of general knowledge and degrades downstream task performance. To address this issue, we propose LoRASculpt to eliminate harmful redundant parameters, thereby harmonizing general and specialized knowledge. Specifically, under theoretical guarantees, we introduce sparse updates into LoRA to discard redundant parameters effectively. Furthermore, we propose a Conflict Mitigation Regularizer to refine the update trajectory of LoRA, mitigating knowledge conflicts with the pretrained weights. Extensive experimental results demonstrate that even at very high degree of sparsity ($\le$ 5%), our method simultaneously enhances generalization and downstream task performance. This confirms that our approach effectively mitigates the catastrophic forgetting issue and further promotes knowledge harmonization in MLLMs.

[Arxiv](https://arxiv.org/abs/2503.16843)