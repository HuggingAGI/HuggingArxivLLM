# 时间提示是否是有限标签动作识别的全部所需？

发布时间：2025年04月02日

`LLM应用` `视频处理` `计算机视觉`

> Is Temporal Prompting All We Need For Limited Labeled Action Recognition?

# 摘要

> 近年来，视频理解领域取得了显著进展，这主要得益于大规模标注数据集的广泛应用。近期，基于对比预训练的视觉-语言模型在零样本任务中展现了卓越的泛化能力，从而有效减少了对标注数据集的依赖。将这些模型应用于视频领域，通常需要对视觉-语言模型的架构进行调整以适应视频数据。然而，这一过程充满挑战，因为这些调整方法不仅计算密集，而且在时间建模方面表现不佳。为此，我们提出了TP-CLIP，这是一种CLIP的适应版本，通过引入时间视觉提示实现时间适应，而无需修改CLIP的核心架构。这一设计保留了CLIP原有的泛化能力。TP-CLIP能够无缝融入CLIP架构，充分利用其预训练功能处理视频数据。通过在多种数据集上的广泛实验，我们验证了TP-CLIP在零样本和少样本学习中的卓越性能。与现有方法相比，TP-CLIP不仅参数更少，而且计算效率更高。特别地，与近期最先进的方法相比，我们仅使用了1/3的GFLOPs和1/28的可调参数数量，但根据不同任务和数据集，仍能超出其性能15.8%。

> Video understanding has shown remarkable improvements in recent years, largely dependent on the availability of large scaled labeled datasets. Recent advancements in visual-language models, especially based on contrastive pretraining, have shown remarkable generalization in zero-shot tasks, helping to overcome this dependence on labeled datasets. Adaptations of such models for videos, typically involve modifying the architecture of vision-language models to cater to video data. However, this is not trivial, since such adaptations are mostly computationally intensive and struggle with temporal modeling. We present TP-CLIP, an adaptation of CLIP that leverages temporal visual prompting for temporal adaptation without modifying the core CLIP architecture. This preserves its generalization abilities. TP-CLIP efficiently integrates into the CLIP architecture, leveraging its pre-trained capabilities for video data. Extensive experiments across various datasets demonstrate its efficacy in zero-shot and few-shot learning, outperforming existing approaches with fewer parameters and computational efficiency. In particular, we use just 1/3 the GFLOPs and 1/28 the number of tuneable parameters in comparison to recent state-of-the-art and still outperform it by up to 15.8% depending on the task and dataset.

[Arxiv](https://arxiv.org/abs/2504.01890)