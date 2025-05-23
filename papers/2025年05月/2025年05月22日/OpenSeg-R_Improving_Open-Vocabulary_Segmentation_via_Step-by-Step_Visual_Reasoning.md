# # OpenSeg-R：逐步视觉推理助力开放词汇分割优化
OpenSeg-R 通过采用逐步的视觉推理策略，有效提升了开放词汇分割的性能表现。

发布时间：2025年05月22日

`其他` `计算机视觉` `人工智能`

> OpenSeg-R: Improving Open-Vocabulary Segmentation via Step-by-Step Visual Reasoning

# 摘要

> 开放词汇分割（OVS）因其超越预定义类别的分割泛化能力而备受关注。然而，现有方法通常通过简单的正向推理预测分割掩膜，缺乏明确的推理过程和可解释性。这使得OVS模型在开放世界设置中难以区分相似类别，因为它们缺乏上下文理解能力和判别性视觉线索。为了解决这一局限性，我们提出了一种用于开放词汇分割的逐步视觉推理框架，名为OpenSeg-R。所提出的OpenSeg-R在分割前利用大规模多模态模型（LMMs）进行层次化视觉推理。具体而言，我们为每张图像生成通用和特定于图像的推理，形成结构化的三元组，以从粗到细的方式解释物体的视觉原因。基于这些推理步骤，我们可以生成详细描述提示，并将其输入分割器以生成更准确的分割掩膜。据我们所知，OpenSeg-R是首个将显式的逐步视觉推理引入OVS的框架。实验结果表明，OpenSeg-R在五个基准数据集上的开放词汇语义分割任务中显著优于现有最先进的方法。此外，它在所有指标上对开放词汇全景分割均实现了稳定提升。定性结果进一步凸显了我们推理引导框架在提高分割精度和可解释性方面的有效性。我们的代码可在https://github.com/Hanzy1996/OpenSeg-R公开获取。

> Open-Vocabulary Segmentation (OVS) has drawn increasing attention for its capacity to generalize segmentation beyond predefined categories. However, existing methods typically predict segmentation masks with simple forward inference, lacking explicit reasoning and interpretability. This makes it challenging for OVS model to distinguish similar categories in open-world settings due to the lack of contextual understanding and discriminative visual cues. To address this limitation, we propose a step-by-step visual reasoning framework for open-vocabulary segmentation, named OpenSeg-R. The proposed OpenSeg-R leverages Large Multimodal Models (LMMs) to perform hierarchical visual reasoning before segmentation. Specifically, we generate both generic and image-specific reasoning for each image, forming structured triplets that explain the visual reason for objects in a coarse-to-fine manner. Based on these reasoning steps, we can compose detailed description prompts, and feed them to the segmentor to produce more accurate segmentation masks. To the best of our knowledge, OpenSeg-R is the first framework to introduce explicit step-by-step visual reasoning into OVS. Experimental results demonstrate that OpenSeg-R significantly outperforms state-of-the-art methods on open-vocabulary semantic segmentation across five benchmark datasets. Moreover, it achieves consistent gains across all metrics on open-vocabulary panoptic segmentation. Qualitative results further highlight the effectiveness of our reasoning-guided framework in improving both segmentation precision and interpretability. Our code is publicly available at https://github.com/Hanzy1996/OpenSeg-R.

[Arxiv](https://arxiv.org/abs/2505.16974)