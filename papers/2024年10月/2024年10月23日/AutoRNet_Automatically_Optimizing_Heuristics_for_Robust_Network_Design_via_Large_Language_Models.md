# AutoRNet: 利用大型语言模型自动优化网络设计的鲁棒性启发式方法

发布时间：2024年10月23日

`LLM应用

理由：这篇论文提出了一个名为AutoRNet的框架，该框架将大型语言模型（LLMs）与进化算法结合，用于生成鲁棒网络设计的启发式方法。这表明LLMs被应用于解决网络设计中的复杂问题，属于LLM在实际问题中的应用，因此分类为“LLM应用”。` `网络优化` `自动化设计`

> AutoRNet: Automatically Optimizing Heuristics for Robust Network Design via Large Language Models

# 摘要

> 构建鲁棒网络因其NP难特性和复杂解空间而极具挑战。现有方法，从手工特征提取到深度学习，虽有所进展，但仍需手动设计和大量标注数据。为此，我们提出AutoRNet框架，将大型语言模型（LLMs）与进化算法结合，生成鲁棒网络设计的启发式方法。我们设计了网络优化策略，为LLMs提供领域特定提示，利用领域知识生成高级启发式。此外，引入自适应适应度函数，在保持度分布的同时平衡收敛性与多样性。AutoRNet在稀疏和密集无标度网络上的评估表明，其减少了对手动设计和大型数据集的需求，表现优于现有方法。

> Achieving robust networks is a challenging problem due to its NP-hard nature and complex solution space. Current methods, from handcrafted feature extraction to deep learning, have made progress but remain rigid, requiring manual design and large labeled datasets. To address these issues, we propose AutoRNet, a framework that integrates large language models (LLMs) with evolutionary algorithms to generate heuristics for robust network design. We design network optimization strategies to provide domain-specific prompts for LLMs, utilizing domain knowledge to generate advanced heuristics. Additionally, we introduce an adaptive fitness function to balance convergence and diversity while maintaining degree distributions. AutoRNet is evaluated on sparse and dense scale-free networks, outperforming current methods by reducing the need for manual design and large datasets.

[Arxiv](https://arxiv.org/abs/2410.17656)