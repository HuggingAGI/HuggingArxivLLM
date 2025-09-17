# 可逆深度平衡模型

发布时间：2025年09月16日

`其他` `基础理论`

> Reversible Deep Equilibrium Models

# 摘要

> 深度平衡模型（DEQs）是一类引人关注的隐式模型，其输出被隐式定义为学习函数的不动点。这类模型在大规模任务中表现优于显式（固定深度）模型，核心在于用多个深层网络换取一个可迭代多次的单层网络。但DEQs的梯度计算是近似的，这往往导致训练动态不稳定，需要通过正则化或多次函数评估来缓解。为此，我们提出可逆深度平衡模型（RevDEQs），它支持精确梯度计算，无需正则化，且函数评估次数远少于DEQs。实验表明，RevDEQs在语言建模和图像分类任务上，相较于同类隐式和显式模型，性能达到了当前最先进水平。

> Deep Equilibrium Models (DEQs) are an interesting class of implicit model where the model output is implicitly defined as the fixed point of a learned function. These models have been shown to outperform explicit (fixed-depth) models in large-scale tasks by trading many deep layers for a single layer that is iterated many times. However, gradient calculation through DEQs is approximate. This often leads to unstable training dynamics and requires regularisation or many function evaluations to fix. Here, we introduce Reversible Deep Equilibrium Models (RevDEQs) that allow for exact gradient calculation, no regularisation and far fewer function evaluations than DEQs. We show that RevDEQs achieve state-of-the-art performance on language modelling and image classification tasks against comparable implicit and explicit models.

[Arxiv](https://arxiv.org/abs/2509.12917)