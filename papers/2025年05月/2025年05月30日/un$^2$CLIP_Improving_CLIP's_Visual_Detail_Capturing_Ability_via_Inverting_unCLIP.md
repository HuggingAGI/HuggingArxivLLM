# un$^2$CLIP：通过反转 unCLIP 增强 CLIP 的视觉细节捕捉能力

发布时间：2025年05月30日

`其他` `多模态`

> un$^2$CLIP: Improving CLIP's Visual Detail Capturing Ability via Inverting unCLIP

# 摘要

> 对比语言-图像预训练（CLIP）作为基础模型，在视觉和多模态任务中表现突出。然而，研究表明CLIP在图像细节区分和密集预测任务中存在不足。针对这一问题，我们提出了一种改进方案，旨在提升CLIP捕捉图像细节的能力。通过研究，我们发现生成模型unCLIP为实现这一目标提供了理想框架。unCLIP基于CLIP图像嵌入训练图像生成器，实质上是对CLIP图像编码器的逆向应用。与CLIP这样的判别模型相比，生成模型更擅长捕捉图像细节，因其训练目标是学习图像的数据分布。此外，unCLIP的条件输入空间与CLIP的原始图像-文本嵌入空间高度一致。基于此，我们提出通过反转unCLIP（命名为un$^2$CLIP）来优化CLIP模型，使其在保持与原文本编码器一致性的同时，获得unCLIP捕捉细节的能力。我们在多个CLIP曾应用的任务上评估了改进后的模型，包括MMVP-VLM基准测试、开放词汇分割任务和多模态语言模型任务。实验结果表明，un$^2$CLIP显著优于原始CLIP及现有改进方法。相关代码和模型已开源，地址为https://github.com/LiYinqi/un2CLIP。

> Contrastive Language-Image Pre-training (CLIP) has become a foundation model and has been applied to various vision and multimodal tasks. However, recent works indicate that CLIP falls short in distinguishing detailed differences in images and shows suboptimal performance on dense-prediction and vision-centric multimodal tasks. Therefore, this work focuses on improving existing CLIP models, aiming to capture as many visual details in images as possible. We find that a specific type of generative models, unCLIP, provides a suitable framework for achieving our goal. Specifically, unCLIP trains an image generator conditioned on the CLIP image embedding. In other words, it inverts the CLIP image encoder. Compared to discriminative models like CLIP, generative models are better at capturing image details because they are trained to learn the data distribution of images. Additionally, the conditional input space of unCLIP aligns with CLIP's original image-text embedding space. Therefore, we propose to invert unCLIP (dubbed un$^2$CLIP) to improve the CLIP model. In this way, the improved image encoder can gain unCLIP's visual detail capturing ability while preserving its alignment with the original text encoder simultaneously. We evaluate our improved CLIP across various tasks to which CLIP has been applied, including the challenging MMVP-VLM benchmark, the dense-prediction open-vocabulary segmentation task, and multimodal large language model tasks. Experiments show that un$^2$CLIP significantly improves the original CLIP and previous CLIP improvement methods. Code and models will be available at https://github.com/LiYinqi/un2CLIP.

[Arxiv](https://arxiv.org/abs/2505.24517)