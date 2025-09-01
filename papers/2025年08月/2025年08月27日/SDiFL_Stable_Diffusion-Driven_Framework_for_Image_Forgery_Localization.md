# SDiFL：稳定扩散驱动的图像伪造定位框架

发布时间：2025年08月27日

`其他` `媒体与娱乐`

> SDiFL: Stable Diffusion-Driven Framework for Image Forgery Localization

# 摘要

> 在Stable Diffusion（SD）等新一代多模态大模型的驱动下，图像编辑技术飞速发展，给图像取证领域带来了严峻挑战。然而，现有的图像伪造定位方法高度依赖人工密集、成本高昂的标注数据，难以跟上这些新兴图像编辑技术的发展速度。为解决这些难题，我们首次将SD的图像生成能力与强大感知能力融入图像取证框架，实现了更高效、更精准的伪造定位。首先，我们从理论上证明，SD的多模态架构可通过伪造相关信息进行条件控制，从而使模型能够直接输出伪造定位结果。在此基础上，我们进一步利用Stable DiffusionV3（SD3）的多模态框架来提升伪造定位性能：将图像伪造残差（即通过特定高通滤波器提取的高频信号）作为显式模态，以此充分利用SD3在潜在空间中的多模态处理能力，并在训练时将该模态融合到潜在空间，进而提升伪造定位效果。值得一提的是，我们的方法完整保留了SD3提取的潜在特征，从而保留了输入图像的丰富语义信息。实验结果显示，与当前最先进的图像伪造定位模型相比，我们的框架在主流基准数据集上性能提升高达12%；更令人振奋的是，该模型在处理真实世界文档伪造图像和自然场景伪造图像的取证任务时表现卓越，即便这些数据在训练中完全未曾见过。

> Driven by the new generation of multi-modal large models, such as Stable Diffusion (SD), image manipulation technologies have advanced rapidly, posing significant challenges to image forensics. However, existing image forgery localization methods, which heavily rely on labor-intensive and costly annotated data, are struggling to keep pace with these emerging image manipulation technologies. To address these challenges, we are the first to integrate both image generation and powerful perceptual capabilities of SD into an image forensic framework, enabling more efficient and accurate forgery localization. First, we theoretically show that the multi-modal architecture of SD can be conditioned on forgery-related information, enabling the model to inherently output forgery localization results. Then, building on this foundation, we specifically leverage the multimodal framework of Stable DiffusionV3 (SD3) to enhance forgery localization performance.We leverage the multi-modal processing capabilities of SD3 in the latent space by treating image forgery residuals -- high-frequency signals extracted using specific highpass filters -- as an explicit modality. This modality is fused into the latent space during training to enhance forgery localization performance. Notably, our method fully preserves the latent features extracted by SD3, thereby retaining the rich semantic information of the input image. Experimental results show that our framework achieves up to 12% improvements in performance on widely used benchmarking datasets compared to current state-of-the-art image forgery localization models. Encouragingly, the model demonstrates strong performance on forensic tasks involving real-world document forgery images and natural scene forging images, even when such data were entirely unseen during training.

[Arxiv](https://arxiv.org/abs/2508.20182)