# Wide & Deep 学习用于节点分类

发布时间：2025年05月04日

`LLM应用` `推荐系统` `社交网络`

> Wide & Deep Learning for Node Classification

# 摘要

> Google 开发的 Wide & Deep 架构是一种简单而有效的推荐系统学习方法，它通过结合广义线性模型的记忆能力和深度模型的泛化能力，在学术界和工业界产生了重要影响。尽管图卷积网络（GCNs）在节点分类任务中表现优异，但近期研究指出异质性和表达性等挑战，这些问题聚焦于图结构，却可能忽略了节点特征的作用。本文提出了一种灵活的 GCNIII 框架，该框架基于 Wide & Deep 架构，并融合了交集记忆、初始残差和身份映射三种技术。通过全面的实证分析，我们证明 GCNIII 在半监督和全监督任务中能够更好地平衡过拟合与过度泛化的矛盾。此外，我们还探索了利用大型语言模型（LLMs）进行节点特征工程，以提升 GCNIII 在跨域节点分类任务中的表现。代码实现已开源，地址为 https://github.com/CYCUCAS/GCNIII。

> Wide & Deep, a simple yet effective learning architecture for recommendation systems developed by Google, has had a significant impact in both academia and industry due to its combination of the memorization ability of generalized linear models and the generalization ability of deep models. Graph convolutional networks (GCNs) remain dominant in node classification tasks; however, recent studies have highlighted issues such as heterophily and expressiveness, which focus on graph structure while seemingly neglecting the potential role of node features. In this paper, we propose a flexible framework GCNIII, which leverages the Wide & Deep architecture and incorporates three techniques: Intersect memory, Initial residual and Identity mapping. We provide comprehensive empirical evidence showing that GCNIII can more effectively balance the trade-off between over-fitting and over-generalization on various semi- and full- supervised tasks. Additionally, we explore the use of large language models (LLMs) for node feature engineering to enhance the performance of GCNIII in cross-domain node classification tasks. Our implementation is available at https://github.com/CYCUCAS/GCNIII.

[Arxiv](https://arxiv.org/abs/2505.02020)