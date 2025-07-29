# 分分钟翻倍你的数据：利用 LLM 诱导的依赖图实现超快速表格数据生成

发布时间：2025年07月25日

`LLM应用` `数据增强` `数据生成`

> Doubling Your Data in Minutes: Ultra-fast Tabular Data Generation via LLM-Induced Dependency Graphs

# 摘要

> 表格数据在众多领域中发挥着关键作用，但高质量数据集的匮乏问题却因隐私顾虑和收集成本而难以解决。目前，基于大型语言模型（LLMs）的表格增强方法虽然取得了一定进展，但仍面临两大挑战：一是表格特征间的密集依赖关系可能导致偏差，二是采样过程的计算开销过高。针对这些问题，我们提出了SPADA（基于稀疏依赖的增强框架），这是一个轻量级的生成框架，通过LLM诱导的图结构显式捕捉稀疏依赖关系。具体而言，我们将每个特征视为图中的一个节点，并通过遍历图结构来生成新的特征值，且每个特征的生成仅依赖其父节点。在合成策略方面，我们探索了两种方法：一种是非参数方法，采用高斯核密度估计；另一种是条件归一化流模型，通过学习可逆映射实现条件密度估计。实验结果表明，在四个不同数据集上，SPADA相较于基于扩散的方法，将约束违规率降低了4%，并且与传统的LLM基线方法相比，生成速度提升了近9,500倍。

> Tabular data is critical across diverse domains, yet high-quality datasets remain scarce due to privacy concerns and the cost of collection. Contemporary approaches adopt large language models (LLMs) for tabular augmentation, but exhibit two major limitations: (1) dense dependency modeling among tabular features that can introduce bias, and (2) high computational overhead in sampling. To address these issues, we propose SPADA for SPArse Dependency-driven Augmentation, a lightweight generative framework that explicitly captures sparse dependencies via an LLM-induced graph. We treat each feature as a node and synthesize values by traversing the graph, conditioning each feature solely on its parent nodes. We explore two synthesis strategies: a non-parametric method using Gaussian kernel density estimation, and a conditional normalizing flow model that learns invertible mappings for conditional density estimation. Experiments on four datasets show that SPADA reduces constraint violations by 4% compared to diffusion-based methods and accelerates generation by nearly 9,500 times over LLM-based baselines.

[Arxiv](https://arxiv.org/abs/2507.19334)