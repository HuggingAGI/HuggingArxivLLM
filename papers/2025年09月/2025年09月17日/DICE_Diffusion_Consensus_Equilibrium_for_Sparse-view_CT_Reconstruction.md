# DICE：用于稀疏视角CT重建的扩散共识平衡

发布时间：2025年09月17日

`其他` `医疗健康`

> DICE: Diffusion Consensus Equilibrium for Sparse-view CT Reconstruction

# 摘要

> 稀疏视图计算机断层扫描（CT）重建的本质挑战在于欠采样导致的不适定逆问题。传统迭代方法虽通过引入手工设计或学习到的先验来正则化求解，但难以捕捉医学图像中的复杂结构。相比之下，扩散模型（DMs）近年来作为强大的生成先验崭露头角，能够准确建模复杂的图像分布。本研究提出扩散共识平衡（DICE）框架，将双智能体共识平衡整合到扩散模型的采样过程中。DICE通过交替执行以下两个步骤实现：(i) 数据一致性智能体，借助近端算子确保测量一致性；(ii) 先验智能体，由扩散模型在每个采样步骤进行清晰图像估计。通过迭代平衡这两个互补智能体，DICE将强大的生成先验能力与测量一致性有效结合。实验结果显示，在15、30、60个视图（共180个）的均匀和非均匀稀疏视图设置下，DICE重建高质量CT图像的性能显著优于最先进的基线方法，充分证明了其有效性和鲁棒性。

> Sparse-view computed tomography (CT) reconstruction is fundamentally challenging due to undersampling, leading to an ill-posed inverse problem. Traditional iterative methods incorporate handcrafted or learned priors to regularize the solution but struggle to capture the complex structures present in medical images. In contrast, diffusion models (DMs) have recently emerged as powerful generative priors that can accurately model complex image distributions. In this work, we introduce Diffusion Consensus Equilibrium (DICE), a framework that integrates a two-agent consensus equilibrium into the sampling process of a DM. DICE alternates between: (i) a data-consistency agent, implemented through a proximal operator enforcing measurement consistency, and (ii) a prior agent, realized by a DM performing a clean image estimation at each sampling step. By balancing these two complementary agents iteratively, DICE effectively combines strong generative prior capabilities with measurement consistency. Experimental results show that DICE significantly outperforms state-of-the-art baselines in reconstructing high-quality CT images under uniform and non-uniform sparse-view settings of 15, 30, and 60 views (out of a total of 180), demonstrating both its effectiveness and robustness.

[Arxiv](https://arxiv.org/abs/2509.14566)