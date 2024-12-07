# 借助旋转技巧对向量量化进行重构

发布时间：2024年10月08日

`其他` `计算机视觉`

> Restructuring Vector Quantization with the Rotation Trick

# 摘要

> 摘要：向量量化变分自编码器（VQ-VAEs）旨在把连续输入压缩至离散潜在空间，并以最小失真进行重建。其运作方式是维护一组向量（常称为码本），将每个编码器输出量化为码本中距离最近的向量。然而，向量量化不可微，编码器的梯度绕着向量量化层流动，而非在直通近似中直接穿过。这种近似不太理想，因为向量量化操作的所有信息都丢失了。在本研究中，我们提出了一种让梯度通过 VQ-VAEs 向量量化层的方法。我们通过旋转和重新缩放的线性变换，将每个编码器输出平滑地转变为对应的码本向量，在反向传播时将其视作常量。这样，当梯度通过向量量化层回传至编码器时，编码器输出与码本向量之间的相对大小和角度就被编码进了梯度中。在 11 种不同的 VQ-VAE 训练范式中，我们发现这种重构提升了重建指标、码本利用率和量化误差。我们的代码可在这个 https URL 获取。

> 
Abstract:Vector Quantized Variational AutoEncoders (VQ-VAEs) are designed to compress a continuous input to a discrete latent space and reconstruct it with minimal distortion. They operate by maintaining a set of vectors -- often referred to as the codebook -- and quantizing each encoder output to the nearest vector in the codebook. However, as vector quantization is non-differentiable, the gradient to the encoder flows around the vector quantization layer rather than through it in a straight-through approximation. This approximation may be undesirable as all information from the vector quantization operation is lost. In this work, we propose a way to propagate gradients through the vector quantization layer of VQ-VAEs. We smoothly transform each encoder output into its corresponding codebook vector via a rotation and rescaling linear transformation that is treated as a constant during backpropagation. As a result, the relative magnitude and angle between encoder output and codebook vector becomes encoded into the gradient as it propagates through the vector quantization layer and back to the encoder. Across 11 different VQ-VAE training paradigms, we find this restructuring improves reconstruction metrics, codebook utilization, and quantization error. Our code is available at this https URL.
    

[Arxiv](https://arxiv.org/pdf/2410.06424)