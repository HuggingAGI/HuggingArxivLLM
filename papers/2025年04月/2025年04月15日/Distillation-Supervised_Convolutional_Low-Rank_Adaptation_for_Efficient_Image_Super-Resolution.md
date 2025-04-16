# 蒸馏监督的卷积低秩适配实现高效图像超分辨率

发布时间：2025年04月15日

`其他` `图像处理` `计算机视觉`

> Distillation-Supervised Convolutional Low-Rank Adaptation for Efficient Image Super-Resolution

# 摘要

> 卷积神经网络（CNN）在图像超分辨率领域得到了广泛应用。然而，基于CNN的方法通常需要更深的网络结构和更大的特征图，这会增加模型复杂度和推理成本。受LoRA在大语言模型微调中的成功应用启发，我们探索将其应用于轻量化模型，并提出了一种名为蒸馏监督卷积低秩适配（DSCLoRA）的方法。这种方法能够在不增加架构复杂度或推理成本的前提下提升模型性能。

具体而言，我们通过将SPAB模块替换为提出的SConvLB模块，并在像素混洗块及其前置卷积层中引入ConvLoRA层，将ConvLoRA集成到高效SR网络SPAN中。DSCLoRA利用低秩分解进行参数更新，并采用基于空间特征亲和力的知识蒸馏策略，将教师模型（预训练的SPAN）的二阶统计信息传递给学生模型（我们的模型）。该方法保留了轻量化模型的核心知识，并在特定条件下促进了最优解的发现。

在基准数据集上的实验表明，DSCLoRA不仅在PSNR和SSIM指标上超越了SPAN，还保持了其高效的推理速度和高质量的图像生成能力。值得注意的是，DSCLoRA在2025年NTIRE高效超分辨率挑战赛的整体性能赛道中排名第一。我们的代码和模型已公开发布在https://github.com/Yaozzz666/DSCF-SR。

> Convolutional neural networks (CNNs) have been widely used in efficient image super-resolution. However, for CNN-based methods, performance gains often require deeper networks and larger feature maps, which increase complexity and inference costs. Inspired by LoRA's success in fine-tuning large language models, we explore its application to lightweight models and propose Distillation-Supervised Convolutional Low-Rank Adaptation (DSCLoRA), which improves model performance without increasing architectural complexity or inference costs. Specifically, we integrate ConvLoRA into the efficient SR network SPAN by replacing the SPAB module with the proposed SConvLB module and incorporating ConvLoRA layers into both the pixel shuffle block and its preceding convolutional layer. DSCLoRA leverages low-rank decomposition for parameter updates and employs a spatial feature affinity-based knowledge distillation strategy to transfer second-order statistical information from teacher models (pre-trained SPAN) to student models (ours). This method preserves the core knowledge of lightweight models and facilitates optimal solution discovery under certain conditions. Experiments on benchmark datasets show that DSCLoRA improves PSNR and SSIM over SPAN while maintaining its efficiency and competitive image quality. Notably, DSCLoRA ranked first in the Overall Performance Track of the NTIRE 2025 Efficient Super-Resolution Challenge. Our code and models are made publicly available at https://github.com/Yaozzz666/DSCF-SR.

[Arxiv](https://arxiv.org/abs/2504.11271)