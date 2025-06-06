# # 用视觉语言提示，参考任何内容
只需一个视觉语言提示，即可参考任何内容。

发布时间：2025年06月05日

`LLM应用` `计算机视觉` `人工智能`

> Refer to Anything with Vision-Language Prompts

# 摘要

> 近期，图像分割模型已能生成高质量的视觉实体掩膜，但它们无法为复杂的视觉-语言查询提供全面的语义理解。这一局限性限制了它们在用户友好型视觉-语言交互应用中的效果。为解决这一问题，我们提出了一种全新的任务——全模态指代表达分割（ORES）。在ORES任务中，模型可以根据纯文本或结合参考视觉实体的提示生成多组掩膜。针对这一挑战，我们开发了一种名为“引用任意分割掩膜组”（RAS）的创新框架。该框架通过以掩膜为中心的大型多模态模型，增强了分割模型对复杂多模态交互的理解能力。为训练和评估ORES模型，我们构建了MaskGroups-2M和MaskGroups-HQ两个数据集，其中包含由文本和参考实体定义的多样化掩膜组。通过全面的实验，我们证明了RAS在ORES新任务中的卓越性能，同时也展现了其在经典指代表达分割（RES）和广义指代表达分割（GRES）任务中的优势。项目页面：https://Ref2Any.github.io。

> Recent image segmentation models have advanced to segment images into high-quality masks for visual entities, and yet they cannot provide comprehensive semantic understanding for complex queries based on both language and vision. This limitation reduces their effectiveness in applications that require user-friendly interactions driven by vision-language prompts. To bridge this gap, we introduce a novel task of omnimodal referring expression segmentation (ORES). In this task, a model produces a group of masks based on arbitrary prompts specified by text only or text plus reference visual entities. To address this new challenge, we propose a novel framework to "Refer to Any Segmentation Mask Group" (RAS), which augments segmentation models with complex multimodal interactions and comprehension via a mask-centric large multimodal model. For training and benchmarking ORES models, we create datasets MaskGroups-2M and MaskGroups-HQ to include diverse mask groups specified by text and reference entities. Through extensive evaluation, we demonstrate superior performance of RAS on our new ORES task, as well as classic referring expression segmentation (RES) and generalized referring expression segmentation (GRES) tasks. Project page: https://Ref2Any.github.io.

[Arxiv](https://arxiv.org/abs/2506.05342)