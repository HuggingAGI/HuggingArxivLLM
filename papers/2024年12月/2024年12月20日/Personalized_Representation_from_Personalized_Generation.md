# 来自个性化生成的个性化表征

发布时间：2024年12月20日

`LLM应用` `个性化任务`

> Personalized Representation from Personalized Generation

# 摘要

> 摘要：现代视觉模型在通用下游任务中表现卓越。然而，如何将其用于个性化视觉任务尚不明确，这类任务既精细又数据稀缺。近期的研究已成功把合成数据用于通用表示学习，T2I 扩散模型的进步也能仅依据少量真实示例生成个性化图像。在此，我们探寻这些理念之间的潜在关联，明确提出利用个性化合成数据学习个性化表示这一挑战，此类表示编码了有关感兴趣对象的知识，且能灵活应用于与目标对象相关的任何下游任务。我们为这一挑战引入了一套评估方案，包括对两个现有数据集的重新构建以及一个专门为此构建的新数据集，并提出一种创新利用图像生成器的对比学习方法。我们表明，我们的方法提升了从识别到分割等各类下游任务的个性化表示学习效果，并分析了对这种提升至关重要的图像生成方法的特点。

> 
Abstract:Modern vision models excel at general purpose downstream tasks. It is unclear, however, how they may be used for personalized vision tasks, which are both fine-grained and data-scarce. Recent works have successfully applied synthetic data to general-purpose representation learning, while advances in T2I diffusion models have enabled the generation of personalized images from just a few real examples. Here, we explore a potential connection between these ideas, and formalize the challenge of using personalized synthetic data to learn personalized representations, which encode knowledge about an object of interest and may be flexibly applied to any downstream task relating to the target object. We introduce an evaluation suite for this challenge, including reformulations of two existing datasets and a novel dataset explicitly constructed for this purpose, and propose a contrastive learning approach that makes creative use of image generators. We show that our method improves personalized representation learning for diverse downstream tasks, from recognition to segmentation, and analyze characteristics of image generation approaches that are key to this gain.
    

[Arxiv](https://arxiv.org/pdf/2412.16156)