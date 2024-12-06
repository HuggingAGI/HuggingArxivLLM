# TrAct：让第一层预激活具备可训练性

发布时间：2024年10月31日

`其他` `模型训练`

> TrAct: Making First-layer Pre-Activations Trainable

# 摘要

> 摘要：我们着眼于视觉模型第一层的训练，发现像素值与梯度更新幅度存在清晰的关联：按定义，抵达第一层权重的梯度与（归一化的）输入像素值直接成正比。所以，对比度低的图像对学习的影响小于对比度高的图像，而非常亮或非常暗的图像对权重的影响则大于中等亮度的图像。在本研究中，我们提议对模型第一层生成的嵌入执行梯度下降。但对于视觉模型而言，切换到带有嵌入层的离散输入并非合理之选。于是，我们提出了这样一个概念性流程：（i）在第一层激活上进行梯度下降步骤以构建激活提议；（ii）找到第一层的最优权重，也就是那些能使到激活提议的平方距离最小的权重。我们给出了该流程的闭式解，并在高效计算所有内容的同时针对稳健随机训练对其进行了调整。从经验来看，我们发现 TrAct（训练激活）能将训练速度加快 1.25 倍至 4 倍，同时仅需少量计算开销。我们展示了 TrAct 与不同优化器在包括卷积和变压器架构等一系列不同视觉模型中的效用。

> 
Abstract:We consider the training of the first layer of vision models and notice the clear relationship between pixel values and gradient update magnitudes: the gradients arriving at the weights of a first layer are by definition directly proportional to (normalized) input pixel values. Thus, an image with low contrast has a smaller impact on learning than an image with higher contrast, and a very bright or very dark image has a stronger impact on the weights than an image with moderate brightness. In this work, we propose performing gradient descent on the embeddings produced by the first layer of the model. However, switching to discrete inputs with an embedding layer is not a reasonable option for vision models. Thus, we propose the conceptual procedure of (i) a gradient descent step on first layer activations to construct an activation proposal, and (ii) finding the optimal weights of the first layer, i.e., those weights which minimize the squared distance to the activation proposal. We provide a closed form solution of the procedure and adjust it for robust stochastic training while computing everything efficiently. Empirically, we find that TrAct (Training Activations) speeds up training by factors between 1.25x and 4x while requiring only a small computational overhead. We demonstrate the utility of TrAct with different optimizers for a range of different vision models including convolutional and transformer architectures.
    

[Arxiv](https://arxiv.org/pdf/2410.23970)