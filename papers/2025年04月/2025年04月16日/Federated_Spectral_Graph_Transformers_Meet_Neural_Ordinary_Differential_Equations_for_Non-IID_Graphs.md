# 联邦频谱图变压器携手神经常微分方程，共探非独立同分布图数据的奥秘

发布时间：2025年04月16日

`其他` `社交网络` `推荐系统`

> Federated Spectral Graph Transformers Meet Neural Ordinary Differential Equations for Non-IID Graphs

# 摘要

> 图神经网络（GNN）研究正快速发展，得益于其从图结构数据中学习分布式表示的能力。然而，集中处理大规模真实世界的图数据进行GNN训练往往面临隐私、监管和商业竞争的挑战。联邦学习（FL）作为一种分布式学习范式，通过协作训练保护数据隐私，提供了解决方案。尽管视觉和语言模型的训练取得了进展，但GNN的联邦学习仍待探索。为应对这一挑战，我们提出了一种基于配备神经常微分方程（ODE）的谱图神经网络的联邦学习方法，展现了在同质和异质图上的优秀效果。该方法能有效处理非独立同分布（non-IID）数据，性能与仅处理IID数据的方法相当。其设计注重隐私保护和带宽优化，适用于社交网络分析、推荐系统和欺诈检测等复杂场景。我们在非IID异质图上的联邦学习取得了显著改进，同时在同质图上也实现了更好的性能。这项工作凸显了联邦学习在复杂图设置中的潜力。开源代码可在GitHub上获取（https://github.com/SpringWiz11/Fed-GNODEFormer）。

> Graph Neural Network (GNN) research is rapidly advancing due to GNNs' capacity to learn distributed representations from graph-structured data. However, centralizing large volumes of real-world graph data for GNN training is often impractical due to privacy concerns, regulatory restrictions, and commercial competition. Federated learning (FL), a distributed learning paradigm, offers a solution by preserving data privacy with collaborative model training. Despite progress in training huge vision and language models, federated learning for GNNs remains underexplored. To address this challenge, we present a novel method for federated learning on GNNs based on spectral GNNs equipped with neural ordinary differential equations (ODE) for better information capture, showing promising results across both homophilic and heterophilic graphs. Our approach effectively handles non-Independent and Identically Distributed (non-IID) data, while also achieving performance comparable to existing methods that only operate on IID data. It is designed to be privacy-preserving and bandwidth-optimized, making it suitable for real-world applications such as social network analysis, recommendation systems, and fraud detection, which often involve complex, non-IID, and heterophilic graph structures. Our results in the area of federated learning on non-IID heterophilic graphs demonstrate significant improvements, while also achieving better performance on homophilic graphs. This work highlights the potential of federated learning in diverse and challenging graph settings. Open-source code available on GitHub (https://github.com/SpringWiz11/Fed-GNODEFormer).

[Arxiv](https://arxiv.org/abs/2504.11808)