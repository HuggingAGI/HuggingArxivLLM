# 量化网络

发布时间：2019年11月21日

`其他` `计算机视觉`

> Quantization Networks

# 摘要

> 摘要：尽管深度神经网络成效显著，但其过高的计算和内存开销，给其在便携式设备上的应用带来严峻挑战。正因如此，能将全精度神经网络转化为低位宽整数版本的低位量化，已成为热门且前景可观的研究方向。现有的方法把网络的低位量化当作近似或优化问题来处理。基于近似的方法会遭遇梯度不匹配的难题，而基于优化的方法仅适用于量化权重，且在训练阶段可能产生高额的计算成本。在本文中，我们把低位量化表述为一个可微的非线性函数（称为量化函数），从而提出一种解读和实现神经网络量化的全新视角。所提出的量化函数能够以无损且端到端的方式进行学习，并且能以简便统一的方式作用于神经网络的任何权重和激活。在图像分类和对象检测任务上开展的大量实验表明，我们的量化网络优于前沿方法。我们坚信，所提出的方法将为神经网络量化的解读带来新的启发。我们的代码可在这个 https URL 获取。

> 
Abstract:Although deep neural networks are highly effective, their high computational and memory costs severely challenge their applications on portable devices. As a consequence, low-bit quantization, which converts a full-precision neural network into a low-bitwidth integer version, has been an active and promising research topic. Existing methods formulate the low-bit quantization of networks as an approximation or optimization problem. Approximation-based methods confront the gradient mismatch problem, while optimization-based methods are only suitable for quantizing weights and could introduce high computational cost in the training stage. In this paper, we propose a novel perspective of interpreting and implementing neural network quantization by formulating low-bit quantization as a differentiable non-linear function (termed quantization function). The proposed quantization function can be learned in a lossless and end-to-end manner and works for any weights and activations of neural networks in a simple and uniform way. Extensive experiments on image classification and object detection tasks show that our quantization networks outperform the state-of-the-art methods. We believe that the proposed method will shed new insights on the interpretation of neural network quantization. Our code is available at this https URL.
    

[Arxiv](https://arxiv.org/pdf/1911.09464)