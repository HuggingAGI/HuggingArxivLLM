# DeepNose：一种能预测人类嗅觉感知的等变卷积神经网络

发布时间：2024年12月11日

`其他` `生物医学`

> DeepNose: An Equivariant Convolutional Neural Network Predictive Of Human Olfactory Percepts

# 摘要

> 摘要：嗅觉系统借助一组气味受体（ORs）的反应来感知分子并形成嗅觉感知。在此，我们假定 ORs 能视作 3D 空间滤波器，能提取与嗅觉系统相关的分子特征，这与其他感觉模式中发现的时空滤波器类似。为构建这些滤波器，我们训练了一个卷积神经网络（CNN）来预测从若干语义数据集中获取的人类嗅觉感知。我们的神经网络 DeepNose 因其等变架构，所产生的反应对分子的方向大致保持不变。我们的网络为不同的嗅觉数据集提供了高保真的感知预测。另外，我们的方法能让我们识别出有助于特定感知描述符的分子特征。由于 DeepNose 网络是按照与生物系统相符的原则设计的，所以我们的方法能为不同的立体异构体预测出不同的感知质量。DeepNose 基于同时处理多个分子的架构，能够推断出气味混合物的感知质量。我们认为，DeepNose 网络能够利用 3D 分子形状为人类的嗅觉感知生成高质量的预测，并助力识别决定气味质量的分子特征。

> 
Abstract:The olfactory system employs responses of an ensemble of odorant receptors (ORs) to sense molecules and to generate olfactory percepts. Here we hypothesized that ORs can be viewed as 3D spatial filters that extract molecular features relevant to the olfactory system, similarly to the spatio-temporal filters found in other sensory modalities. To build these filters, we trained a convolutional neural network (CNN) to predict human olfactory percepts obtained from several semantic datasets. Our neural network, the DeepNose, produced responses that are approximately invariant to the molecules' orientation, due to its equivariant architecture. Our network offers high-fidelity perceptual predictions for different olfactory datasets. In addition, our approach allows us to identify molecular features that contribute to specific perceptual descriptors. Because the DeepNose network is designed to be aligned with the biological system, our approach predicts distinct perceptual qualities for different stereoisomers. The architecture of the DeepNose relying on the processing of several molecules at the same time permits inferring the perceptual quality of odor mixtures. We propose that the DeepNose network can use 3D molecular shapes to generate high-quality predictions for human olfactory percepts and help identify molecular features responsible for odor quality.
    

[Arxiv](https://arxiv.org/pdf/2412.08747)