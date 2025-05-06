# 应用于电子商务的长尾搜索查询嵌入式检索方法

发布时间：2025年05月03日

`LLM应用`

> Embedding based retrieval for long tail search queries in ecommerce

# 摘要

> 本研究聚焦于在Best Buy实现语义产品搜索，我们对两塔模型架构[14]及训练、评估数据集进行了多项优化。在bestbuy.com上，搜索请求遵循帕累托分布，少数热门请求占据大部分搜索量，而大量长尾请求则因低频发出面临稀疏交互信号的挑战。我们致力于构建服务于这些长尾查询的模型，并通过三项关键优化提升检索效果：首先，引入大型语言模型改善转换信号的稀疏性；其次，基于Best Buy目录数据预训练现成的Transformer模型；第三，在微调过程中结合查询-查询与查询-商品配对策略。此外，我们通过合并微调模型权重进一步优化了评估指标。最后，我们设计了一套评估数据集整理方案，结合人工评估机制持续监控模型性能。实验表明，在线A/B测试中，该召回机制较传统基于术语匹配的召回方法提升了3%的转化率。

> In this abstract we present a series of optimizations we performed on the two-tower model architecture [14], training and evaluation datasets to implement semantic product search at Best Buy. Search queries on bestbuy.com follow the pareto distribution whereby a minority of them account for most searches. This leaves us with a long tail of search queries that have low frequency of issuance. The queries in the long tail suffer from very spare interaction signals. Our current work focuses on building a model to serve the long tail queries. We present a series of optimizations we have done to this model to maximize conversion for the purpose of retrieval from the catalog. The first optimization we present is using a large language model to improve the sparsity of conversion signals. The second optimization is pretraining an off-the-shelf transformer-based model on the Best Buy catalog data. The third optimization we present is on the finetuning front. We use query-to-query pairs in addition to query-to-product pairs and combining the above strategies for finetuning the model. We also demonstrate how merging the weights of these finetuned models improves the evaluation metrics. Finally, we provide a recipe for curating an evaluation dataset for continuous monitoring of model performance with human-in-the-loop evaluation. We found that adding this recall mechanism to our current term match-based recall improved conversion by 3% in an online A/B test.

[Arxiv](https://arxiv.org/abs/2505.01946)