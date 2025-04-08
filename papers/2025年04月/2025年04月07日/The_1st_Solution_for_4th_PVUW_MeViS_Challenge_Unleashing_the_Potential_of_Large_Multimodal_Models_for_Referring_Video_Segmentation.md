# # 第四届PVUW MeViS挑战赛方案一：挖掘大型多模态模型在视频分割中的潜力

发布时间：2025年04月07日

`LLM应用` `计算机视觉` `视频处理`

> The 1st Solution for 4th PVUW MeViS Challenge: Unleashing the Potential of Large Multimodal Models for Referring Video Segmentation

# 摘要

> 运动表达视频分割旨在根据输入的运动表达对视频中的物体进行分割。与传统的引用视频目标分割（RVOS）不同，它不仅关注运动，还强调多物体表达，因此更具挑战性。最近，大型多模态模型（LMMs）凭借其强大的视觉-语言感知能力，在RVOS领域开始崭露头角。在这项研究中，我们提出了一种简单有效的推理优化方法，以充分释放LMMs在引用视频分割中的潜力。首先，我们采用Sa2VA作为基线模型，这是一种用于图像和视频密集接地理解的统一LMM。其次，在推理过程中，我们对视频帧进行均匀采样，以增强模型对整个视频的理解。最后，我们整合多个专家模型的预测结果，以减少单一模型的错误预测。我们的解决方案在MeViS测试集上达到了61.98%的J&F分数，并在CVPR 2025的第4届PVUW挑战赛MeViS赛道中荣获第一名。

> Motion expression video segmentation is designed to segment objects in accordance with the input motion expressions. In contrast to the conventional Referring Video Object Segmentation (RVOS), it places emphasis on motion as well as multi-object expressions, making it more arduous. Recently, Large Multimodal Models (LMMs) have begun to shine in RVOS due to their powerful vision-language perception capabilities. In this work, we propose a simple and effective inference optimization method to fully unleash the potential of LMMs in referring video segmentation. Firstly, we use Sa2VA as our baseline, which is a unified LMM for dense grounded understanding of both images and videos. Secondly, we uniformly sample the video frames during the inference process to enhance the model's understanding of the entire video. Finally, we integrate the results of multiple expert models to mitigate the erroneous predictions of a single model. Our solution achieved 61.98% J&F on the MeViS test set and ranked 1st place in the 4th PVUW Challenge MeViS Track at CVPR 2025.

[Arxiv](https://arxiv.org/abs/2504.05178)