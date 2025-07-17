# MFGDiffusion：掩膜引导烟雾合成，提升森林火灾检测效果

发布时间：2025年07月15日

`其他` `森林防火` `图像生成`

> MFGDiffusion: Mask-Guided Smoke Synthesis for Enhanced Forest Fire Detection

# 摘要

> 山火的最初征兆是烟雾。随着深度学习技术的飞速发展，基于图像的烟雾检测已成为预防和发现森林火灾的关键方法。然而，获取高质量的山火烟雾图像数据十分困难，这成为制约山火烟雾检测效果的重要因素。图像生成模型为合成逼真的烟雾图像提供了可行的解决方案。然而，现有的图像修复模型在生成高质量烟雾表现方面仍存在明显局限性，主要表现为合成烟雾与背景环境的不协调。为了解决这些问题，我们提出了一套全面的森林火灾烟雾图像生成框架。首先，我们利用预训练的分割模型和多模态模型获取烟雾掩膜和图像描述。其次，针对现有图像修复模型对掩膜和带掩膜图像信息利用率不足的问题，我们引入了一种基于掩膜和带掩膜图像特征引导的网络架构。同时，我们提出了一种新的损失函数——掩膜随机差异损失，通过随机扩展和腐蚀掩膜边缘，增强了生成效果在掩膜周边的一致性。最后，为了生成用于后续检测任务的随机掩膜烟雾图像数据集，我们融入了烟雾特征，并采用多模态大语言模型作为筛选工具，以选择多样化且合理的烟雾图像，从而提升了合成数据集的质量。实验结果表明，我们生成的烟雾图像不仅逼真多样，而且能够有效提升山火烟雾检测模型的性能。代码已开源，地址为：https://github.com/wghr123/MFGDiffusion。


> Smoke is the first visible indicator of a wildfire.With the advancement of deep learning, image-based smoke detection has become a crucial method for detecting and preventing forest fires. However, the scarcity of smoke image data from forest fires is one of the significant factors hindering the detection of forest fire smoke. Image generation models offer a promising solution for synthesizing realistic smoke images. However, current inpainting models exhibit limitations in generating high-quality smoke representations, particularly manifesting as inconsistencies between synthesized smoke and background contexts. To solve these problems, we proposed a comprehensive framework for generating forest fire smoke images. Firstly, we employed the pre-trained segmentation model and the multimodal model to obtain smoke masks and image captions.Then, to address the insufficient utilization of masks and masked images by inpainting models, we introduced a network architecture guided by mask and masked image features. We also proposed a new loss function, the mask random difference loss, which enhances the consistency of the generated effects around the mask by randomly expanding and eroding the mask edges.Finally, to generate a smoke image dataset using random masks for subsequent detection tasks, we incorporated smoke characteristics and use a multimodal large language model as a filtering tool to select diverse and reasonable smoke images, thereby improving the quality of the synthetic dataset. Experiments showed that our generated smoke images are realistic and diverse, and effectively enhance the performance of forest fire smoke detection models. Code is available at https://github.com/wghr123/MFGDiffusion.

[Arxiv](https://arxiv.org/abs/2507.11252)