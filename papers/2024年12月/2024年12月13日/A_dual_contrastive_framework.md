# 一个双重对比框架

发布时间：2024年12月13日

`LLM应用` `多模态` `字幕生成`

> A dual contrastive framework

# 摘要

> 在当下的多模态任务里，模型通常会冻结编码器与解码器，而让中间层适配特定任务的目标，像区域字幕生成。区域级的视觉理解给大规模视觉语言模型带来了巨大挑战。有限的空间感知是已知问题，尤其是粗粒度预训练，更增加了优化潜在表示以达成有效编码器 - 解码器对齐的难度。我们提出了 AlignCap，这是一个旨在通过潜在空间的细粒度对齐来强化区域级理解的框架。我们的方法引入了全新的潜在特征细化模块，能增强条件潜在空间的表示，从而提升区域级字幕生成的性能。我们还提出了创新的对齐策略——语义空间对齐模块，它能提升多模态表示的质量。另外，我们在两个模块中以新颖的方式融入了对比学习，进一步提高区域级字幕生成的性能。为应对空间限制，我们采用通用对象检测（GOD）方法作为数据预处理管道，增强区域级的空间推理能力。大量实验表明，我们的方法在各类任务中显著提升了区域级字幕生成的性能。

> In current multimodal tasks, models typically freeze the encoder and decoder while adapting intermediate layers to task-specific goals, such as region captioning. Region-level visual understanding presents significant challenges for large-scale vision-language models. While limited spatial awareness is a known issue, coarse-grained pretraining, in particular, exacerbates the difficulty of optimizing latent representations for effective encoder-decoder alignment. We propose AlignCap, a framework designed to enhance region-level understanding through fine-grained alignment of latent spaces. Our approach introduces a novel latent feature refinement module that enhances conditioned latent space representations to improve region-level captioning performance. We also propose an innovative alignment strategy, the semantic space alignment module, which boosts the quality of multimodal representations. Additionally, we incorporate contrastive learning in a novel manner within both modules to further enhance region-level captioning performance. To address spatial limitations, we employ a General Object Detection (GOD) method as a data preprocessing pipeline that enhances spatial reasoning at the regional level. Extensive experiments demonstrate that our approach significantly improves region-level captioning performance across various tasks

[Arxiv](https://arxiv.org/abs/2412.10348)