# 诱导2:4稀疏性的近端算子

发布时间：2025年01月29日

`LLM理论

理由：这篇论文主要讨论了通过正则化器和局部平方损失优化稀疏矩阵乘法的方法，并将其应用于大型语言模型的修剪。虽然涉及到了大型语言模型的应用，但核心内容更偏向于理论层面的优化方法推导和验证，因此归类为LLM理论更为合适。` `人工智能` `硬件加速`

> A Proximal Operator for Inducing 2:4-Sparsity

# 摘要

> # 摘要
近年来，AI加速器和GPU的硬件进步使得稀疏矩阵乘法能够高效计算，尤其是在连续四个权重中有两个为零的情况下。然而，这种2:4稀疏性通常会降低模型的准确性。我们提出了一种正则化器，利用特征的局部相关性来优化训练模型中的稀疏掩码。通过推导近端算子，我们最小化了正则化器和局部平方损失，并证明在2:4稀疏情况下存在高效解。优化掩码后，我们使用掩码梯度更新进一步减少局部平方损失。我们在小规模问题上验证了该方法，并将其应用于修剪参数高达700亿的大型语言模型。在130亿参数的模型上，我们的方法超越了现有最优算法，而在700亿参数的模型上，我们与其性能相当。

> Recent hardware advancements in AI Accelerators and GPUs allow to efficiently compute sparse matrix multiplications, especially when 2 out of 4 consecutive weights are set to zero. However, this so-called 2:4 sparsity usually comes at a decreased accuracy of the model. We derive a regularizer that exploits the local correlation of features to find better sparsity masks in trained models. We minimize the regularizer jointly with a local squared loss by deriving the proximal operator for which we show that it has an efficient solution in the 2:4-sparse case. After optimizing the mask, we use maskedgradient updates to further minimize the local squared loss. We illustrate our method on toy problems and apply it to pruning entire large language models up to 70B parameters. On models up to 13B we improve over previous state of the art algorithms, whilst on 70B models we match their performance.

[Arxiv](https://arxiv.org/abs/2501.18015)