# 《Splats 之课：在二维监督下由教师引导的 3D 高斯 Splats 生成扩散》

发布时间：2024年11月30日

`其他` `计算机图形学` `三维重建`

> A Lesson in Splats: Teacher-Guided Diffusion for 3D Gaussian Splats Generation with 2D Supervision

# 摘要

> 我们推出了用于高斯斑点的扩散模型——SplatDiffusion，旨在实现从单张图像生成三维结构，化解将 2D 输入升维至 3D 时的不适定性难题。现有的方法多依赖确定性的前馈预测，这限制了其处理由 2D 数据进行 3D 推理时固有的模糊性的能力。近来，扩散模型在作为包括高斯斑点在内的 3D 数据的强大生成模型方面展现出潜力；然而，标准扩散框架通常要求目标信号和去噪信号处于相同模态，鉴于 3D 数据稀缺，这颇具挑战。为应对此问题，我们提出了新颖的训练策略，将去噪模态与监督模态分离。通过用确定性模型作为噪声教师来创建噪声信号，并从单步去噪转变为由图像渲染损失监督的多步去噪，我们的方法相比确定性教师显著提升了性能。另外，我们的方法很灵活，只需稍作调整就能向各种 3D 高斯斑点（3DGS）教师学习；我们超越了作为教师的两个不同确定性模型的性能，证明了我们框架的潜在通用性。我们的方法还融入了一种引导机制，能从多个视图聚合信息，在多个视图可用时提升重建质量。对象级和场景级数据集上的实验结果表明了我们框架的有效性。

> We introduce a diffusion model for Gaussian Splats, SplatDiffusion, to enable generation of three-dimensional structures from single images, addressing the ill-posed nature of lifting 2D inputs to 3D. Existing methods rely on deterministic, feed-forward predictions, which limit their ability to handle the inherent ambiguity of 3D inference from 2D data. Diffusion models have recently shown promise as powerful generative models for 3D data, including Gaussian splats; however, standard diffusion frameworks typically require the target signal and denoised signal to be in the same modality, which is challenging given the scarcity of 3D data. To overcome this, we propose a novel training strategy that decouples the denoised modality from the supervision modality. By using a deterministic model as a noisy teacher to create the noised signal and transitioning from single-step to multi-step denoising supervised by an image rendering loss, our approach significantly enhances performance compared to the deterministic teacher. Additionally, our method is flexible, as it can learn from various 3D Gaussian Splat (3DGS) teachers with minimal adaptation; we demonstrate this by surpassing the performance of two different deterministic models as teachers, highlighting the potential generalizability of our framework. Our approach further incorporates a guidance mechanism to aggregate information from multiple views, enhancing reconstruction quality when more than one view is available. Experimental results on object-level and scene-level datasets demonstrate the effectiveness of our framework.

[Arxiv](https://arxiv.org/abs/2412.00623)