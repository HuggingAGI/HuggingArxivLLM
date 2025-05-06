# # GRAIL：图编辑距离与节点对齐——利用LLM生成的代码

发布时间：2025年05月04日

`LLM应用

理由：这篇论文主要探讨了如何将大型语言模型（LLMs）应用于图编辑距离（GED）的计算问题，通过结合LLMs和自动提示调优技术，生成计算GED的程序。这种方法属于LLM的具体应用，因此归类为LLM应用。` `图分析` `人工智能`

> GRAIL: Graph Edit Distance and Node Alignment Using LLM-Generated Code

# 摘要

> 图编辑距离（GED）是衡量两个图相似性的常用指标。由于计算最优GED属于NP难问题，研究者们开发了多种神经和非神经启发式方法。尽管神经方法在近似质量上优于传统方法，但它们仍面临三大挑战：（1）依赖难以获取的真实数据；（2）缺乏解释性；（3）跨领域泛化能力不足，需要高昂的重新训练成本。GRAIL的出现彻底改变了这一领域。它摒弃了传统神经模型预测GED的方式，转而结合大型语言模型（LLMs）与自动提示调优技术，生成计算GED的程序。这种从预测到生成的转变带来了诸多优势，包括端到端的可解释性以及无需真实数据监督的自主进化学习机制。通过在七个数据集上的大量实验，GRAIL不仅在预测质量上超越现有最优方法，更实现了对各类图分布的强健跨领域泛化能力。

> Graph Edit Distance (GED) is a widely used metric for measuring similarity between two graphs. Computing the optimal GED is NP-hard, leading to the development of various neural and non-neural heuristics. While neural methods have achieved improved approximation quality compared to non-neural approaches, they face significant challenges: (1) They require large amounts of ground truth data, which is itself NP-hard to compute. (2) They operate as black boxes, offering limited interpretability. (3) They lack cross-domain generalization, necessitating expensive retraining for each new dataset. We address these limitations with GRAIL, introducing a paradigm shift in this domain. Instead of training a neural model to predict GED, GRAIL employs a novel combination of large language models (LLMs) and automated prompt tuning to generate a program that is used to compute GED. This shift from predicting GED to generating programs imparts various advantages, including end-to-end interpretability and an autonomous self-evolutionary learning mechanism without ground-truth supervision. Extensive experiments on seven datasets confirm that GRAIL not only surpasses state-of-the-art GED approximation methods in prediction quality but also achieves robust cross-domain generalization across diverse graph distributions.

[Arxiv](https://arxiv.org/abs/2505.02124)