# MultiClaimNet：一个多语言事实核查声明集群数据集

发布时间：2025年03月28日

`LLM应用` `事实核查` `多语言处理`

> MultiClaimNet: A Massively Multilingual Dataset of Fact-Checked Claim Clusters

# 摘要

> 在事实核查领域，声明常在不同平台和语言间重复出现，减少这种冗余至关重要。尽管检索已核查的事实声明曾被视为解决方案，但面对未验证声明激增和已核查数据库规模扩大的现状，我们需要更高效、替代性的解决方案。一种有前景的方法是将讨论相同事实的声明自动聚类，以提升检索和验证效率。然而，声明聚类研究受限于缺乏合适的数据集。为解决这一问题，我们推出了 	extit{MultiClaimNet}，这是一个包含三个多语言声明集群数据集的集合，涵盖 86 种语言和多种主题。声明集群通过有限的人工干预从声明匹配对中自动形成。我们利用现有声明匹配数据集构建了 	extit{MultiClaimNet} 中的较小数据集。为构建更大规模的数据集，我们提出并验证了一种方法：通过检索近似最近邻形成候选声明对，并使用大型语言模型进行声明相似性的自动化标注。该数据集包含 85.3 万条以 78 种语言书写的已核查事实声明。我们进一步采用多种聚类技术和句子嵌入模型进行了广泛实验，以建立基线性能。我们的数据集和研究成果为可扩展声明聚类奠定了坚实基础，助力更高效的事实核查流水线。

> In the context of fact-checking, claims are often repeated across various platforms and in different languages, which can benefit from a process that reduces this redundancy. While retrieving previously fact-checked claims has been investigated as a solution, the growing number of unverified claims and expanding size of fact-checked databases calls for alternative, more efficient solutions. A promising solution is to group claims that discuss the same underlying facts into clusters to improve claim retrieval and validation. However, research on claim clustering is hindered by the lack of suitable datasets. To bridge this gap, we introduce \textit{MultiClaimNet}, a collection of three multilingual claim cluster datasets containing claims in 86 languages across diverse topics. Claim clusters are formed automatically from claim-matching pairs with limited manual intervention. We leverage two existing claim-matching datasets to form the smaller datasets within \textit{MultiClaimNet}. To build the larger dataset, we propose and validate an approach involving retrieval of approximate nearest neighbors to form candidate claim pairs and an automated annotation of claim similarity using large language models. This larger dataset contains 85.3K fact-checked claims written in 78 languages. We further conduct extensive experiments using various clustering techniques and sentence embedding models to establish baseline performance. Our datasets and findings provide a strong foundation for scalable claim clustering, contributing to efficient fact-checking pipelines.

[Arxiv](https://arxiv.org/abs/2503.22280)