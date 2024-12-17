# 归一化流属于有生成能力的模型

发布时间：2024年12月09日

`其他`

> Normalizing Flows are Capable Generative Models

# 摘要

> 摘要：归一化流（NFs）是针对连续输入的基于似然的模型，在密度估计和生成建模任务中成果斐然，不过近年来关注度相对较低。在本研究中，我们证实NFs比以往所认为的更具优势。我们推出了TarFlow：一种简便且可扩展的架构，能造就高性能的NF模型。TarFlow可视为掩码自回归流（MAFs）的基于Transformer的变体，由一系列作用于图像块的自回归Transformer块构成，各层之间的自回归方向交替变化。TarFlow易于进行端到端训练，能够直接对像素进行建模和生成。我们还提出了三项提升样本质量的关键技术：训练时的高斯噪声增强、训练后的去噪流程，以及针对有条件和无条件设置的有效引导方法。综合这些，TarFlow在图像似然估计方面创下新的领先成果，大幅超越此前的最佳方法，并且首次通过独立的NF模型生成了质量和多样性可与扩散模型媲美的样本。我们的代码可在这个https URL获取。

> 
Abstract:Normalizing Flows (NFs) are likelihood-based models for continuous inputs. They have demonstrated promising results on both density estimation and generative modeling tasks, but have received relatively little attention in recent years. In this work, we demonstrate that NFs are more powerful than previously believed. We present TarFlow: a simple and scalable architecture that enables highly performant NF models. TarFlow can be thought of as a Transformer-based variant of Masked Autoregressive Flows (MAFs): it consists of a stack of autoregressive Transformer blocks on image patches, alternating the autoregression direction between layers. TarFlow is straightforward to train end-to-end, and capable of directly modeling and generating pixels. We also propose three key techniques to improve sample quality: Gaussian noise augmentation during training, a post training denoising procedure, and an effective guidance method for both class-conditional and unconditional settings. Putting these together, TarFlow sets new state-of-the-art results on likelihood estimation for images, beating the previous best methods by a large margin, and generates samples with quality and diversity comparable to diffusion models, for the first time with a stand-alone NF model. We make our code available at this https URL.
    

[Arxiv](https://arxiv.org/pdf/2412.06329)