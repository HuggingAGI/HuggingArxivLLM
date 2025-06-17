# MaskPro：面向大型语言模型的严格(N:M)稀疏性线性空间概率学习方法

发布时间：2025年06月15日

`LLM理论` `模型优化`

> MaskPro: Linear-Space Probabilistic Learning for Strict (N:M)-Sparsity on Large Language Models

# 摘要

> 大型语言模型（LLMs）的快速扩展使得推理效率成为实际部署中的关键瓶颈。为解决这一问题，我们提出了一种半结构化稀疏性方法，通过在每M个权重中保留N个元素，实现硬件友好加速和内存优化。然而，现有的(N:M)稀疏性方法主要分为两类：基于规则的逐层贪心搜索，存在较大误差；以及基于梯度的组合学习，训练成本高昂。为此，我们提出了一种名为MaskPro的新型线性空间概率框架，通过为每M个连续权重学习先验类别分布，并利用该分布通过N路无放回采样生成整个(N:M)稀疏性。此外，为缓解超大规模组合空间中策略梯度高方差引发的训练不稳定性，我们提出了一种新型更新方法，通过引入损失残差的移动平均追踪器替代传统损失函数。最后，通过全面的理论分析和广泛实验，我们验证了MaskPro的优越性能、内存效率的出色扩展性以及对数据样本的卓越鲁棒性。我们的代码已开源，地址为https://github.com/woodenchild95/Maskpro.git。

> The rapid scaling of large language models (LLMs) has made inference efficiency a primary bottleneck in the practical deployment. To address this, semi-structured sparsity offers a promising solution by strategically retaining $N$ elements out of every $M$ weights, thereby enabling hardware-friendly acceleration and reduced memory. However, existing (N:M)-compatible approaches typically fall into two categories: rule-based layerwise greedy search, which suffers from considerable errors, and gradient-driven combinatorial learning, which incurs prohibitive training costs. To tackle these challenges, we propose a novel linear-space probabilistic framework named MaskPro, which aims to learn a prior categorical distribution for every $M$ consecutive weights and subsequently leverages this distribution to generate the (N:M)-sparsity throughout an $N$-way sampling without replacement. Furthermore, to mitigate the training instability induced by the high variance of policy gradients in the super large combinatorial space, we propose a novel update method by introducing a moving average tracker of loss residuals instead of vanilla loss. Finally, we conduct comprehensive theoretical analysis and extensive experiments to validate the superior performance of MaskPro, as well as its excellent scalability in memory efficiency and exceptional robustness to data samples. Our code is available at https://github.com/woodenchild95/Maskpro.git.

[Arxiv](https://arxiv.org/abs/2506.12876)