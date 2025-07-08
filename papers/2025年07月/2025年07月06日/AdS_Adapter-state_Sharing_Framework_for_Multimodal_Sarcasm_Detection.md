# AdS：多模态讽刺检测的适配器状态共享框架

发布时间：2025年07月06日

`LLM应用` `社交媒体` `计算机视觉`

> AdS: Adapter-state Sharing Framework for Multimodal Sarcasm Detection

# 摘要

> 多模态图像文本讽刺在社交媒体上的普及为观点挖掘带来了挑战，尤其是在资源受限的场景下。现有方法依赖于对大型预训练模型进行完整的微调，这使得它们难以在低资源环境下应用。尽管近期的参数高效微调（PEFT）方法展现出潜力，但它们在复杂任务如讽刺检测中的现成应用表现并不理想。我们提出AdS（适配器-状态共享），一个基于CLIP的轻量级框架。该框架仅在高层插入适配器，并引入了一种新颖的适配器-状态共享机制，其中文本适配器引导视觉适配器。这种设计不仅促进了高效跨模态学习，还保留了低级单模态表示。在两个公共基准上的实验表明，AdS在使用远少于现有PEFT和完整微调方法的可训练参数的情况下，实现了最先进的结果。

> The growing prevalence of multimodal image-text sarcasm on social media poses challenges for opinion mining, especially under resource constraints. Existing approaches rely on full fine-tuning of large pre-trained models, making them unsuitable for low-resource settings. While recent parameter-efficient fine-tuning (PEFT) methods offer promise, their off-the-shelf use underperforms on complex tasks like sarcasm detection. We propose AdS (Adapter-State Sharing), a lightweight framework built on CLIP that inserts adapters only in the upper layers and introduces a novel adapter-state sharing mechanism, where textual adapters guide visual ones. This design promotes efficient cross-modal learning while preserving low-level unimodal representations. Experiments on two public benchmarks demonstrate that AdS achieves state-of-the-art results using significantly fewer trainable parameters than existing PEFT and full fine-tuning approaches.

[Arxiv](https://arxiv.org/abs/2507.04508)