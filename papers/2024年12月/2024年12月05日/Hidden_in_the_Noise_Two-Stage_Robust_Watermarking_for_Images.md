# 《隐匿于噪声：针对图像的两阶段稳健水印技术》

发布时间：2024年12月05日

`其他` `图像生成` `图像水印`

> Hidden in the Noise: Two-Stage Robust Watermarking for Images

# 摘要

> 随着图像生成器质量的持续提升，深度伪造成为社会热议的话题。图像水印技术能让负责的模型所有者检测并标记其人工智能生成的内容，从而减轻危害。然而，当前图像水印技术的前沿方法仍易遭受伪造和去除攻击。这种脆弱性部分源于水印会扭曲生成图像的分布，无意间透露了水印技术的相关信息。
    在本研究中，我们首先展示了一种基于扩散模型初始噪声的无失真图像水印方法。但检测水印需要将图像的初始噪声与所有先前用过的初始噪声进行对比。为解决这些问题，我们提出了一个用于高效检测的两阶段水印框架。在生成阶段，我们用生成的傅里叶模式增强初始噪声，以嵌入关于所用初始噪声组的信息。在检测时，我们（i）检索相关噪声组，（ii）在给定组内搜索可能与图像匹配的初始噪声。这种水印方式在应对大量攻击时，在抗伪造和去除方面达到了领先水平的鲁棒性。

> As the quality of image generators continues to improve, deepfakes become a topic of considerable societal debate. Image watermarking allows responsible model owners to detect and label their AI-generated content, which can mitigate the harm. Yet, current state-of-the-art methods in image watermarking remain vulnerable to forgery and removal attacks. This vulnerability occurs in part because watermarks distort the distribution of generated images, unintentionally revealing information about the watermarking techniques.
  In this work, we first demonstrate a distortion-free watermarking method for images, based on a diffusion model's initial noise. However, detecting the watermark requires comparing the initial noise reconstructed for an image to all previously used initial noises. To mitigate these issues, we propose a two-stage watermarking framework for efficient detection. During generation, we augment the initial noise with generated Fourier patterns to embed information about the group of initial noises we used. For detection, we (i) retrieve the relevant group of noises, and (ii) search within the given group for an initial noise that might match our image. This watermarking approach achieves state-of-the-art robustness to forgery and removal against a large battery of attacks.

[Arxiv](https://arxiv.org/abs/2412.04653)