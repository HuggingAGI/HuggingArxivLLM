# 基于嵌入与聚类的公共数据元素（CDE）语义分组动态框架

发布时间：2025年06月02日

`LLM应用` `医疗健康` `医疗信息化`

> A Dynamic Framework for Semantic Grouping of Common Data Elements (CDE) Using Embeddings and Clustering

# 摘要

> 本研究致力于构建一个动态且可扩展的框架，通过解决语义异质性、结构变异性及上下文依赖性等关键挑战，实现异质性生物医学数据集中公共数据元素 (CDEs) 的有效整合，从而简化数据集成流程、提升互操作性并加速科学发现。我们的方法基于大型语言模型 (LLMs) 的上下文感知文本嵌入技术，将 CDEs 转换为捕获语义关系和模式的密集向量表示。通过层次密度聚类算法 (HDBSCAN)，这些嵌入被聚类以识别语义相似的 CDEs。框架包含四个核心步骤：(1) 基于 LLM 的文本嵌入，用于数学化语义上下文表示；(2) 无监督聚类算法 HDBSCAN 进行嵌入聚类；(3) 利用 LLM 摘要实现自动化标签；(4) 监督学习训练分类器，将新的或未聚类的 CDEs 分配到已标记集群。在 NIH NLM CDE 仓库（包含超过 24,000 个 CDEs）上的评估表明，系统在优化后的最小集群大小为 20 时，识别出 118 个有意义的集群。分类器实现了 90.46% 的总体准确率，在较大类别中表现尤为突出。与 Gravity Projects 的健康社会决定因素领域进行外部验证，结果显示高度一致（调整兰德指数 0.52，归一化互信息 0.78），证实了嵌入方法有效捕获集群特征。这一灵活且可扩展的方法为 CDE 整合提供了一种实用解决方案，显著提升了选择效率并支持持续的数据互操作性。

> This research aims to develop a dynamic and scalable framework to facilitate harmonization of Common Data Elements (CDEs) across heterogeneous biomedical datasets by addressing challenges such as semantic heterogeneity, structural variability, and context dependence to streamline integration, enhance interoperability, and accelerate scientific discovery. Our methodology leverages Large Language Models (LLMs) for context-aware text embeddings that convert CDEs into dense vectors capturing semantic relationships and patterns. These embeddings are clustered using Hierarchical Density-Based Spatial Clustering of Applications with Noise (HDBSCAN) to group semantically similar CDEs. The framework incorporates four key steps: (1) LLM-based text embedding to mathematically represent semantic context, (2) unsupervised clustering of embeddings via HDBSCAN, (3) automated labeling using LLM summarization, and (4) supervised learning to train a classifier assigning new or unclustered CDEs to labeled clusters. Evaluated on the NIH NLM CDE Repository with over 24,000 CDEs, the system identified 118 meaningful clusters at an optimized minimum cluster size of 20. The classifier achieved 90.46 percent overall accuracy, performing best in larger categories. External validation against Gravity Projects Social Determinants of Health domains showed strong agreement (Adjusted Rand Index 0.52, Normalized Mutual Information 0.78), indicating that embeddings effectively capture cluster characteristics. This adaptable and scalable approach offers a practical solution to CDE harmonization, improving selection efficiency and supporting ongoing data interoperability.

[Arxiv](https://arxiv.org/abs/2506.02160)