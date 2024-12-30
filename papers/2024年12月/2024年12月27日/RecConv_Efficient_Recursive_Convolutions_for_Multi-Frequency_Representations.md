# RecConv：实现多频表示的高效递归卷积

发布时间：2024年12月27日

`其他` `计算机视觉` `图像处理`

> RecConv: Efficient Recursive Convolutions for Multi-Frequency Representations

# 摘要

> 近期视觉转换器（ViTs）的进步彰显了其全局建模能力的优势，促使大核卷积被广泛用于扩大有效感受野（ERF）。但参数数量和计算复杂度（FLOPs）随核大小的二次方增长，带来了显著的效率和优化难题。本文引入了 RecConv，这是一种递归分解策略，能利用小核卷积高效构建多频表示。RecConv 在参数增长与分解级别间建立了线性关系，对于基础核 $k$ 和分解级别 $\ell$ 确定了有效核大小 $k×2^\ell$ ，且无论 ERF 如何扩展都能保持 FLOPs 不变。具体来说，相较于标准卷积和深度卷积的指数增长（$4^\ell$），RecConv 仅实现了参数扩展的 $\ell + 2$ 倍和最大 FLOPs 增加的 $5/3$ 倍。RecNeXt-M3 在 FLOPs 相似的情况下，在 COCO 上比 RepViT-M1.1 的 $AP^{box}$ 高出 1.9 。这一创新为设计各种模式下高效紧凑的网络开辟了一条充满希望的道路。代码和模型可在 url{https://github.com/suous/RecNeXt} 获取。

> Recent advances in vision transformers (ViTs) have demonstrated the advantage of global modeling capabilities, prompting widespread integration of large-kernel convolutions for enlarging the effective receptive field (ERF). However, the quadratic scaling of parameter count and computational complexity (FLOPs) with respect to kernel size poses significant efficiency and optimization challenges. This paper introduces RecConv, a recursive decomposition strategy that efficiently constructs multi-frequency representations using small-kernel convolutions. RecConv establishes a linear relationship between parameter growth and decomposing levels which determines the effective kernel size $k\times 2^\ell$ for a base kernel $k$ and $\ell$ levels of decomposition, while maintaining constant FLOPs regardless of the ERF expansion. Specifically, RecConv achieves a parameter expansion of only $\ell+2$ times and a maximum FLOPs increase of $5/3$ times, compared to the exponential growth ($4^\ell$) of standard and depthwise convolutions. RecNeXt-M3 outperforms RepViT-M1.1 by 1.9 $AP^{box}$ on COCO with similar FLOPs. This innovation provides a promising avenue towards designing efficient and compact networks across various modalities. Codes and models can be found at url{https://github.com/suous/RecNeXt}.

[Arxiv](https://arxiv.org/abs/2412.19628)