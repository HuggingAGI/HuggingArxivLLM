# ProtDAT：用于从任何蛋白质文本描述来设计蛋白质序列的统一框架

发布时间：2024年12月05日

`LLM应用` `药物开发` `蛋白质设计`

> ProtDAT: A Unified Framework for Protein Sequence Design from Any Protein Text Description

# 摘要

> 蛋白质设计已成为关键手段，在药物开发、酶工程等众多应用领域展现出巨大潜力。然而，仅依靠预训练和微调大型语言模型的蛋白质设计方法，难以捕捉多模态蛋白质数据中的关系。为此，我们提出了 ProtDAT，这是一个全新的细粒度框架，能够依据任何描述性蛋白质文本输入来设计蛋白质。ProtDAT 基于蛋白质数据的固有特性，将序列和文本整合成一个紧密的整体，而非独立的个体。它借助创新的多模态交叉注意力，在基础层面实现了蛋白质序列和文本信息的无缝融合。实验结果显示，ProtDAT 在蛋白质序列生成方面达到了顶尖水平，在合理性、功能性、结构相似性和有效性方面表现卓越。在来自 Swiss-Prot 的 20,000 个文本 - 序列对中，它使 pLDDT 提升了 6％，TM 分数提高了 0.26，RMSD 降低了 1.2 Å，凸显了其推动蛋白质设计的潜力。

> Protein design has become a critical method in advancing significant potential for various applications such as drug development and enzyme engineering. However, protein design methods utilizing large language models with solely pretraining and fine-tuning struggle to capture relationships in multi-modal protein data. To address this, we propose ProtDAT, a de novo fine-grained framework capable of designing proteins from any descriptive protein text input. ProtDAT builds upon the inherent characteristics of protein data to unify sequences and text as a cohesive whole rather than separate entities. It leverages an innovative multi-modal cross-attention, integrating protein sequences and textual information for a foundational level and seamless integration. Experimental results demonstrate that ProtDAT achieves the state-of-the-art performance in protein sequence generation, excelling in rationality, functionality, structural similarity, and validity. On 20,000 text-sequence pairs from Swiss-Prot, it improves pLDDT by 6%, TM-score by 0.26, and reduces RMSD by 1.2 Å, highlighting its potential to advance protein design.

[Arxiv](https://arxiv.org/abs/2412.04069)