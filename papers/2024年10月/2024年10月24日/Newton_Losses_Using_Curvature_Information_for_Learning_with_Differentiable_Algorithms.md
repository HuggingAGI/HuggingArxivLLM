# Newton 损失：借助曲率信息开展可微算法学习

发布时间：2024年10月24日

`其他` `神经网络` `排序算法`

> Newton Losses: Using Curvature Information for Learning with Differentiable Algorithms

# 摘要

> 摘要：在以自定义目标（如排名损失和最短路径损失）训练神经网络时，常见问题在于这些目标本身不可微。流行的做法是持续放宽目标以提供梯度，以实现学习。然而，此类可微放宽往往是非凸的，可能出现梯度消失和爆炸的情况，这使得它们（即便单独来看）都难以优化。在此，损失函数成为训练深度神经网络的瓶颈。我们提出了牛顿损失法，通过利用经验Fisher和Hessian矩阵的二阶信息来提升现有难以优化的损失的性能。我们并非用二阶技术训练神经网络，而是仅利用损失函数的二阶信息将其替换为牛顿损失，同时用梯度下降来训练网络。这让我们的方法计算效率颇高。我们将牛顿损失应用于八种可微的排序和最短路径算法，对优化程度较低的可微算法实现了显著改进，对优化良好的可微算法也实现了持续改进。

> 
Abstract:When training neural networks with custom objectives, such as ranking losses and shortest-path losses, a common problem is that they are, per se, non-differentiable. A popular approach is to continuously relax the objectives to provide gradients, enabling learning. However, such differentiable relaxations are often non-convex and can exhibit vanishing and exploding gradients, making them (already in isolation) hard to optimize. Here, the loss function poses the bottleneck when training a deep neural network. We present Newton Losses, a method for improving the performance of existing hard to optimize losses by exploiting their second-order information via their empirical Fisher and Hessian matrices. Instead of training the neural network with second-order techniques, we only utilize the loss function's second-order information to replace it by a Newton Loss, while training the network with gradient descent. This makes our method computationally efficient. We apply Newton Losses to eight differentiable algorithms for sorting and shortest-paths, achieving significant improvements for less-optimized differentiable algorithms, and consistent improvements, even for well-optimized differentiable algorithms.
    

[Arxiv](https://arxiv.org/pdf/2410.19055)