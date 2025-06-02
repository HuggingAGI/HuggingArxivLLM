# 文档价值评估在大型语言模型摘要生成中的应用：基于聚类夏普利值的方法

发布时间：2025年05月28日

`LLM应用` `互联网` `搜索引擎`

> Document Valuation in LLM Summaries: A Cluster Shapley Approach

# 摘要

> 大型语言模型 (LLMs) 正在被越来越多地用于从多个来源检索和总结内容的系统中，例如搜索引擎和AI助手。虽然这些模型通过生成连贯的摘要提升了用户体验，但它们模糊了原始内容创作者的贡献，引发了关于信用归属和补偿的担忧。我们致力于解决在LLM生成的摘要中评估单个文档价值的挑战。我们提出采用一种基于博弈论的Shapley值方法，根据每个文档的边际贡献来分配信用。虽然Shapley值在理论上具有吸引力，但在大规模计算时成本高昂。因此，我们提出了一种名为Cluster Shapley的高效近似算法，该算法利用文档之间的语义相似性。通过基于LLM的嵌入对文档进行聚类并在集群级别计算Shapley值，我们的方法在显著减少计算量的同时保持了归属质量。我们通过使用亚马逊产品评论的摘要任务展示了我们的方法。Cluster Shapley在保持高精度的同时显著降低了计算复杂度，优于蒙特卡罗采样和Kernel SHAP等基线方法，具有更好的高效前沿。我们的方法与所使用的具体LLM、摘要过程和评估程序无关，这使其可以广泛应用于各种摘要场景。

> Large Language Models (LLMs) are increasingly used in systems that retrieve and summarize content from multiple sources, such as search engines and AI assistants. While these models enhance user experience by generating coherent summaries, they obscure the contributions of original content creators, raising concerns about credit attribution and compensation. We address the challenge of valuing individual documents used in LLM-generated summaries. We propose using Shapley values, a game-theoretic method that allocates credit based on each document's marginal contribution. Although theoretically appealing, Shapley values are expensive to compute at scale. We therefore propose Cluster Shapley, an efficient approximation algorithm that leverages semantic similarity between documents. By clustering documents using LLM-based embeddings and computing Shapley values at the cluster level, our method significantly reduces computation while maintaining attribution quality. We demonstrate our approach to a summarization task using Amazon product reviews. Cluster Shapley significantly reduces computational complexity while maintaining high accuracy, outperforming baseline methods such as Monte Carlo sampling and Kernel SHAP with a better efficient frontier. Our approach is agnostic to the exact LLM used, the summarization process used, and the evaluation procedure, which makes it broadly applicable to a variety of summarization settings.

[Arxiv](https://arxiv.org/abs/2505.23842)