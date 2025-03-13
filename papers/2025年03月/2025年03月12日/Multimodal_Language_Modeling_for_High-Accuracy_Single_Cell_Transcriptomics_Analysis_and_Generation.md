# 多模态语言建模助力高精度单细胞转录组学分析与生成

发布时间：2025年03月12日

`LLM应用` `生物医学` `生物信息学`

> Multimodal Language Modeling for High-Accuracy Single Cell Transcriptomics Analysis and Generation

# 摘要

> 预训练语言模型（PLMs）彻底改变了科学研究的方式，但它们在单细胞分析中的应用仍然有限。文本PLMs无法处理单细胞RNA测序数据，而细胞PLMs缺乏处理自由文本的能力，这限制了它们在多模态任务中的应用。现有尝试整合这些模态的努力通常会面临信息丢失或单模态预训练不足的问题，导致性能欠佳。为了解决这些挑战，我们提出了单细胞多模态生成预训练变换器（scMMGPT），一个统一的PLM，用于联合细胞和文本建模。scMMGPT有效地整合了最先进的细胞和文本PLMs，促进跨模态知识共享，从而提升性能。为了弥合文本与细胞之间的模态差距，scMMGPT采用了专用的跨模态投影器，并在包含2700万个细胞的大型数据集上进行了广泛预训练——这是目前用于多模态细胞-文本PLMs的最大数据集。这种大规模预训练使scMMGPT在联合细胞-文本任务中表现出色，实现了细胞描述生成中84%的文本差异相对改进，细胞类型注释准确率提高了20.5%，以及文本条件伪细胞生成中$k$-NN准确率提升了4%，超越了基线模型。

> Pre-trained language models (PLMs) have revolutionized scientific research, yet their application to single-cell analysis remains limited. Text PLMs cannot process single-cell RNA sequencing data, while cell PLMs lack the ability to handle free text, restricting their use in multimodal tasks. Existing efforts to bridge these modalities often suffer from information loss or inadequate single-modal pre-training, leading to suboptimal performances. To address these challenges, we propose Single-Cell MultiModal Generative Pre-trained Transformer (scMMGPT), a unified PLM for joint cell and text modeling. scMMGPT effectively integrates the state-of-the-art cell and text PLMs, facilitating cross-modal knowledge sharing for improved performance. To bridge the text-cell modality gap, scMMGPT leverages dedicated cross-modal projectors, and undergoes extensive pre-training on 27 million cells -- the largest dataset for multimodal cell-text PLMs to date. This large-scale pre-training enables scMMGPT to excel in joint cell-text tasks, achieving an 84\% relative improvement of textual discrepancy for cell description generation, 20.5\% higher accuracy for cell type annotation, and 4\% improvement in $k$-NN accuracy for text-conditioned pseudo-cell generation, outperforming baselines.

[Arxiv](https://arxiv.org/abs/2503.09427)