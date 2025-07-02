# 语言解锁的ViT（LUViT）：利用LLMs赋能自监督视觉变换器

发布时间：2025年07月01日

`LLM应用` `多模态`

> Language-Unlocked ViT (LUViT): Empowering Self-Supervised Vision Transformers with LLMs

# 摘要

> 将大型语言模型（LLMs）与视觉变压器（ViTs）相结合，在视觉任务中展现了巨大潜力，充分挖掘了LLMs的语义知识和推理能力。然而，LLMs的文本中心预训练与ViTs的视觉中心训练之间存在固有的模态不匹配问题，这是个关键挑战。直接融合方法常无法充分发挥LLMs的潜力，且面临微调不稳定的问题，因此通常的做法是冻结LLM模块，仅训练视觉组件。为解决这一难题，我们提出了语言解锁的视觉变压器（LUViT），这是一种通过协同预训练策略弥合模态不匹配的新方法。LUViT通过以下方式实现：（1）利用掩码自动编码（MAE）预训练ViT以获得更丰富的视觉表示；（2）在LLM模块中同时训练低秩适应（LoRA）层，采用MAE目标。这种联合优化使ViT生成与LLM对齐的特征，并让LLM能够有效解释视觉信息。通过大量实验，我们证明LUViT在各种下游视觉任务中显著提升了性能，展示了利用LLM知识实现视觉理解的一种更高效、更有效的方式。

> The integration of Large Language Model (LLMs) blocks with Vision Transformers (ViTs) holds immense promise for vision-only tasks by leveraging the rich semantic knowledge and reasoning capabilities of LLMs. However, a fundamental challenge lies in the inherent modality mismatch between text-centric pretraining of LLMs and vision-centric training of ViTs. Direct fusion often fails to fully exploit the LLM's potential and suffers from unstable finetuning. As a result, LLM blocks are kept frozen while only the vision components are learned. As a remedy to these challenges, we introduce Language-Unlocked Vision Transformers (LUViT), a novel approach that bridges this modality mismatch through a synergistic pre-training strategy. LUViT co-adapts a ViT backbone and an LLM fusion block by (1) employing Masked Auto-Encoding (MAE) to pre-train the ViT for richer visual representations, and (2) concurrently training Low-Rank Adaptation (LoRA) layers within the LLM block using the MAE objective. This joint optimization guides the ViT to produce LLM-aligned features and the LLM to effectively interpret visual information. We demonstrate through extensive experiments that LUViT significantly improves performance on various downstream vision tasks, showcasing a more effective and efficient pathway to harness LLM knowledge for visual understanding.

[Arxiv](https://arxiv.org/abs/2507.00754)