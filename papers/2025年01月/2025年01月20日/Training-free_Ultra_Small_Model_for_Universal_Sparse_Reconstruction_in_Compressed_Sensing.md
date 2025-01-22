# 无需训练的极小型模型实现压缩感知中的通用稀疏重建

发布时间：2025年01月20日

`其他

理由：这篇论文主要讨论的是压缩感知（CS）和稀疏重建的问题，提出了一种超小型人工神经网络模型——系数学习（CL），并展示了其在稀疏重建中的高效性和准确性。虽然提到了预训练大模型（LLM）的局限性，但论文的核心内容并不直接涉及LLM、Agent、RAG或LLM理论。因此，将其分类为“其他”更为合适。` `物理传感` `医学成像`

> Training-free Ultra Small Model for Universal Sparse Reconstruction in Compressed Sensing

# 摘要

> # 摘要
近年来，预训练大模型备受瞩目，但在高可解释性或资源受限的应用中（如物理传感、医学成像和生物信息学），它们面临挑战。压缩感知（CS）作为一项成熟理论，推动了这些领域的突破。然而，CS作为典型的欠定线性系统，在使用传统迭代方法时，尤其是面对大规模数据时，稀疏重建时间过长。现有的AI方法（如深度展开）难以替代，因为预训练模型在训练条件和数据集分布之外表现不佳，或缺乏可解释性。本文未追随大模型热潮，而是提出了一种超小型人工神经网络模型——系数学习（CL），实现了无需训练、快速稀疏重建，同时完美继承了传统迭代方法的通用性和可解释性，并引入了结合先验知识的新特性。在CL中，长度为$n$的信号仅需$n$个可训练参数。我们实现了一个名为CLOMP的案例模型进行评估。实验在合成和真实的一维、二维信号上进行，结果显示效率和准确性显著提升。与代表性迭代方法相比，CLOMP在大规模数据上的效率提升了100到1000倍。在八个不同图像数据集上的测试表明，CLOMP在采样率为0.1、0.3、0.5时，结构相似性指数分别提升了292%、98%、45%。我们相信，这一方法将真正推动CS重建进入AI时代，惠及无数依赖稀疏解的欠定线性系统。

> Pre-trained large models attract widespread attention in recent years, but they face challenges in applications that require high interpretability or have limited resources, such as physical sensing, medical imaging, and bioinformatics. Compressed Sensing (CS) is a well-proved theory that drives many recent breakthroughs in these applications. However, as a typical under-determined linear system, CS suffers from excessively long sparse reconstruction times when using traditional iterative methods, particularly with large-scale data. Current AI methods like deep unfolding fail to substitute them because pre-trained models exhibit poor generality beyond their training conditions and dataset distributions, or lack interpretability. Instead of following the big model fervor, this paper proposes ultra-small artificial neural models called coefficients learning (CL), enabling training-free and rapid sparse reconstruction while perfectly inheriting the generality and interpretability of traditional iterative methods, bringing new feature of incorporating prior knowledges. In CL, a signal of length $n$ only needs a minimal of $n$ trainable parameters. A case study model called CLOMP is implemented for evaluation. Experiments are conducted on both synthetic and real one-dimensional and two-dimensional signals, demonstrating significant improvements in efficiency and accuracy. Compared to representative iterative methods, CLOMP improves efficiency by 100 to 1000 folds for large-scale data. Test results on eight diverse image datasets indicate that CLOMP improves structural similarity index by 292%, 98%, 45% for sampling rates of 0.1, 0.3, 0.5, respectively. We believe this method can truly usher CS reconstruction into the AI era, benefiting countless under-determined linear systems that rely on sparse solution.

[Arxiv](https://arxiv.org/abs/2501.11592)