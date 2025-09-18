# 量子变分激活函数为柯尔莫哥洛夫-阿诺德网络注入新动力

发布时间：2025年09月17日

`其他` `基础理论`

> Quantum Variational Activation Functions Empower Kolmogorov-Arnold Networks

# 摘要

> 变分量子电路（VQCs）是量子机器学习的核心，而柯尔莫哥洛夫-阿诺德网络（KANs）的最新进展则彰显了可学习激活函数的强大潜力。为此，我们提出量子变分激活函数（QVAFs）以整合这些方向，其通过名为数据重上传激活（DARUANs）的单量子比特数据重上传电路实现。研究发现，在数据预处理中引入可训练权重的DARUAN，其频谱会随数据重复次数呈指数增长；与基于傅里叶的激活函数相比，该方法能在不损失表达能力的前提下，实现参数规模的指数级缩减。将DARUAN嵌入KANs后，便得到量子启发的KANs（QKANs）。这种QKANs既保留了KANs的可解释性，又提升了其参数效率、表达能力与泛化能力。为提升可扩展性、可行性与计算效率，我们进一步提出两种新技术：层扩展与混合QKANs（HQKANs），后者可直接替代大规模模型前馈网络中的多层感知器（MLPs）。我们在函数回归、图像分类及自回归生成语言建模任务上进行了理论分析与大量实验，结果证实了QKANs的高效性与可扩展性。DARUANs与QKANs为在含噪声中等规模量子（NISQ）硬件及经典量子模拟器上推动量子机器学习发展开辟了广阔前景。

> Variational quantum circuits (VQCs) are central to quantum machine learning, while recent progress in Kolmogorov-Arnold networks (KANs) highlights the power of learnable activation functions. We unify these directions by introducing quantum variational activation functions (QVAFs), realized through single-qubit data re-uploading circuits called DatA Re-Uploading ActivatioNs (DARUANs). We show that DARUAN with trainable weights in data pre-processing possesses an exponentially growing frequency spectrum with data repetitions, enabling an exponential reduction in parameter size compared with Fourier-based activations without loss of expressivity. Embedding DARUAN into KANs yields quantum-inspired KANs (QKANs), which retain the interpretability of KANs while improving their parameter efficiency, expressivity, and generalization. We further introduce two novel techniques to enhance scalability, feasibility and computational efficiency, such as layer extension and hybrid QKANs (HQKANs) as drop-in replacements of multi-layer perceptrons (MLPs) for feed-forward networks in large-scale models. We provide theoretical analysis and extensive experiments on function regression, image classification, and autoregressive generative language modeling, demonstrating the efficiency and scalability of QKANs. DARUANs and QKANs offer a promising direction for advancing quantum machine learning on both noisy intermediate-scale quantum (NISQ) hardware and classical quantum simulators.

[Arxiv](https://arxiv.org/abs/2509.14026)