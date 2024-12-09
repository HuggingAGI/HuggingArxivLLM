# DAug：用于放射影像检索与分类的基于扩散的通道增强技术

发布时间：2024年12月06日

`LLM应用` `医学图像`

> DAug: Diffusion-based Channel Augmentation for Radiology Image Retrieval and Classification

# 摘要

> 医学图像理解得细致查看精细的视觉细节，某些特定区域更得格外留意。尽管放射科医生凭借多年经验积累了这方面的专长，但人工智能模型在训练数据有限的情况下，很难学会该关注哪里。这种局限致使医学图像理解的稳健性不尽人意。为应对此问题，我们提出了基于扩散的特征增强（DAug），这是一种便捷的方法，能凭借生成模型的输出提升感知模型的性能。具体而言，我们把放射学图像拓展到多个通道，新增通道为疾病易发病区域的热图。基于扩散的图像到图像转换模型用于依据选定的疾病类别生成这类热图。我们的方法基于这样一个事实：生成模型能学习正常和异常图像的分布，而这种知识对图像理解任务是一种补充。另外，我们提出了图像 - 文本 - 类别混合对比学习，以同时利用文本和类别标签。将这两种新方法相结合，我们的方法在不改变模型架构的情况下超越了基线模型，在医学图像检索和分类任务上达到了顶尖水平。

> Medical image understanding requires meticulous examination of fine visual details, with particular regions requiring additional attention. While radiologists build such expertise over years of experience, it is challenging for AI models to learn where to look with limited amounts of training data. This limitation results in unsatisfying robustness in medical image understanding. To address this issue, we propose Diffusion-based Feature Augmentation (DAug), a portable method that improves a perception model's performance with a generative model's output. Specifically, we extend a radiology image to multiple channels, with the additional channels being the heatmaps of regions where diseases tend to develop. A diffusion-based image-to-image translation model was used to generate such heatmaps conditioned on selected disease classes. Our method is motivated by the fact that generative models learn the distribution of normal and abnormal images, and such knowledge is complementary to image understanding tasks. In addition, we propose the Image-Text-Class Hybrid Contrastive learning to utilize both text and class labels. With two novel approaches combined, our method surpasses baseline models without changing the model architecture, and achieves state-of-the-art performance on both medical image retrieval and classification tasks.

[Arxiv](https://arxiv.org/abs/2412.04828)