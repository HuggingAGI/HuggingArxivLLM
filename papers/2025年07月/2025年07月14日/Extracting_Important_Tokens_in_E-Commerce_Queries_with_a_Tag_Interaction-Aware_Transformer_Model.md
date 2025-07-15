# 电商查询关键令牌提取：标签交互感知的Transformer模型

发布时间：2025年07月14日

`LLM应用

理由：这篇论文主要探讨了如何将基于变压器的语言模型（如BERT）应用于电子商务搜索引擎中的查询改写任务，以提高检索的准确性。具体来说，作者通过引入语义标签来提升查询短语嵌入的质量，从而优化搜索结果。这属于将大型语言模型应用于特定任务的范畴，因此归类为LLM应用。` `电子商务` `搜索引擎`

> Extracting Important Tokens in E-Commerce Queries with a Tag Interaction-Aware Transformer Model

# 摘要

> 电子商务搜索引擎的核心使命是精准检索与用户查询意图高度契合的最相关商品。这一任务充满挑战，原因包括模糊查询、买家与卖家间的词汇鸿沟，以及由于令牌数量过多或过少导致的查询过于宽泛或狭窄。为应对这些挑战，我们引入查询改写技术，通过删除、替换或扩展查询中的令牌来优化查询，以弥合查询与用户真实意图间的语义鸿沟。早期方法主要依赖于统计量度，从具有点击或购买行为的用户会话中提取令牌共现频率。近年来，基于变压器的深度学习模型，如神经语言模型或序列到序列模型，成为处理查询改写的主流工具。然而，这些模型未能充分利用令牌的语义标签，而这对于捕捉电子商务场景下的用户意图至关重要。在本研究中，我们将查询改写重新定义为一个令牌分类任务，并开发了一种基于依赖感知的变压器语言模型——TagBERT。TagBERT通过整合令牌的语义标签，显著提升了查询短语嵌入的质量。在真实大规模电子商务数据集上的实验表明，TagBERT在关键的令牌分类任务上超越了包括BERT、eBERT以及序列到序列变压器模型在内的众多竞争者。

> The major task of any e-commerce search engine is to retrieve the most relevant inventory items, which best match the user intent reflected in a query. This task is non-trivial due to many reasons, including ambiguous queries, misaligned vocabulary between buyers, and sellers, over- or under-constrained queries by the presence of too many or too few tokens. To address these challenges, query reformulation is used, which modifies a user query through token dropping, replacement or expansion, with the objective to bridge semantic gap between query tokens and users' search intent. Early methods of query reformulation mostly used statistical measures derived from token co-occurrence frequencies from selective user sessions having clicks or purchases. In recent years, supervised deep learning approaches, specifically transformer-based neural language models, or sequence-to-sequence models are being used for query reformulation task. However, these models do not utilize the semantic tags of a query token, which are significant for capturing user intent of an e-commerce query. In this work, we pose query reformulation as a token classification task, and solve this task by designing a dependency-aware transformer-based language model, TagBERT, which makes use of semantic tags of a token for learning superior query phrase embedding. Experiments on large, real-life e-commerce datasets show that TagBERT exhibits superior performance than plethora of competing models, including BERT, eBERT, and Sequence-to-Sequence transformer model for important token classification task.

[Arxiv](https://arxiv.org/abs/2507.10385)